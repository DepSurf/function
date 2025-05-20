# Function: <code>compound_nr</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122285c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff81238ee1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81241c29)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812454c7)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffffffff8125265a)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125bd1f)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffffffff812745b7)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81281c85)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (ffffffff8128683c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memory_hotplug.c (ffffffff81ac9a60)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812ae1b5)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (ffffffff812c49d1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9cf8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffffffff812d6eb9)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff8136f530)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff8124f33a)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/vmscan.c (ffffffff81267a17)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8126ecea)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81273017)
Location: include/linux/mm.h:917
Inline: True
```
```
In mm/compaction.c (ffffffff81282ad6)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/rmap.c (ffffffff812a5890)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812b403f)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff812e0e62)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812e3625)
Location: include/linux/mm.h:917
Inline: True
```
```
In mm/khugepaged.c (ffffffff812f0963)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812f999d)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812ff60e)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In fs/proc/task_mmu.c (ffffffff813b6bf9)
Location: include/linux/mm.h:917
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff8125961b)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:page_cache_delete
```
```
In mm/truncate.c (ffffffff8126add8)
Location: include/linux/mm.h:956
Inline: True
```
```
In mm/vmscan.c (ffffffff81272437)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8127a100)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8127d6b1)
Location: include/linux/mm.h:956
Inline: True
```
```
In mm/compaction.c (ffffffff8128ccf5)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/rmap.c (ffffffff812b0ced)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff812bfad4)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff812ebc62)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/migrate.c (ffffffff812eea95)
Location: include/linux/mm.h:956
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f3abb)
Location: include/linux/mm.h:956
Inline: True
```
```
In mm/khugepaged.c (ffffffff812fc0da)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130571e)
Location: include/linux/mm.h:956
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b94b)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In fs/libfs.c (ffffffff81351e01)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/buffer.c (ffffffff81367682)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/direct-io.c (ffffffff8136f3f9)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/mpage.c (ffffffff813712fc)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff813bbd12)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c8296)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff81405753)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff81408491)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff81421d69)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8142af1c)
Location: include/linux/mm.h:956
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8142c711)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e5de)
Location: include/linux/mm.h:956
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff814917e8)
Location: include/linux/mm.h:956
Inline: True
```
```
In block/bio.c (ffffffff8155ab4a)
Location: include/linux/mm.h:956
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
In mm/filemap.c (ffffffff8125d96b)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff8126ff8b)
Location: include/linux/mm.h:979
Inline: True
```
```
In mm/vmscan.c (ffffffff81277764)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8127f254)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81282831)
Location: include/linux/mm.h:979
Inline: True
```
```
In mm/compaction.c (ffffffff81291b10)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812972e9)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/page_vma_mapped.c (ffffffff812b303a)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b4c2a)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff812c5234)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff81c2d873)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/migrate.c (ffffffff812f4c25)
Location: include/linux/mm.h:979
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff425)
Location: include/linux/mm.h:979
Inline: True
```
```
In mm/khugepaged.c (ffffffff813030ab)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130cd5b)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff81311fa0)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8131302d)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/libfs.c (ffffffff81358b25)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/buffer.c (ffffffff8136e0c5)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/direct-io.c (ffffffff81375cab)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/mpage.c (ffffffff81377caf)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff813c39a5)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cf3d9)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff8140ba91)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_readpage_inline
```
```
In fs/ext4/inode.c (ffffffff8140e7a5)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8142856b)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81431a8f)
Location: include/linux/mm.h:979
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff814333e0)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ecryptfs/mmap.c (ffffffff814840b2)
Location: include/linux/mm.h:979
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/fuse/file.c (ffffffff8149670b)
Location: include/linux/mm.h:979
Inline: True
```
```
In block/bio.c (ffffffff8156314e)
Location: include/linux/mm.h:979
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
In mm/filemap.c (ffffffff81299c1d)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/filemap.c:page_cache_delete_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/truncate.c (ffffffff812ad3b6)
Location: include/linux/mm.h:983
Inline: True
```
```
In mm/vmscan.c (ffffffff812b5113)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812bd648)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812c1065)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/util.c:copy_huge_page
```
```
In mm/compaction.c (ffffffff812d13d1)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812d7c99)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/page_vma_mapped.c (ffffffff812f4bca)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f6a7a)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/page_alloc.c (ffffffff81309781)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff81d4c15a)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/huge_memory.c (ffffffff81349035)
Location: include/linux/mm.h:983
Inline: True
```
```
In mm/khugepaged.c (ffffffff8134ce1b)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813576d3)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8135d7b1)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff8135fb01)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In fs/libfs.c (ffffffff813a717d)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/buffer.c (ffffffff813bce4e)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/direct-io.c (ffffffff813c210e)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/mpage.c (ffffffff813c4369)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8141226e)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814207ae)
Location: include/linux/mm.h:983
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff8145d2d9)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8146169d)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff8147c29e)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff814852d9)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff81486569)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff814db1f9)
Location: include/linux/mm.h:983
Inline: True
```
```
In fs/fuse/file.c (ffffffff814edfe6)
Location: include/linux/mm.h:983
Inline: True
```
```
In block/bio.c (ffffffff815c6d1f)
Location: include/linux/mm.h:983
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
In kernel/events/uprobes.c (ffffffff812e5deb)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f44d0)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/filemap.c:read_cache_page_gfp
  - mm/filemap.c:read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_get_read_batch
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_lock_entries
  - mm/filemap.c:__filemap_add_folio
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_free_folio
  - mm/filemap.c:__filemap_remove_folio
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page-writeback.c (ffffffff812fef44)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:folio_clear_dirty_for_io
  - mm/page-writeback.c:folio_redirty_for_writepage
  - mm/page-writeback.c:folio_account_redirty
  - mm/page-writeback.c:folio_account_cleaned
  - mm/page-writeback.c:folio_account_dirtied
  - mm/page-writeback.c:folio_write_one
```
```
In mm/folio-compat.c (ffffffff81300a52)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/folio-compat.c:pagecache_get_page
```
```
In mm/readahead.c (ffffffff81301548)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_pages
```
```
In mm/swap.c (ffffffff81303248)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:__folio_activate
  - mm/swap.c:lru_note_cost_folio
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:pagevec_move_tail_fn
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__page_cache_release
```
```
In mm/truncate.c (ffffffff81308d0d)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_mapping_pagevec
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:mapping_evict_folio
```
```
In mm/vmscan.c (ffffffff8130f3ba)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:folio_isolate_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:pageout
  - mm/vmscan.c:__acct_reclaim_writeback
```
```
In mm/shmem.c (ffffffff8131921c)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131dfe5)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/util.c:folio_copy
  - mm/util.c:folio_mapcount
```
```
In mm/compaction.c (ffffffff81330be4)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff813366dc)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/workingset.c:workingset_activation
  - mm/workingset.c:workingset_refault
  - mm/workingset.c:workingset_eviction
```
```
In mm/gup.c (ffffffff81337c8d)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:unpin_user_page_range_dirty_lock
```
```
In mm/memory.c (ffffffff81342dd4)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/mlock.c (ffffffff8134c1d5)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:mlock_folio
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_vma_mapped.c (ffffffff81357d60)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8135bbbe)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory_hotplug.c (ffffffff81f1bb3a)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_io.c (ffffffff81378f54)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/swap_state.c (ffffffff8137bbb0)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8137f0c9)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
```
In mm/swap_slots.c (ffffffff81383dca)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
```
```
In mm/mempolicy.c (ffffffff81396286)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff813a04ca)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b5da6)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff813c079b)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c575f)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff813d54d1)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_migrate
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:charge_memcg
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/hugetlb_cgroup.c (ffffffff813d78c3)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memory-failure.c (ffffffff813da5ce)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff813de2f5)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff813e3750)
Location: include/linux/mm.h:915
Inline: True
```
```
In mm/page_idle.c (ffffffff813e633f)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
```
In fs/libfs.c (ffffffff8142c5e3)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81432729)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_do_switch_wbs
  - fs/fs-writeback.c:inode_do_switch_wbs
```
```
In fs/buffer.c (ffffffff814432cf)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/direct-io.c (ffffffff81448fe3)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/mpage.c (ffffffff8144bc3c)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readahead
```
```
In fs/verity/enable.c (ffffffff814720a1)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/verity/enable.c:read_file_data_page
```
```
In fs/iomap/buffered-io.c (ffffffff81488548)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
  - fs/iomap/buffered-io.c:iomap_write_iter
  - fs/iomap/buffered-io.c:iomap_readahead
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/proc/task_mmu.c (ffffffff81499e73)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff814dbe3a)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e0813)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/ext4/move_extent.c (ffffffff814fe933)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff8150864a)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff8150a0e6)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/hugetlbfs/inode.c (ffffffff815548d3)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff81568dda)
Location: include/linux/mm.h:915
Inline: True
```
```
In fs/fuse/file.c (ffffffff8157ed70)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff81671c53)
Location: include/linux/mm.h:915
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e18f8)
Location: include/linux/mm.h:915
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In kernel/sched/fair.c (ffffffff81152671)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_numa_migrate_memory
```
```
In mm/truncate.c (ffffffff81371413)
Location: include/linux/mm.h:1045
Inline: True
```
```
In mm/shmem.c (ffffffff8138a807)
Location: include/linux/mm.h:1045
Inline: True
```
```
In mm/compaction.c (ffffffff813a7766)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff813c4d55)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/mlock.c:mlock_new_page
  - mm/mlock.c:__munlock_page
  - mm/mlock.c:__mlock_new_page
  - mm/mlock.c:__mlock_page
  - mm/mlock.c:__mlock_page
```
```
In mm/page_vma_mapped.c (ffffffff813d31aa)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d6879)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory_hotplug.c (ffffffff820c39dc)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_io.c (ffffffff813f68e4)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/mempolicy.c (ffffffff8141628b)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8141fcda)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81435eec)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81442a22)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8144a0b1)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/hugetlb_cgroup.c (ffffffff8145d4d6)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/page_isolation.c (ffffffff81464f85)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff8146b120)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/libfs.c (ffffffff814b9c13)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff814d2623)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
```
```
In fs/direct-io.c (ffffffff814d72d3)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/mpage.c (ffffffff814d985a)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8151be5f)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/proc/task_mmu.c (ffffffff8152e117)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff81574dba)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81579a73)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff81599173)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815a313a)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815a468a)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/squashfs/file.c (ffffffff815ee021)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/squashfs/file.c:__readahead_batch
```
```
In fs/hugetlbfs/inode.c (ffffffff815f63a3)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8160c74a)
Location: include/linux/mm.h:1045
Inline: True
```
```
In fs/fuse/file.c (ffffffff81624a30)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_readahead
```
```
In block/bio.c (ffffffff8172d513)
Location: include/linux/mm.h:1045
Inline: True
```
```
In lib/iov_iter.c (ffffffff817d2598)
Location: include/linux/mm.h:1045
Inline: True
Inline callers:
  - lib/iov_iter.c:iter_xarray_populate_pages
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
In mm/truncate.c (ffffffff813a35ce)
Location: include/linux/mm.h:2018
Inline: True
```
```
In mm/shmem.c (ffffffff813bcb61)
Location: include/linux/mm.h:2018
Inline: True
```
```
In mm/compaction.c (ffffffff813db26b)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_vma_mapped.c (ffffffff814070c0)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140b3a0)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/rmap.c:vma_address
```
```
In mm/memory_hotplug.c (ffffffff821479ca)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/ksm.c (ffffffff814548f3)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/khugepaged.c (ffffffff8147ddce)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/hugetlb_cgroup.c (ffffffff81492c53)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/page_isolation.c (ffffffff8149aa52)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff8149ffc4)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/libfs.c (ffffffff814eeb81)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff81508d9d)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff8150d88e)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/direct-io.c (ffffffff8151036e)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8155414e)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/proc/task_mmu.c (ffffffff815664e7)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff815acc5e)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b09cd)
Location: include/linux/mm.h:2018
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff815cfc3e)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff815d9aee)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff815daf9e)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e50e)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff816445f6)
Location: include/linux/mm.h:2018
Inline: True
```
```
In fs/fuse/file.c (ffffffff8165b632)
Location: include/linux/mm.h:2018
Inline: True
```
```
In block/bio.c (ffffffff817697be)
Location: include/linux/mm.h:2018
Inline: True
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
In mm/truncate.c (ffffffff813cd177)
Location: include/linux/mm.h:2073
Inline: True
```
```
In mm/shmem.c (ffffffff813e79b6)
Location: include/linux/mm.h:2073
Inline: True
```
```
In mm/compaction.c (ffffffff81404f87)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/page_vma_mapped.c (ffffffff81433770)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff81437cf0)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/rmap.c:vma_address
```
```
In mm/memory_hotplug.c (ffffffff82229ffa)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/ksm.c (ffffffff8148fb36)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/khugepaged.c (ffffffff814ac669)
Location: include/linux/mm.h:2073
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff814c235e)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/page_isolation.c (ffffffff814ca13f)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/secretmem.c (ffffffff814cf714)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/libfs.c (ffffffff81522b64)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - fs/libfs.c:zero_user_segments
```
```
In fs/buffer.c (ffffffff8153e064)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - fs/buffer.c:zero_user_segments
```
```
In fs/mpage.c (ffffffff815425a7)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/direct-io.c (ffffffff81544817)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff8158a134)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:zero_user_segments
```
```
In fs/proc/task_mmu.c (ffffffff8159e544)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/ext4/inline.c (ffffffff815e5b84)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815e98ff)
Location: include/linux/mm.h:2073
Inline: True
Inline callers:
  - fs/ext4/inode.c:zero_user_segments
```
```
In fs/ext4/move_extent.c (ffffffff816084c7)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff81612817)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff816137c7)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff816679c7)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167db25)
Location: include/linux/mm.h:2073
Inline: True
```
```
In fs/fuse/file.c (ffffffff81695311)
Location: include/linux/mm.h:2073
Inline: True
```
```
In block/bio.c (ffffffff817ab9d7)
Location: include/linux/mm.h:2073
Inline: True
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
In mm/filemap.c (ffff8000102afe6c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffff8000102c9d58)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d40f8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffff8000102d8444)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffff8000102eb218)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f30fc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffff800010309f40)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffff80001031a3bc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (ffff800010320fe8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/migrate.c (ffff80001034f1bc)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (ffff800010367574)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffff80001036d4bc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffff80001037be44)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffff800010438ad8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In arch/arm/mm/flush.c (c031eb88)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/filemap.c (c04dccbc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (c04f3c38)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c04fc2b8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (c04ff6ec)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (c050e88c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0515470)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/swap_state.c (c0539938)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memcontrol.c (c0558d58)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/memfd.c (c0566bec)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:804
Inline: True
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
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6608)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:flush_dcache_icache_hugepage
```
```
In mm/filemap.c (c000000000364e40)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (c000000000386550)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c000000000393414)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (c000000000398244)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (c0000000003ac7bc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b9b40)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (c0000000003d9bfc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (c0000000003ed570)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (c0000000003f64b4)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memory_hotplug.c (c000000000430924)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000433bf0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (c000000000454b80)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (c00000000045d34c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (c000000000471340)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c00000000054c2e0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffe0001d53b4)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffe0001e8f84)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffe0001eff8e)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffe0001f2cda)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffffffe0001ff6da)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffe000205472)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/swap_state.c (ffffffe000222478)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memcontrol.c (ffffffe000245786)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffe00024a226)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffffffe0002525fc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm.h:804
Inline: True
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
In mm/filemap.c (ffffffff8121aeac)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff81231531)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8123a279)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8123db17)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffffffff8124acaa)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125436f)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffffffff8126cc07)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8127a2d5)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (ffffffff8127ee8c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memory_hotplug.c (ffffffff81a688d0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a6795)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (ffffffff812bcfb1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812c22d8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffffffff812cf499)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81367b10)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff8120e0ac)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff812245f1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8122d283)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81230b17)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffffffff8123dc4a)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81246fbf)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffffffff8125ec54)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff8126c1c5)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (ffffffff81270cbc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memory_hotplug.c (ffffffff81a25390)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff81298235)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (ffffffff812ae0f1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812b3328)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffffffff812c011d)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813587b0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff81218c4c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff8122f2d1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81238019)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8123b8b7)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffffffff81248a4a)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125210f)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffffffff8126a9a7)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81278075)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (ffffffff8127cc2c)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memory_hotplug.c (ffffffff81ad4ce0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a45a5)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (ffffffff812badc1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812c00e8)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffffffff812cd2a9)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813655e0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
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
In mm/filemap.c (ffffffff81227d41)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/vmscan.c (ffffffff8123e6e1)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81247664)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8124afc7)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/compaction.c (ffffffff8125827b)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81261abf)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/rmap.c (ffffffff8127a321)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/page_alloc.c (ffffffff81287c65)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/swap_state.c (ffffffff8128c7fc)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/memory_hotplug.c (ffffffff81ae11bb)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b48f5)
Location: include/linux/mm.h:804
Inline: True
```
```
In mm/memcontrol.c (ffffffff812cb511)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:uncharge_page
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0b32)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In mm/memfd.c (ffffffff812de02f)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81378cc0)
Location: include/linux/mm.h:804
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
```
</details>
</li>
</ul>

## Differences
