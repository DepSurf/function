# Function: <code>page_mapcount</code>

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
In mm/page_alloc.c (ffffffff81192597)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/shmem.c (ffffffff811a8840)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811b624c)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff811ba10e)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/debug.c:dump_page_badflags
```
```
In mm/memory.c (ffffffff811bda27)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (ffffffff811c2bfa)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffff811cc253)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/swapfile.c (ffffffff811d498b)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff811db805)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff811dfe9c)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff811e5552)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f2e21)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff811f728b)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memory-failure.c (ffffffff81202ec0)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff81276948)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
```
In fs/proc/page.c (ffffffff81288007)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8130e9e4)
Location: include/linux/mm.h:443
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811a2000)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/shmem.c (ffffffff811bf665)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811d01f2)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff811d4548)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff811db3c2)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffff811deb87)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff811e94ec)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811eec7c)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff811fbf11)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff811fecbe)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81204001)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff81212dee)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
```
```
In mm/huge_memory.c (ffffffff812182fc)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121c77d)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81227609)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff812a46c3)
Location: include/linux/mm.h:526
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
In fs/proc/page.c (ffffffff812b5379)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81342d71)
Location: include/linux/mm.h:526
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811b1e61)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/shmem.c (ffffffff811cfc61)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811e0220)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff811e45d7)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff811eaf1d)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffff811ee9a7)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff811fa83c)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ff5ac)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8120c9c1)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812104f6)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81216237)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122515e)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/huge_memory.c (ffffffff8122a89c)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122e19e)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81239bbf)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/task_mmu.c (ffffffff812ba023)
Location: include/linux/mm.h:513
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
In fs/proc/page.c (ffffffff812cabef)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81358b90)
Location: include/linux/mm.h:513
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811b8b31)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/shmem.c (ffffffff811d9395)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff811e9eee)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff811eea0b)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff811f6031)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff811f99ac)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff81205501)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8120a2d8)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8121832b)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff8121aa26)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff81222b93)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81230879)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/huge_memory.c (ffffffff812364c0)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8123a445)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81245016)
Location: include/linux/mm.h:569
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c7761)
Location: include/linux/mm.h:569
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
In fs/proc/page.c (ffffffff812d807f)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8136d400)
Location: include/linux/mm.h:569
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811ca220)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/shmem.c (ffffffff811ee66f)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
```
```
In mm/compaction.c (ffffffff81200249)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81204e7b)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8120dc93)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mlock.c (ffffffff81211dd8)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff8121e4b3)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8122353e)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812331b5)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff81236985)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8123dfea)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124e5b9)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/huge_memory.c (ffffffff81255366)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81259167)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81264f06)
Location: include/linux/mm.h:586
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb361)
Location: include/linux/mm.h:586
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
In fs/proc/page.c (ffffffff812fc661)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81391e89)
Location: include/linux/mm.h:586
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff811f0c61)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81221677)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81225c7d)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8122e720)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/mlock.c (ffffffff81232b8b)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81239449)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8124037b)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff812463a8)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812561dc)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff81259955)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812615b0)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8127238d)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
```
```
In mm/huge_memory.c (ffffffff812791dc)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127d548)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memory-failure.c (ffffffff8128921e)
Location: include/linux/mm.h:628
Inline: True
```
```
In mm/memfd.c (ffffffff81294482)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff81318685)
Location: include/linux/mm.h:628
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
In fs/proc/page.c (ffffffff8132a252)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff813c0ebe)
Location: include/linux/mm.h:628
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff81202abb)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff812346c9)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81239347)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81242632)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mlock.c (ffffffff8124635b)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8124da92)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81254a7b)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8125a7ca)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff8126a6ca)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff8126d565)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81275e13)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8128699d)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
```
```
In mm/huge_memory.c (ffffffff8128d88b)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812921de)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff8129e16e)
Location: include/linux/mm.h:656
Inline: True
```
```
In mm/memfd.c (ffffffff812a8edb)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
```
```
In fs/proc/task_mmu.c (ffffffff8132f595)
Location: include/linux/mm.h:656
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
In fs/proc/page.c (ffffffff8134157a)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff813da21e)
Location: include/linux/mm.h:656
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
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
In mm/filemap.c (ffffffff81219eeb)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81244487)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff8124a3a7)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81251421)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff81258595)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8125f9b0)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81266d24)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff81275834)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffffffff812857f6)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff81288a8f)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81290d2a)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff812a0f2f)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812a81ff)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812acc0b)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff812b9322)
Location: include/linux/mm.h:722
Inline: True
```
```
In mm/memfd.c (ffffffff812c54e3)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81356fe5)
Location: include/linux/mm.h:722
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
In fs/proc/page.c (ffffffff8136998e)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81405e61)
Location: include/linux/mm.h:722
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8122785b)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81252947)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff8125880e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8125f9d1)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff81266a65)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8126e1c0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81275644)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff81284804)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812953b9)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812985ff)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812a0aaa)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff812b233f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812b96df)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812be4d9)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memory-failure.c (ffffffff812cb212)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (ffffffff812d6ef2)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff8136f5b5)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (ffffffff81381bad)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff814209c1)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8125419a)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81282d8e)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff812871b7)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8128fe89)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff81296685)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff8129e912)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a69e3)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff812b69af)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812c8ab7)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812cc16f)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812d549b)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e78df)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff812ee234)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f23fb)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff81301346)
Location: include/linux/mm.h:814
Inline: True
```
```
In mm/memfd.c (ffffffff8130c023)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813b6e05)
Location: include/linux/mm.h:814
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
In fs/proc/page.c (ffffffff813cc1c5)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8146fa5d)
Location: include/linux/mm.h:814
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81be6a3a)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff8128cd87)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff812913b2)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8129a909)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812a1605)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812a9cc8)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b1e83)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff812c2bff)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812d463c)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812d79ff)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812e0f18)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f2f0c)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/huge_memory.c (ffffffff812f98a4)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fe8b3)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff8130d3b0)
Location: include/linux/mm.h:847
Inline: True
```
```
In mm/memfd.c (ffffffff81317ee3)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813c84a5)
Location: include/linux/mm.h:847
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
In fs/proc/page.c (ffffffff813dddfe)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8148a2f5)
Location: include/linux/mm.h:847
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81bd87d0)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81291ff3)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81296906)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8129fde8)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812a7388)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812af153)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b7553)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff812c9a7b)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff812db3f4)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff812def1f)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812e8618)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f904f)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff81305576)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff81313938)
Location: include/linux/mm.h:870
Inline: True
```
```
In mm/memfd.c (ffffffff8131e0d3)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff813cf4e5)
Location: include/linux/mm.h:870
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
In fs/proc/page.c (ffffffff813e4d45)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8148fe45)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81cb9e27)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff812d1709)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff812d7165)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812e33eb)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812e89c5)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/rmap.c (ffffffff812f9aff)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
```
```
In mm/madvise.c (ffffffff8130ea9b)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81322601)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff81326baf)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81330548)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8134355e)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/khugepaged.c (ffffffff8134f3b0)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff8136065e)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff814208c5)
Location: include/linux/mm.h:873
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
In fs/proc/page.c (ffffffff81436915)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff814e78b2)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81e6b48f)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/compaction.c (ffffffff8133115e)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff813369f8)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81344789)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81376941)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8138fbb1)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/mempolicy.c (ffffffff813961f2)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff813a108c)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b5db6)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff813b68fa)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_unmap
```
```
In mm/khugepaged.c (ffffffff813c5f61)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff813dbfa8)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81499625)
Location: include/linux/mm.h:822
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
In fs/proc/page.c (ffffffff814b10b7)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81575c78)
Location: include/linux/mm.h:822
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff81359a29)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/debug.c (ffffffff813ade53)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813bc8fa)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff813f48f1)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff81410544)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/mempolicy.c (ffffffff814161e0)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8142150b)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81435efb)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff81438273)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/khugepaged.c (ffffffff8144aaaf)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff814628a9)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8152d7e9)
Location: include/linux/mm.h:883
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
In fs/proc/page.c (ffffffff81547a37)
Location: include/linux/mm.h:883
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/filemap.c (ffffffff8138b376)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/debug.c (ffffffff813e214e)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813f12e9)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81427ada)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff814494dc)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff814562dd)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8146bbd1)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8146df43)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/huge_memory.c (ffffffff81477dd4)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81480ba5)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff814987c0)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81565c19)
Location: include/linux/mm.h:1128
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
In fs/proc/page.c (ffffffff8157f657)
Location: include/linux/mm.h:1128
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/filemap.c (ffffffff813b4ea0)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/debug.c (ffffffff8140c9bc)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8141bebf)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff814612ed)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81482f37)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_folio_add
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/ksm.c (ffffffff81490d67)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8149ab9d)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_folio
  - mm/migrate.c:add_page_for_migration
```
```
In mm/migrate_device.c (ffffffff8149e90a)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_unmap
```
```
In mm/huge_memory.c (ffffffff814a7553)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814aeb82)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff814c7c22)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159dbf8)
Location: include/linux/mm.h:1211
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
In fs/proc/page.c (ffffffff815b8094)
Location: include/linux/mm.h:1211
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/filemap.c (ffff8000102aee8c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffff8000102eb5fc)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffff8000102f0824)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffff8000102fa130)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffff8000102fda64)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffff800010305550)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff80001030b5b8)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffff80001031ebb0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffff80001033406c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffff800010337248)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffff800010340420)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffff800010352b5c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffff800010359e68)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035fe48)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffff80001036f058)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (ffff80001037be74)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffff800010438cc8)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (ffff80001044ff1c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffff8000105035c8)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/filemap.c (c04daabc)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (c050ead8)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (c0513cfc)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0518fbc)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (c051ce88)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (c05235b4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0527a2c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (c05377dc)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (c053c704)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c0546c68)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:write_protect_page
```
```
In mm/memfd.c (c0566c24)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c060130c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/page.c (c0613160)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (c06bfc4c)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (c0000000003623e0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (c0000000003ac9d4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (c0000000003b5280)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0000000003bf4c0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (c0000000003c8fa0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (c0000000003d25c0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003db714)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (c0000000003f33cc)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (c00000000040cd90)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (c000000000411bf8)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (c00000000041d874)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (c000000000439538)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (c0000000004436f4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (c00000000044abe4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memory-failure.c (c00000000045f9e4)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (c000000000471374)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (c00000000054c578)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (c000000000567be4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (c000000000648120)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffe0001d43ee)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffe0001ff89e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffe000204024)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffe000207762)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mlock.c (ffffffe00020c28a)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffe00021138a)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000214f40)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
```
```
In mm/madvise.c (ffffffe0002205ec)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffe000225312)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffe000230158)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffe0002354da)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
```
In mm/memfd.c (ffffffe00025262e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffe0002d2e3e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In fs/proc/page.c (ffffffe0002e2fee)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffe0003703f2)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8121feab)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff8124af97)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81250e5e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81258021)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8125f0b5)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81266810)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126dc94)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8127ce54)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8128d999)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff81290bdf)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8129908a)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff812aa91f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812b1cbf)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b6ab9)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memory-failure.c (ffffffff812c37f2)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (ffffffff812cf4d2)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81367b95)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (ffffffff8137a18d)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81418fa1)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8121305b)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff8123df37)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff81243d9e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8124dadd)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff812514df)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81259152)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125fcc4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8126ecfe)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8127f726)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff8128285f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff8128ac4a)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff8129c27f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812a303b)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a7c89)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memory-failure.c (ffffffff812b4832)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (ffffffff812c0156)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81358835)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (ffffffff8136ac5d)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81409a21)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8121dc4b)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81248d37)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff8124ebfe)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81255dc1)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8125ce55)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff812645b0)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126ba34)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8127abf4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8128b7a9)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff8128e9ef)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff81296e9a)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff812a872f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812afacf)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b48c9)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memory-failure.c (ffffffff812c1602)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (ffffffff812cd2e2)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81365665)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (ffffffff81377c5d)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff81415141)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
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
In mm/filemap.c (ffffffff8122ccbb)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/compaction.c (ffffffff81258566)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/debug.c (ffffffff8125e57e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8126584f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
```
```
In mm/mlock.c (ffffffff8126c822)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
```
```
In mm/mprotect.c (ffffffff81273f6e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127b3c4)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
```
```
In mm/madvise.c (ffffffff8128a7d5)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8129b5b5)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/mempolicy.c (ffffffff8129e8ef)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/ksm.c (ffffffff812a6c6a)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_search
```
```
In mm/migrate.c (ffffffff812b8a4f)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff812bfe0e)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c52ba)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff812d20c2)
Location: include/linux/mm.h:717
Inline: True
```
```
In mm/memfd.c (ffffffff812de068)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
```
```
In fs/proc/task_mmu.c (ffffffff81378d45)
Location: include/linux/mm.h:717
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
In fs/proc/page.c (ffffffff8138b6fe)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
```
In fs/fuse/dev.c (ffffffff8142bebe)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
</details>
</li>
</ul>

## Differences
