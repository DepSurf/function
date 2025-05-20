# Function: <code>count_vm_event</code>

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
In mm/filemap.c (ffffffff8118fad5)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page_alloc.c (ffffffff81196739)
Location: include/linux/vmstat.h:39
Inline: True
```
```
In mm/swap.c (ffffffff8119e031)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811a0ea8)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:zone_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/shmem.c (ffffffff811aae0a)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff811bec15)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/mlock.c (ffffffff811c2c12)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:mlock_vma_page
```
```
In mm/page_io.c (ffffffff811d235b)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
```
```
In mm/hugetlb.c (ffffffff811db1ef)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffff811f317c)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff811f4ddc)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/dax.c (ffffffff8125dde8)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
```
In fs/drop_caches.c (ffffffff8126ffe7)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff811a3a3b)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page_alloc.c (ffffffff811aa248)
Location: include/linux/vmstat.h:39
Inline: True
```
```
In mm/swap.c (ffffffff811b38c5)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811bc0cb)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811c0f64)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff811d1b64)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff811daa7d)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff811de7a5)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_io.c (ffffffff811f01bb)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff811f9433)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffff81212efd)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812187fd)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8121952d)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In fs/dax.c (ffffffff81287ebe)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
```
In fs/drop_caches.c (ffffffff8129b7ff)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff811b3d97)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/page_alloc.c (ffffffff811ba778)
Location: include/linux/vmstat.h:39
Inline: True
```
```
In mm/swap.c (ffffffff811c3f55)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811cc79b)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811d1563)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff811e1aab)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff811ea5f1)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff811ee5c5)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_io.c (ffffffff81200b7f)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff8120a769)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffff8122526d)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff8122ad9d)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122baad)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In fs/dax.c (ffffffff8129c9d3)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/drop_caches.c (ffffffff812b03bf)
Location: include/linux/vmstat.h:39
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff811ba8b4)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811bd46e)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page_alloc.c (ffffffff811c27b8)
Location: include/linux/vmstat.h:38
Inline: True
```
```
In mm/swap.c (ffffffff811cc345)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811d53f5)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811d9dc1)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff811eb871)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff811f608d)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff811f9833)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_io.c (ffffffff8120b7cd)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/hugetlb.c (ffffffff81215af5)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffff81230977)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff8123691b)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238c38)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812aafb0)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/drop_caches.c (ffffffff812bd830)
Location: include/linux/vmstat.h:38
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff811ce06f)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811d2093)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page_alloc.c (ffffffff811d75c8)
Location: include/linux/vmstat.h:49
Inline: True
```
```
In mm/swap.c (ffffffff811e1335)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff811ea925)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:putback_lru_page
  - mm/vmscan.c:putback_lru_page
```
```
In mm/shmem.c (ffffffff811efaa6)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81201bed)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff8120dcf5)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81211c63)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_io.c (ffffffff81224cf3)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff81226200)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/hugetlb.c (ffffffff81230723)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/migrate.c (ffffffff8124e6fa)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812558eb)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81258acd)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/dax.c (ffffffff812ce81a)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
```
In fs/drop_caches.c (ffffffff812e1100)
Location: include/linux/vmstat.h:49
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff811efbf7)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff811f3c98)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page_alloc.c (ffffffff811f890c)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In mm/swap.c (ffffffff81201eae)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8120c137)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81211249)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81222fb7)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff81230299)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff812329a3)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_io.c (ffffffff81247293)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff8124877d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff81272576)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff81279785)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127a8cb)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In fs/dax.c (ffffffff812f8e4c)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff8130d32d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff81201e52)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8120492b)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/page_alloc.c (ffffffff8120ae82)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In mm/swap.c (ffffffff8121482e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8121eddb)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81223196)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81236007)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff81242c49)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81245f25)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_io.c (ffffffff8125b6e7)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff8125cd53)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff81286b68)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff8128de05)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8128eecb)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In fs/dax.c (ffffffff8130da3c)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff81322c1d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff81217c7b)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8121c09e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff812244ec)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8122e45e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812331b9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff812474f9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff81254aea)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff812583b7)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81271142)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff81276859)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff81277eff)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812a110e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812a8785)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812aa95e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81335c65)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff8134a63d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff8122554e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81229a30)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8123227c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8123c5ee)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812413da)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81255999)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff8126304a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81266887)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff8127ff82)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff81286349)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812879ef)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812b251e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812b9cf9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bbf02)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81349865)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff813628dd)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff8125352c)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81256883)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff81260068)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff8126ad54)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8126dc35)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff8128411b)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff81294e2a)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81296967)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff812b255d)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff812b8621)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812b99b7)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812e7abe)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812ee899)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff812f13f8)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8138f4ff)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff813a86ad)
Location: include/linux/vmstat.h:68
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff8125e145)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8126141a)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81275794)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81279972)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff8128e228)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff8129f6ae)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/page_alloc.c (ffffffff812be085)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff812c3d0c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812c541d)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812f2eae)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812f9f11)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:get_huge_zero_page
  - mm/huge_memory.c:get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff812fd976)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a0b8a)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff813b9a2d)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108e64b)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff81260e21)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81265c56)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8127aab4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127ead5)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff812938b1)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff812a46ae)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_reuse
```
```
In mm/page_alloc.c (ffffffff812c33b0)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff812cab11)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff812cc0d7)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812f922b)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff81300cb8)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813046c8)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813a7d96)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff813c0b8d)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109e12f)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff8129d88c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff812a2486)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812b8b14)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812bc654)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_alloc_hugepage
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff812d3d31)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff812e5961)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/page_alloc.c (ffffffff81307108)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff8130fb20)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff813112c5)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/huge_memory.c (ffffffff8134a958)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134e3fe)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813f76ca)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff814109fd)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b1a6e)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff812f48ee)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff812f9fc2)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8130574c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff813145b4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff813187b4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81332c01)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff81347c71)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/page_alloc.c (ffffffff8136f1f4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff8137a540)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/swap_state.c (ffffffff8137c23d)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/zswap.c (ffffffff813855e0)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff813a335a)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff813c1878)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c5e92)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:khugepaged_scan_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/dax.c (ffffffff8146a4ad)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff8148636c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cc1d6)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff8135e8f7)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff813646f2)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8136f887)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff813886f4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff8138c561)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff813a9939)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff813c0061)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/page_alloc.c (ffffffff813eb764)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff813f7fe4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:count_swpout_vm_event
```
```
In mm/swap_state.c (ffffffff813f99dd)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/zswap.c (ffffffff81403350)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff81422ffa)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81443957)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff8144a8a0)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/dax.c (ffffffff814faf5d)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff81519c38)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cf7f9)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff813917ef)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81396bc5)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff813a19a7)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff813ba884)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813beb8d)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff813dcbd9)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff813f4d67)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/page_alloc.c (ffffffff81420784)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff8142b20b)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage_bdev_sync
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8142ca0c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/zswap.c (ffffffff814368e3)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_load
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/ksm.c (ffffffff81458050)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81478e9c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff81480adc)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/dax.c (ffffffff815323b0)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff8155153f)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d7ed9)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__split_large_page
```
```
In mm/filemap.c (ffffffff813bb576)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff813c0935)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff813cb62b)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
```
In mm/vmscan.c (ffffffff813e39a4)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/shmem.c (ffffffff813ea9e9)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
```
```
In mm/compaction.c (ffffffff81406b2b)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff814213d7)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
```
```
In mm/page_alloc.c (ffffffff8144d544)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff814649c9)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio
  - mm/page_io.c:swap_read_folio_bdev_sync
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_writepage_bdev_sync
  - mm/page_io.c:swap_writepage_fs
```
```
In mm/swap_state.c (ffffffff8146612a)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:swap_cache_get_folio
```
```
In mm/zswap.c (ffffffff814713ec)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_memcg_cb
```
```
In mm/ksm.c (ffffffff814929d3)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff814a847c)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_get_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
```
In mm/khugepaged.c (ffffffff814aeabc)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/dax.c (ffffffff815672a0)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/drop_caches.c (ffffffff81587444)
Location: include/linux/vmstat.h:69
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffff8000102b2710)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffff8000102b77f4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffff8000102c1320)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffff8000102cd8e4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d3b14)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffff8000102ece70)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffff8000102fa314)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffff8000102fd68c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffff800010317d74)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffff800010320a0c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffff8000103224ec)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffff800010352d34)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffff80001035a5b4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035c780)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In fs/dax.c (ffff80001040a318)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffff800010429164)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (c04df980)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c04e4434)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (c04ed3cc)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (c04f810c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fba70)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/compaction.c (c0510d8c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (c051bc5c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (c051c9fc)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (c05320dc)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (c05393f8)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (c053ab00)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In fs/drop_caches.c (c05f1d28)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (c000000000368ce0)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (c00000000036f5ec)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (c00000000037c3e4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (c00000000038b434)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c0000000003928d8)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (c0000000003b0a00)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (c0000000003c4470)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (c0000000003c8d40)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (c0000000003ea2d0)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (c0000000003f5d20)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (c0000000003f80a4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (c000000000439820)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (c000000000444060)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000445cf8)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In fs/dax.c (c0000000005164cc)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (c0000000005394d4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffe0001d8036)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffe0001dbae2)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffe0001e35de)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffe0001ec47a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffe0001ef83c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/compaction.c (ffffffe0002015be)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffe000209ac4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffe00020bec6)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffe00021dae8)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffe000221fa4)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffe000223350)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In fs/dax.c (ffffffe0002b3eec)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffe0002c719a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff8121db9e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81222080)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8122a8cc)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff81234c3e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81239a2a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff8124dfe9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff8125b69a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff8125eed7)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff812785d2)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff8127e999)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff8127ff87)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812aaafe)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812b22d9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b44e2)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81341e45)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff8135aebd)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff81210d68)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff81215230)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8121d9ec)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff81227cae)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122ca5a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff81240f89)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff8124dc7a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff81251307)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff8126a4c2)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff812707c9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff81271d3f)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff8129c45e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812a3669)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a5562)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff813327fd)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff8134bb5d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff8121b93e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8121fe20)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8122866c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff812329de)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812377ca)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff8124bd89)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff8125943a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff8125cc77)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81276372)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff8127c739)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff8127dddf)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812a890e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812b00e9)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b22f2)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133f915)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff8135898d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
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
In mm/filemap.c (ffffffff8122a995)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/oom_kill.c (ffffffff8122ef00)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff812379dc)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_cache_add_active_or_unevictable
```
```
In mm/vmscan.c (ffffffff81241e99)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:throttle_direct_reclaim
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81246d0b)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/compaction.c (ffffffff8125b699)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_do_work
```
```
In mm/memory.c (ffffffff81268e3a)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
```
```
In mm/mlock.c (ffffffff8126c657)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_isolated_page
  - mm/mlock.c:mlock_vma_page
  - mm/mlock.c:clear_page_mlock
  - mm/mlock.c:clear_page_mlock
```
```
In mm/page_alloc.c (ffffffff81285f4c)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:__alloc_pages_direct_compact
```
```
In mm/page_io.c (ffffffff8128c309)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff8128d98f)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:lookup_swap_cache
```
```
In mm/migrate.c (ffffffff812b8c2e)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
```
```
In mm/huge_memory.c (ffffffff812c0429)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c26f2)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8135240f)
Location: include/linux/vmstat.h:60
Inline: True
```
```
In fs/drop_caches.c (ffffffff8136c08d)
Location: include/linux/vmstat.h:60
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
</details>
</li>
</ul>

## Differences
