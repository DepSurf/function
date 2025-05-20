# Function: <code>radix_tree_is_internal_node</code>

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
In mm/filemap.c (ffffffff811a181c)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/truncate.c (0)
Location: include/linux/radix-tree.h:59
Inline: True
```
```
In mm/shmem.c (ffffffff811bf6f7)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811c8cd2)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/migrate.c (ffffffff81211af1)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/khugepaged.c (ffffffff8121c6c3)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81262394)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In fs/dax.c (ffffffff812878bd)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - fs/dax.c:dax_unlock_mapping_entry
```
```
In lib/radix-tree.c (ffffffff81435bfc)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_replace_clear_tags
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:__radix_tree_delete_node
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/radix-tree.c:radix_tree_locate_item
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_range_tag_if_tagged
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:radix_tree_node_alloc
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
In mm/filemap.c (ffffffff811b1690)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811be158)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811cfcdb)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811d8dda)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8122e0e7)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81275892)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/radix-tree.c (ffffffff81451114)
Location: include/linux/radix-tree.h:59
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
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
In mm/filemap.c (ffffffff811b78f3)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages
  - mm/filemap.c:find_get_entries
```
```
In mm/page-writeback.c (ffffffff811c6339)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811d9417)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811e12cd)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8123a3c1)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff81282df7)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In lib/idr.c (ffffffff818ecff8)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_replace
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc
```
```
In lib/radix-tree.c (ffffffff818f0f8c)
Location: include/linux/radix-tree.h:61
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:replace_slot
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In mm/filemap.c (ffffffff811cbe7b)
Location: include/linux/radix-tree.h:60
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
In mm/page-writeback.c (ffffffff811db159)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff811ee6ed)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff811f72dd)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff812590e1)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fs-writeback.c (ffffffff812a5947)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:60
Inline: True
```
```
In lib/idr.c (ffffffff81973018)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_replace_ext
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_cmn
```
```
In lib/radix-tree.c (ffffffff819773dc)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:idr_get_free_cmn
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:replace_slot
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In mm/filemap.c (ffffffff811ecfb0)
Location: include/linux/radix-tree.h:60
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
In mm/page-writeback.c (ffffffff811fc411)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/page-writeback.c:tag_pages_for_writeback
```
```
In mm/shmem.c (ffffffff81213b40)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_partial_swap_usage
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/backing-dev.c (ffffffff8121850d)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
```
In mm/khugepaged.c (ffffffff8127d451)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memfd.c (ffffffff8129420d)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/fs-writeback.c (ffffffff812cc520)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:60
Inline: True
```
```
In lib/idr.c (ffffffff819cf5a9)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - lib/idr.c:ida_destroy
  - lib/idr.c:ida_get_new_above
  - lib/idr.c:idr_replace
  - lib/idr.c:idr_for_each
  - lib/idr.c:idr_alloc_u32
```
```
In lib/radix-tree.c (ffffffff819d3b6c)
Location: include/linux/radix-tree.h:60
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag_slot
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup_slot
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:__radix_tree_next_slot
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:replace_slot
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:radix_tree_free_nodes
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:56
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a0cdf8)
Location: include/linux/radix-tree.h:56
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a7c764)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
Inline: True
```
```
In lib/radix-tree.c (ffffffff81ab3a94)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In lib/radix-tree.c (ffffffff815edbcc)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
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
In lib/radix-tree.c (ffffffff816122fc)
Location: include/linux/radix-tree.h:44
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:__radix_tree_create
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:44
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
In lib/radix-tree.c (ffffffff815f5964)
Location: include/linux/radix-tree.h:44
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:44
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
In lib/radix-tree.c (ffffffff81662dc4)
Location: include/linux/radix-tree.h:44
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:44
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
In lib/radix-tree.c (ffffffff8177cf34)
Location: include/linux/radix-tree.h:46
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:46
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:46
Inline: True
```
```
In lib/radix-tree.c (ffffffff820397e4)
Location: include/linux/radix-tree.h:46
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:55
Inline: True
```
```
In lib/radix-tree.c (ffffffff820b7b04)
Location: include/linux/radix-tree.h:55
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:55
Inline: True
```
```
In lib/radix-tree.c (ffffffff82192414)
Location: include/linux/radix-tree.h:55
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_get
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e148)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/radix-tree.c (ffff800010d8d74c)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (c0c61e24)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/radix-tree.c (c0e87d28)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5abec)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/radix-tree.c (c000000000ecfd64)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c6ce)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:of_hwspin_lock_get_id
```
```
In lib/radix-tree.c (ffffffe0008b69b6)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a528e4)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
Inline: True
```
```
In lib/radix-tree.c (ffffffff81a0f9e4)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
Inline: True
```
```
In lib/radix-tree.c (ffffffff81abecd4)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
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
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: include/linux/radix-tree.h:43
Inline: True
```
```
In lib/radix-tree.c (ffffffff81acb194)
Location: include/linux/radix-tree.h:43
Inline: True
Inline callers:
  - lib/radix-tree.c:idr_destroy
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:idr_get_free
  - lib/radix-tree.c:radix_tree_gang_lookup_tag
  - lib/radix-tree.c:radix_tree_gang_lookup
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_next_chunk
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_clear
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:radix_tree_tag_set
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:__radix_tree_lookup
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:radix_tree_insert
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:delete_node
  - lib/radix-tree.c:radix_tree_extend
```
</details>
</li>
</ul>

## Differences
