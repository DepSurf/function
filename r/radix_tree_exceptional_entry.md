# Function: <code>radix_tree_exceptional_entry</code>

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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/radix-tree.h:232
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/shmem.c (ffffffff811c3b85)
Location: include/linux/radix-tree.h:235
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
```
```
In fs/dax.c (ffffffff81287a69)
Location: include/linux/radix-tree.h:235
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/radix-tree.h:235
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/shmem.c (ffffffff811d3bc2)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In fs/dax.c (ffffffff8129bf71)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/radix-tree.h:269
Inline: True
```
```
In lib/radix-tree.c (ffffffff81452004)
Location: include/linux/radix-tree.h:269
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_replace
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/shmem.c (ffffffff811dc399)
Location: include/linux/radix-tree.h:273
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In fs/dax.c (ffffffff812aa487)
Location: include/linux/radix-tree.h:273
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:273
Inline: True
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
In mm/filemap.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/truncate.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/shmem.c (ffffffff811f2213)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/mincore.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In fs/dax.c (ffffffff812cdcb3)
Location: include/linux/radix-tree.h:272
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
```
```
In lib/radix-tree.c (0)
Location: include/linux/radix-tree.h:272
Inline: True
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
In mm/filemap.c (ffffffff811ed9bf)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:page_cache_prev_hole
  - mm/filemap.c:page_cache_next_hole
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:page_cache_tree_insert
```
```
In mm/readahead.c (ffffffff811ffff5)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/swap.c (ffffffff8120321f)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/swap.c:pagevec_remove_exceptionals
```
```
In mm/truncate.c (ffffffff81203794)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/shmem.c (ffffffff8120d52f)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/shmem.c:shmem_seek_hole_data
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_partial_swap_usage
```
```
In mm/workingset.c (ffffffff812255bc)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In mm/mincore.c (ffffffff81231d21)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/madvise.c (ffffffff81244d77)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
```
In mm/khugepaged.c (ffffffff8127b39f)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In mm/memcontrol.c (ffffffff8127fce1)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff812f83eb)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:unlock_mapping_entry
  - fs/dax.c:__get_unlocked_mapping_entry
```
```
In fs/proc/task_mmu.c (ffffffff81319815)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/radix-tree.c (ffffffff819d3fc8)
Location: include/linux/radix-tree.h:276
Inline: True
Inline callers:
  - lib/radix-tree.c:__radix_tree_delete
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_split
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:radix_tree_join
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_replace
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:__radix_tree_insert
  - lib/radix-tree.c:radix_tree_extend
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
