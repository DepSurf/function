# Function: <code>PageCompound</code>

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
In kernel/futex.c (ffffffff810ffc23)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page_alloc.c (ffffffff81192572)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
```
```
In mm/swap.c (ffffffff8119d47a)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff811a2330)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/compaction.c (ffffffff811b57a3)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/hugetlb.c (ffffffff811daaa6)
Location: include/linux/page-flags.h:422
Inline: True
```
```
In mm/sparse.c (ffffffff811e3900)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff811e46e5)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/ksm.c:page_trans_compound_anon
  - mm/ksm.c:page_trans_compound_anon
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/slub.c (ffffffff811e8ad4)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/slub.c:ksize
  - mm/slub.c:kfree
```
```
In mm/huge_memory.c (ffffffff811f70f8)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8120259c)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/direct-io.c (ffffffff81249890)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/page.c (ffffffff81288242)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
```
In block/bio.c (ffffffff813b19e9)
Location: include/linux/page-flags.h:422
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_check_pages_dirty
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
In kernel/futex.c (ffffffff811077f8)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811a2000)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811a76e4)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811b2a17)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff811b7e32)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff811bf665)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff811c49ba)
Location: include/linux/page-flags.h:155
Inline: True
```
```
In mm/compaction.c (ffffffff811cfc33)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811d44da)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff811d49bd)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811db39f)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffff811df238)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff811e94ec)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff811eec68)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff811fbf11)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff811fecbe)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff81202356)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81203ee8)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/slub.c (ffffffff8120aeb1)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
```
```
In mm/migrate.c (ffffffff81212dee)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812182fc)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121bf66)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81221241)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff81226a00)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/direct-io.c (ffffffff81272538)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812a46c3)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812b5691)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81342d71)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff813f650c)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8110efc3)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811b1e61)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811b7ad4)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811c3099)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff811c8494)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff811cfd0f)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff811d4aca)
Location: include/linux/page-flags.h:158
Inline: True
```
```
In mm/compaction.c (ffffffff811dfc74)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811e452f)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff811e4a27)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811eaf03)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffff811ef04c)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff811fa83c)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff811ff598)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8120c9c1)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812104f6)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8121418d)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81215ed7)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8121cefc)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
```
```
In mm/migrate.c (ffffffff8122515e)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8122a89c)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122d712)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81233985)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff81238fcf)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/block_dev.c (ffffffff8128378c)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff81286058)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812ba023)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812caf18)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81358b90)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8140feec)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8111018f)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811b8b31)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff811bf907)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811cb524)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811d0e39)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff811d9451)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff811dd8ea)
Location: include/linux/page-flags.h:158
Inline: True
```
```
In mm/compaction.c (ffffffff811e997f)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
```
In mm/debug.c (ffffffff811ee98b)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff811ef03f)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f6016)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff811f9fe9)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81205501)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8120a250)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8120c43f)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/hugetlb.c (ffffffff8121832b)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8121aa26)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8121f584)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81222b93)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81228fdc)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff81230879)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812364c0)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81239f98)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8123f233)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In mm/memory-failure.c (ffffffff81245460)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/block_dev.c (ffffffff81290dc2)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812936a2)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812c7761)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812d83b5)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8136d400)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff8141d86a)
Location: include/linux/page-flags.h:158
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8111b8dc)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811ca220)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811d4434)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff811e08c4)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff811e6329)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff811ee725)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff811f336a)
Location: include/linux/page-flags.h:159
Inline: True
```
```
In mm/compaction.c (ffffffff811ffccb)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81204dfb)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8120610a)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120dc77)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8121247e)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8121e4b3)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff812234b2)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff812261e3)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81229bb9)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812331b5)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff81236985)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse.c (ffffffff8123a7ba)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff8123dfea)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81242ee7)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff8124b4b6)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81254626)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81259750)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8125ef93)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812653e6)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/block_dev.c (ffffffff812b3acf)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812b6576)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff812eb361)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812fcab5)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81391e89)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff814486fa)
Location: include/linux/page-flags.h:159
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff811283b1)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff811f0c61)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811f5e88)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff81202133)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8120789b)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff8120f3ac)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff81214595)
Location: include/linux/page-flags.h:154
Inline: True
```
```
In mm/compaction.c (ffffffff812211cf)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81225c7d)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8122641f)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122e6f7)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff812331d8)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81239449)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8124037b)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81246326)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff81247c65)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8124ae72)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812587a2)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff81259955)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8125dd38)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff812615b0)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812688c6)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff8126e03a)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81278475)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127d4ad)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8128310c)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8128921e)
Location: include/linux/page-flags.h:154
Inline: True
```
```
In mm/memfd.c (ffffffff81294482)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/block_dev.c (ffffffff812dc37d)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812de10d)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff81318685)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8132a6d4)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff813c0ebe)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff81479307)
Location: include/linux/page-flags.h:154
Inline: True
Inline callers:
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81133c91)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff81202abb)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81207b24)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/swap.c (ffffffff81214ab3)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8121a41d)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:move_active_pages_to_lru
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/shmem.c (ffffffff81221bdc)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff81227465)
Location: include/linux/page-flags.h:155
Inline: True
```
```
In mm/compaction.c (ffffffff8123421a)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_suitable
```
```
In mm/debug.c (ffffffff81239347)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8123a77b)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124260a)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff812469a6)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8124da92)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81254a7b)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8125a746)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8125c23a)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8126088c)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8126ce74)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:free_huge_page
```
```
In mm/mempolicy.c (ffffffff8126d565)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse.c (ffffffff8127258e)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/ksm.c (ffffffff81275e13)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8127d366)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
```
```
In mm/migrate.c (ffffffff81282eaa)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128cac5)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81291bec)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8129915c)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8129e16e)
Location: include/linux/page-flags.h:155
Inline: True
```
```
In mm/memfd.c (ffffffff812a8edb)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/block_dev.c (ffffffff812f1acd)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_direct_IO_simple
```
```
In fs/direct-io.c (ffffffff812f37ad)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_complete
```
```
In fs/proc/task_mmu.c (ffffffff8132f595)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81341a2f)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff813da21e)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
```
In block/bio.c (ffffffff81499a42)
Location: include/linux/page-flags.h:155
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8113ebf6)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffff81219eeb)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81223d62)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8122c7bd)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff81231449)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff812371e5)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffff81243fb1)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124a3a7)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8124ba91)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812513d4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81258c32)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8125f9b0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81266d24)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff8126ddd2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff81275826)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/swap_state.c (ffffffff8127741a)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8127a17e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812857f6)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81288a8f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812916e6)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff81298a3f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812a0f2f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a77c5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812acb4d)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b4531)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b9322)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/memfd.c (ffffffff812c54e3)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81356fe5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81369e55)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81405e61)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814c7b2f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8114a878)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121a7e8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8122785b)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81231af2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8123a9dd)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8123f509)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff81245455)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffff81252471)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff812587d4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81259f81)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125f984)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff81267102)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8126e1c0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81275644)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff8127cbf2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff812847f6)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81286efa)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81289c5e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812953b9)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff812985ff)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812a1466)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812a88bd)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812ae968)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b8c65)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812be437)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c5e51)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812cbed4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff812d6ef2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff8136f5b5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81382075)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff814209c1)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814e0c2f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8115b39a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81247200)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125419a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8125e6b2)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff81265448)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In mm/shmem.c (ffffffff8126cd4c)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff81272fa5)
Location: include/linux/page-flags.h:194
Inline: True
```
```
In mm/compaction.c (ffffffff81282825)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8128705b)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81287db8)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/memory.c (ffffffff8128fe3c)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff81296ab6)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8129e912)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a1a18)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a6b19)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812b4087)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff812b69a1)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812b947a)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812bcb92)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812cb55f)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/mempolicy.c (ffffffff812cc16f)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812d6377)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff812ddc1e)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
```
```
In mm/migrate.c (ffffffff812e40a2)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ed815)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff812f23fb)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff812fbb39)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81302086)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff8130c023)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813b6e05)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813cc6a5)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8146fa5d)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff8153fa82)
Location: include/linux/page-flags.h:194
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff811574dc)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8125187c)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81be6a3a)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81268737)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81270071)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812777f1)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff8127d645)
Location: include/linux/page-flags.h:196
Inline: True
```
```
In mm/compaction.c (ffffffff8128c946)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8129130b)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8129218a)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129a8bc)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a1926)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812a9cc8)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad2d5)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b1fb9)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812bfb14)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff812c2bf1)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812c4e13)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812c86c2)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812d717f)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/mempolicy.c (ffffffff812d79ff)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812e1e8c)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff812e6bd5)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
```
```
In mm/migrate.c (ffffffff812efd35)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f9300)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff812fe8b3)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff81307789)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8130e891)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff81317ee3)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8138afb0)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:headpage_already_acct
  - fs/io_uring.c:headpage_already_acct
```
```
In fs/proc/task_mmu.c (ffffffff813c84a5)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813de307)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8148a2f5)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff8155c2a2)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/events/uprobes.c (ffffffff812556cc)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81bd87d0)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8126e4d1)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8127510f)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127c651)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812827c5)
Location: include/linux/page-flags.h:196
Inline: True
```
```
In mm/compaction.c (ffffffff8129184a)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8129683b)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81297ed6)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff8129fca9)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a70e6)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812af153)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2506)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b7689)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff812c5274)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff812c9a6d)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff812cbaa7)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff812cf072)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812db3f4)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff812def1f)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812e9629)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff812ee387)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
```
```
In mm/migrate.c (ffffffff812f56ba)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ff4d5)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff81305576)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8130df0a)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81314d3b)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff8131e0d3)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/io_uring.c (ffffffff8139172b)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/proc/task_mmu.c (ffffffff813cf4e5)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff813e50ec)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8148fe45)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff81564b52)
Location: include/linux/page-flags.h:196
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/events/uprobes.c (ffffffff8129137c)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81cb9e27)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff812ab4d9)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:lru_cache_add
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff812b23e7)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812bf1d1)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/util.c (ffffffff812c0935)
Location: include/linux/page-flags.h:210
Inline: True
```
```
In mm/compaction.c (ffffffff812d10d6)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff812d7079)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812d82ec)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:unpin_user_page_range_dirty_lock
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (ffffffff812e329f)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812e85e1)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec_fill
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/page_vma_mapped.c (ffffffff812f40f6)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f9d99)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_mlock
  - mm/rmap.c:page_mlock
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff813097c1)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/madvise.c (ffffffff8130ea8d)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff81310b9e)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81314612)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff81322601)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff81326baf)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81331565)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (ffffffff81334270)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff8133fcbb)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813490e5)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:is_transparent_hugepage
```
```
In mm/khugepaged.c (ffffffff8134f3b0)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81358d69)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81360ddb)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/io_uring.c (ffffffff813df62a)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
  - fs/io_uring.c:io_buffer_account_pin
```
```
In fs/proc/task_mmu.c (ffffffff814208c5)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81436cbc)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff814e78b2)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff815c8ed2)
Location: include/linux/page-flags.h:210
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/events/uprobes.c (ffffffff812e694d)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81e6b48f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/swap.c (ffffffff813052c5)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_folio
  - mm/swap.c:folio_add_lru
  - mm/swap.c:folio_mark_accessed
  - mm/swap.c:folio_rotate_reclaimable
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffff8130d365)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8131ae8e)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_writepage
```
```
In mm/compaction.c (ffffffff81331bb1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/debug.c (ffffffff813368f5)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813381f2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff81344612)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff8134c6e3)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff8135d459)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
```
```
In mm/page_alloc.c (ffffffff8136a3e2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/madvise.c (ffffffff813768bf)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8137b956)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8137faa2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/hugetlb.c (ffffffff8138fbb1)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
```
```
In mm/mempolicy.c (ffffffff813961f2)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff813a23ca)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b5db6)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff813b6887)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c0661)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_in_file
  - mm/huge_memory.c:split_huge_pages_pid
```
```
In mm/khugepaged.c (ffffffff813c5e9c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813d2f87)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dc432)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff813de2c0)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In fs/proc/task_mmu.c (ffffffff81499625)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff814b151c)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81575c78)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff81673f9e)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In io_uring/io_uring.c (ffffffff816cd26f)
Location: include/linux/page-flags.h:314
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
  - io_uring/io_uring.c:io_buffer_account_pin
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
In kernel/events/uprobes.c (ffffffff8135043d)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff81359a2c)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/shmem.c (ffffffff8138ccd1)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/compaction.c (ffffffff813a745d)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813adb85)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813af999)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813bc769)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff813c527a)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/rmap.c (ffffffff813d7faf)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_new_anon_rmap
  - mm/rmap.c:page_add_anon_rmap
```
```
In mm/page_alloc.c (ffffffff813e653f)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcp_prepare
```
```
In mm/madvise.c (ffffffff813f48f1)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81410549)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff814161e3)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81422026)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate.c (ffffffff81435f04)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8143a40a)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81442dab)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144aab6)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff814587b0)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8146207f)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff81464f50)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/memfd.c (ffffffff81471657)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff8152d7f1)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81547ec5)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In block/bio.c (ffffffff8172fc0e)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In io_uring/rsrc.c (ffffffff817a095f)
Location: include/linux/page-flags.h:293
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
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
In kernel/events/uprobes.c (ffffffff8138166e)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8138b379)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/compaction.c (ffffffff813dac8e)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff813e1f15)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e4109)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813f1157)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:zap_pte_range
```
```
In mm/page_alloc.c (ffffffff8141bced)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff81427add)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8143b065)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff814494df)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81456d10)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate.c (ffffffff8146bbd4)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146fd5a)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147867a)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_pid
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81480b29)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff8148e375)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8149908a)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff8149aa20)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/memfd.c (ffffffff814a5b98)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81565c21)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8157fac7)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In block/bio.c (ffffffff8176be3c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
```
```
In io_uring/rsrc.c (ffffffff817e1bbc)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
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
In kernel/events/uprobes.c (ffffffff813aa9ff)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff813b4ea3)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/compaction.c (ffffffff81404b8b)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8140c741)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8141bec3)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:zap_pte_range
```
```
In mm/page_alloc.c (ffffffff81446e77)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff814612f0)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81474b35)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81482f3a)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81491817)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:remove_stable_node
```
```
In mm/migrate.c (ffffffff8149aba0)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8149efda)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_device_unmap
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a7556)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814aeb09)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814bdbe5)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c8777)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff814ca110)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/page_isolation.c:isolate_single_pageblock
```
```
In mm/memfd.c (ffffffff814d6b45)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff8159dc01)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff815b84da)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In block/bio-integrity.c (ffffffff817f868b)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - block/bio-integrity.c:bio_integrity_unpin_bvec
```
```
In io_uring/rsrc.c (ffffffff81825f75)
Location: include/linux/page-flags.h:289
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
  - io_uring/rsrc.c:io_buffer_account_pin
```
```
In net/ipv4/tcp.c (ffffffff81fce525)
Location: include/linux/page-flags.h:289
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
In virt/kvm/arm/mmu.c (ffff8000100cad28)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In kernel/futex.c (ffff8000101b7d18)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffff8000102a5c3c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffff8000102aee8c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffff8000102c17a4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffff8000102cb91c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffff8000102d0d14)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffff8000102d83c8)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffff8000102eaffc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffff8000102f07ac)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffff8000102f1a4c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fa10c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffff8000102fe364)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffff800010305550)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff80001030b5b8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffff8000103147c0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffff80001031eb38)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffff800010321910)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffff800010324cd4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffff8000103362e0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:alloc_gigantic_page
```
```
In mm/mempolicy.c (ffff800010337248)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffff800010340d70)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffff80001034a2c0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffff800010352b5c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff80001035933c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035fdbc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffff800010368b5c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff80001036f558)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffff80001037be74)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffff800010438cc8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffff8000104501d4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffff8000105035c8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffff8000105dd778)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca068)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
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
In arch/arm/mm/flush.c (c031ec3c)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In kernel/events/uprobes.c (c04d4e4c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04daabc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c04ecb00)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (c04f577c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/util.c (c04ff6a8)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (c050e6e8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (c0513cfc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0518fbc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (c051ce88)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (c05235b4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0527a2c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (c052ea88)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (c05377dc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053c704)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c0546c68)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:write_protect_page
```
```
In mm/slub.c (c054ebf4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/memfd.c (c0566c24)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c060130c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/page.c (c0613160)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (c06bfc4c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (c078abb4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In arch/powerpc/mm/mem.c (c0000000000874f0)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a65a8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:flush_dcache_icache_hugepage
```
```
In kernel/futex.c (c00000000021d310)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c000000000358b9c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c0000000003623e0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (c00000000037b570)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (c000000000388a94)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (c000000000390f04)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (c000000000398198)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (c0000000003ac444)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (c0000000003b5120)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0000000003b6034)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bf480)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (c0000000003c9b3c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (c0000000003d25c0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003db714)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (c0000000003e5f10)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (c0000000003f334c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (c0000000003f7094)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (c0000000003fadd8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (c000000000410bbc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/mempolicy.c (c000000000411bf8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (c00000000041e5c0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (c000000000429198)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (c00000000043452c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000442780)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (c00000000044ab50)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c000000000456f90)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c0000000004610b4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (c000000000471374)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c00000000054c578)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (c0000000005681d0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (c000000000648120)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (c00000000076f044)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffe00013c9cc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffe0001d43ee)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffe0001e2cc8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
  - mm/swap.c:__put_page
```
```
In mm/vmscan.c (ffffffe0001ea5b0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/util.c (ffffffe0001f2c94)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffe0001ff4e0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffe000203fbc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffe000207762)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffe00020c28a)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffe00021138a)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000214f40)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
```
In mm/page_alloc.c (ffffffe00021b108)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffe0002205ec)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe000225312)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffe0002322c0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__free_huge_page
```
```
In mm/ksm.c (ffffffe0002354da)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
```
In mm/slub.c (ffffffe00023bc1c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/memfd.c (ffffffe00025262e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffe0002d2e3e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/page.c (ffffffe0002e2fee)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffe0003703f2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffe000420822)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81142e98)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81212e38)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121feab)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8122a142)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8123302d)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff81237b59)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff8123daa5)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffff8124aac1)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81250e24)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff812525d1)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81257fd4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8125f752)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81266810)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126dc94)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81275242)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127ce46)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127f54a)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128223e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128d999)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff81290bdf)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81299a46)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812a0e9d)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812a6f48)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b1245)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b6a17)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812be431)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c44b4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff812cf4d2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81367b95)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8137a655)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81418fa1)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814d920f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff811361f8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81205ba8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121305b)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff8121d262)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff812260cd)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff8122ab99)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff81230aa5)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffff8123da61)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff81243d64)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81245368)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124dab5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff81251b72)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81259152)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125fcc4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff8126719c)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8126ecf0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127136a)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff81273d5e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8127f726)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8128285f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8128b606)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8129297d)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff81298985)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a2615)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a7be7)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812af4f5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812b54f4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff812c0156)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81358835)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8136b125)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81409a21)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814c9bbf)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff81140d48)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81210bd8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8121dc4b)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81227ee2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff81230dcd)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff812358f9)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff8123b845)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffff81248861)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8124ebc4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff81250371)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255d74)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8125d4f2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812645b0)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126ba34)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81272fe2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8127abe6)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8127d2ea)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128004e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128b7a9)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8128e9ef)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81297856)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff8129ecad)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812a4d58)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812af055)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b4827)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812bc241)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812c22c4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff812cd2e2)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81365665)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81378125)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81415141)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814d529f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
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
In kernel/futex.c (ffffffff8114df9e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121faeb)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff8122ccbb)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/swap.c (ffffffff81237222)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:deactivate_page
  - mm/swap.c:deactivate_file_page
  - mm/swap.c:__lru_cache_add
  - mm/swap.c:activate_page
  - mm/swap.c:rotate_reclaimable_page
```
```
In mm/vmscan.c (ffffffff8124021d)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/vmscan.c:move_pages_to_lru
```
```
In mm/shmem.c (ffffffff81245ba9)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In mm/util.c (ffffffff8124af55)
Location: include/linux/page-flags.h:186
Inline: True
```
```
In mm/compaction.c (ffffffff81258086)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:pageblock_skip_persistent
```
```
In mm/debug.c (ffffffff8125e544)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8125fcfc)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81265804)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
```
```
In mm/mlock.c (ffffffff8126ced8)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81273f6e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127b3c4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/page_alloc.c (ffffffff81282b44)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_ok
```
```
In mm/madvise.c (ffffffff8128a7c7)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swap_state.c (ffffffff8128ceb3)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/swapfile.c (ffffffff8128fd3e)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8129b5b5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:PageHuge
```
```
In mm/mempolicy.c (ffffffff8129e8ef)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812a7632)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/slub.c (ffffffff812aedb9)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
```
```
In mm/migrate.c (ffffffff812b58b4)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bf3a5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/huge_memory.c:page_trans_huge_mapcount
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c51fa)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812cca12)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff812d2d4f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/memfd.c (ffffffff812de068)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81378d45)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8138bbd5)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8142bebe)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
```
In block/bio.c (ffffffff814ede4f)
Location: include/linux/page-flags.h:186
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:bio_set_pages_dirty
```
</details>
</li>
</ul>

## Differences
