# Function: <code>__page_mapcount</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4930)
Location: mm/util.c:410
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - mm/memory-failure.c:memory_failure
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811c4930-ffffffff811c49a1: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4a40)
Location: mm/util.c:413
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - mm/memory-failure.c:memory_failure
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811d4a40-ffffffff811d4ab1: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811dd860)
Location: mm/util.c:497
Inline: False
Direct callers:
  - mm/filemap.c:__delete_from_page_cache
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:__handle_mm_fault
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811dd860-ffffffff811dd8d1: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f32e0)
Location: mm/util.c:497
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/shmem.c:shmem_add_seals
  - mm/shmem.c:shmem_add_seals
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:handle_pte_fault
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff811f32e0-ffffffff811f3351: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214520)
Location: mm/util.c:533
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:handle_pte_fault
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81214520-ffffffff8121458b: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812273f0)
Location: mm/util.c:536
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:__handle_mm_fault
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - mm/memfd.c:memfd_fcntl
  - mm/memfd.c:memfd_fcntl
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff812273f0-ffffffff8122745e: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812370e0)
Location: mm/util.c:579
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812370e0-ffffffff81237152: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245350)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81245350-ffffffff812453c2: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272ea0)
Location: mm/util.c:712
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81272ea0-ffffffff81272f12: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d580)
Location: mm/util.c:725
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/mlock.c:__putback_lru_fast_prepare
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8127d580-ffffffff8127d5e7: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282710)
Location: mm/util.c:715
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff81282710-ffffffff81282777: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0830)
Location: mm/util.c:736
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/rmap.c:make_device_exclusive_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812c0830-ffffffff812c0897: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131d7b0)
Location: mm/util.c:815
Inline: False
Direct callers:
  - mm/filemap.c:filemap_unaccount_folio
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_wp
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate_device.c:migrate_vma_unmap
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/memory-failure.c:hwpoison_user_mappings
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8131d7b0-ffffffff8131d887: __page_mapcount (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8280)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffff8000102d8280-ffff8000102d8310: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff3ac)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:unmap_page_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:reuse_swap_page
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:write_protect_page
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c04ff3ac-c04ff404: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397fb0)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:zap_pte_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
c000000000397fb0-c000000000398098: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f2b96)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:unmap_page_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:page_mapcount_is_zero
  - mm/rmap.c:page_referenced
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/swapfile.c:reuse_swap_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:ksm_do_scan
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffe0001f2b96-ffffffe0001f2c08: __page_mapcount (STB_GLOBAL)
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
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d9a0)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8123d9a0-ffffffff8123da12: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812309a0)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_protection_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff812309a0-ffffffff81230a12: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b740)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8123b740-ffffffff8123b7b2: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __page_mapcount(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124ae50)
Location: mm/util.c:684
Inline: False
Direct callers:
  - mm/filemap.c:unaccount_page_cache_page
  - mm/compaction.c:isolate_migratepages_block
  - mm/debug.c:__dump_page
  - mm/memory.c:do_numa_page
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:__munlock_isolated_page
  - mm/mprotect.c:change_pte_range
  - mm/rmap.c:try_to_unmap
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/mempolicy.c:migrate_page_add
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/ksm.c:stable_tree_search
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/khugepaged.c:khugepaged
  - mm/memfd.c:memfd_wait_for_pins
  - mm/memfd.c:memfd_wait_for_pins
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/page.c:kpagecount_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
```
**Symbols:**

```
ffffffff8124ae50-ffffffff8124aec2: __page_mapcount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
