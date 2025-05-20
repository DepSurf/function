# Function: <code>PageSwapBacked</code>

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
In mm/filemap.c (ffffffff8118e4fc)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff8119c5c5)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:__page_cache_release
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:lru_add_page_tail
```
```
In mm/vmscan.c (ffffffff811a02b3)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:check_move_unevictable_pages
```
```
In mm/compaction.c (ffffffff811b55cb)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/compaction.c:acct_isolated
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/mlock.c (ffffffff811c2cf0)
Location: include/linux/page-flags.h:223
Inline: True
```
```
In mm/mempolicy.c (ffffffff811e01f3)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff8181a680)
Location: include/linux/page-flags.h:223
Inline: True
```
```
In mm/migrate.c (ffffffff811f102d)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f7104)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff811fecfe)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/memcontrol.c:lock_page_lru
  - mm/memcontrol.c:unlock_page_lru
```
```
In mm/memory-failure.c (ffffffff812031a6)
Location: include/linux/page-flags.h:223
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
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
In kernel/events/uprobes.c (ffffffff81199fbd)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811a1f39)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/swap.c (ffffffff811b1f2c)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811bca93)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/compaction.c (ffffffff811d0262)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811da65e)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811de993)
Location: include/linux/page-flags.h:277
Inline: True
```
```
In mm/rmap.c (ffffffff811e852a)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/mempolicy.c (ffffffff811fef11)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/memory_hotplug.c (ffffffff81894164)
Location: include/linux/page-flags.h:277
Inline: True
```
```
In mm/migrate.c (ffffffff81212fc0)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81217d36)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memcontrol.c (ffffffff81224b28)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff81227c9d)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/proc/task_mmu.c (ffffffff812a519d)
Location: include/linux/page-flags.h:277
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
In kernel/futex.c (ffffffff8110eee9)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811a96f1)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b1d88)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811be3a7)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811c258c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811cd166)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff811d10d1)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811d48fe)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff811e02d8)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811ea17a)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811ee7b5)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In mm/rmap.c (ffffffff811f99cf)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ff71d)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81200971)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81201152)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81204170)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8120b29f)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff81210751)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff812161d2)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818c8863)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In mm/migrate.c (ffffffff81225330)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8122a034)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122e687)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81237116)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff8123a239)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8127dcd7)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812ba072)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff812cadde)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81110229)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811b0bda)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811b8bfa)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page-writeback.c (ffffffff811c77ac)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811caa0c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811d5e67)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff811dcfb4)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811dd68d)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff811e9f5f)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff811f5020)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffff811f973b)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In mm/rmap.c (ffffffff81204374)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a277)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8120b5da)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8120bfa0)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8120f828)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8121680c)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8121c1a5)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8122170e)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff818ffe70)
Location: include/linux/page-flags.h:287
Inline: True
```
```
In mm/migrate.c (ffffffff81230a20)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81235b92)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8123a0d0)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8123f631)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff81245e32)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8128b8c6)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812c77c0)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812d82a0)
Location: include/linux/page-flags.h:287
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8111b982)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811c475f)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811ca164)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811dc5ed)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811df77c)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811eb387)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff811eef24)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811f310d)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff812002ba)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8120d0ff)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81211b6b)
Location: include/linux/page-flags.h:288
Inline: True
```
```
In mm/rmap.c (ffffffff8121d146)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812234e6)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81224abc)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812255d0)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8122b0c6)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812314bc)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff812369d2)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8123ca39)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81989fbc)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff8124e7a3)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8125493d)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff812597a8)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8125f38b)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff81265e6a)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff812ae476)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812eb3c0)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812fc9a0)
Location: include/linux/page-flags.h:288
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff811284c7)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811e4d12)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (ffffffff811eb2e4)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff811fe916)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81201f7c)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8120cb5e)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff8120fa1a)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff81214a04)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff812216e8)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff8122dcea)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812328b4)
Location: include/linux/page-flags.h:295
Inline: True
```
```
In mm/mprotect.c (ffffffff8123920f)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8123f04a)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81246362)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812470ef)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81247b71)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124c32d)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812543bc)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff812599c6)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff812602f9)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff819e6719)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff812725c9)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81278720)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8127d19e)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8128385d)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff8128a2be)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/buffer.c (ffffffff812d6146)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813186f0)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8132a5c0)
Location: include/linux/page-flags.h:295
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81133da9)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811f5382)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff811ff4d1)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8120ef2e)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff812148fc)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8121fa1d)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff812227ee)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff812278e4)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff81234745)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff812411ac)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812460f7)
Location: include/linux/page-flags.h:307
Inline: True
```
```
In mm/mprotect.c (ffffffff8124d796)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff81253660)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8125a784)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8125b547)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8125c141)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81260830)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8126879c)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8126d5d8)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff81274a36)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff81a21c4f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/migrate.c (ffffffff81286bda)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8128cd9f)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81291d17)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812973d3)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff8129f268)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
```
```
In fs/buffer.c (ffffffff812eb516)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8132f602)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8134191a)
Location: include/linux/page-flags.h:307
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8113ece8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8120d04c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81216760)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8121eac1)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff812245c4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122f188)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff81231df4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff81237684)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff81244561)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8124d8ad)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff81253488)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff81258312)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffff8125f79f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812658cc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812759b0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812766b2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81277310)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127a1b2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128387e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff81288b1b)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff81292b86)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff8129c591)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a1177)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a7a8d)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812abf98)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812b2ebc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812b91a6)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In fs/buffer.c (ffffffff8130cc17)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8135704e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81369d0f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8114a712)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121a3b9)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff81224070)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8122c561)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81232354)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123d318)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff8123feb4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff812458d4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff81252a21)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff8125bde4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff812619e8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff812667e2)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffff8126dfaf)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812741e1)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff81284980)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812861a2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81286df0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81289c92)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8129341e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8129868b)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff812a2906)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812abff0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b2587)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b9c9c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bdfe6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812c498c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812cbf9c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8131fbe7)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8136f61e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81381f2f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8115b266)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81246d62)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8124fa1c)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81259e71)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8125f64a)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812658de)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff8126e8b3)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81273604)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff81282b0e)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/memory.c (ffffffff81291c63)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
```
```
In mm/mlock.c (ffffffff812968ad)
Location: include/linux/page-flags.h:348
Inline: True
```
```
In mm/mprotect.c (ffffffff8129e854)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a5462)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff812b6b79)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812b83a2)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812b936f)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812bcb70)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812c693c)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff812cc1fb)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff812d7086)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812e1453)
Location: include/linux/page-flags.h:348
Inline: True
```
```
In mm/migrate.c (ffffffff812e7b27)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812ee83c)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page_tail
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f3933)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812fe0c5)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81302150)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81359f20)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813b6e6f)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813cc55f)
Location: include/linux/page-flags.h:348
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff811573a3)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812513cf)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125a942)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81265623)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81269bc8)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812702ba)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:page_check_dirty_writeback
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff812792b0)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8127ddc4)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff8128d0ce)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81290de5)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/memory.c (ffffffff8129c52f)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a1c66)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812a9c0a)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b08f7)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff812c2db6)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812c3a6f)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812c4cff)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812c86a0)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812d247c)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff812d7a8a)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff812df1e2)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812ec30c)
Location: include/linux/page-flags.h:357
Inline: True
```
```
In mm/migrate.c (ffffffff812f2ef7)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812f9eb0)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812ff130)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130a563)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130d91d)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memory-failure.c:isolate_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81368050)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813c850f)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813de1a8)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff811587b7)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812554d7)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8125f194)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff8126a121)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126d8df)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8127613b)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff8127e29c)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81282481)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff81291b95)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff81296445)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffffffff812970c1)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff812a19f9)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812a7540)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812af095)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b5f25)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memory_hotplug.c (ffffffff812c6a2b)
Location: include/linux/page-flags.h:357
Inline: True
```
```
In mm/madvise.c (ffffffff812c9c2f)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812ca839)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812cb98f)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812cf050)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812d8f2d)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/mempolicy.c (ffffffff812defa9)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff812e69bc)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f9297)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff81300c5b)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81305da5)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff8130c8fd)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81313e85)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8136eb10)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813cf54e)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813e4f8e)
Location: include/linux/page-flags.h:357
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8117d6c4)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81290f16)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8129b8f6)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff812a6db4)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__set_page_dirty
```
```
In mm/swap.c (ffffffff812a9f4e)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_deactivate_file_fn
  - mm/swap.c:lru_note_cost_page
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b2794)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff812bc5a7)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812c04f1)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff812d18ef)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/workingset.c (ffffffff812d6bd5)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/workingset.c:workingset_refault
```
```
In mm/gup.c (ffffffff812d7a74)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
```
```
In mm/memory.c (ffffffff812e29c9)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff812e881d)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/mprotect.c (ffffffff812f08a2)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812f888c)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/memory_hotplug.c (ffffffff8130b4d7)
Location: include/linux/page-flags.h:371
Inline: True
```
```
In mm/madvise.c (ffffffff8130ec4f)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8130f839)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81310994)
Location: include/linux/page-flags.h:371
Inline: True
```
```
In mm/swapfile.c (ffffffff813145f0)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff8131f92f)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/mempolicy.c (ffffffff81326c39)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8132e8dc)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81343581)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:add_page_for_migration
  - mm/migrate.c:unmap_and_move
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff8134a8fb)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134fc0c)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff81357afd)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8135f168)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/userfaultfd.c (ffffffff81366ef1)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8142092e)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81436b5e)
Location: include/linux/page-flags.h:371
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/events/uprobes.c (ffffffff812e630d)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff812f0bd2)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/swap.c (ffffffff81306b63)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
```
```
In mm/memory.c (ffffffff813432ef)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135ed13)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/huge_memory.c (ffffffff813bfb73)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c7e60)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff813e430c)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff81499ee0)
Location: include/linux/page-flags.h:521
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
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
In kernel/events/uprobes.c (ffffffff8134fdc1)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813bb2ab)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff813d9b9e)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/huge_memory.c (ffffffff8143d73f)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8144c036)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff8146bdb8)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8152e13e)
Location: include/linux/page-flags.h:500
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
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
In kernel/events/uprobes.c (ffffffff81380f7a)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813efd7e)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff8140e294)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff81472de8)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81481849)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814a0b87)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff815663d9)
Location: include/linux/page-flags.h:493
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
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
In kernel/events/uprobes.c (ffffffff813aa353)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8141b319)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_set_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/rmap.c (ffffffff8143aaa7)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/huge_memory.c (ffffffff814a1554)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814b0899)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814d0389)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159e408)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
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
In kernel/futex.c (ffff8000101b7b98)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffff8000102a5794)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffff8000102af824)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffff8000102bbfcc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffff8000102c11d8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102ce768)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffff8000102d31ec)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffff8000102d8e88)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffff8000102eb2a8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffff8000102f3194)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffff8000102f8d24)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffff8000102fd7a0)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffff8000103051f8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffff800010309e00)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffff80001031eb48)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffff8000103207d0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffff800010321794)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010324c28)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffff800010331438)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffff8000103372c0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffff800010342324)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffff800010352dd0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffff80001035a50c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035f5a4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffff8000103675e8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffff8000103703e8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffff8000103d824c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffff800010438d0c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffff800010450148)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (c040194c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c04d4c10)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c04de1e8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c04e6ec0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (c04ed474)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (c04f8528)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (c04fb178)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (c0500074)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (c050eb78)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0515514)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (c051b384)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c051cba4)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (c0523484)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c052663c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0537764)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c05391ac)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (c0539f80)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053c724)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c0548068)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (c0552ab0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (c0558d08)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In fs/buffer.c (c05b131c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (c0600aa0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (c06133d4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (c00000000021d04c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c0000000003585b0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (c0000000003673ec)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (c000000000373758)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (c00000000037c264)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (c00000000038c558)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (c000000000391c50)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (c0000000003989a0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (c0000000003acaf0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (c0000000003b9c08)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (c0000000003c23a4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (c0000000003c8b50)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (c0000000003d2518)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d9a64)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (c0000000003f3364)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c0000000003f5a50)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (c0000000003f6ecc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fad40)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (c00000000040a194)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (c000000000411cb8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (c00000000041fcd0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (c00000000042e260)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (c000000000439938)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (c000000000443fb8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (c00000000044a4a4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (c000000000454c10)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (c000000000461184)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (c0000000004dbfa4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (c00000000054c5fc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (c00000000056812c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffe00013c87c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/filemap.c (ffffffe0001d7106)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffe0001de102)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffe0001e3572)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffe0001ec8cc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffe0001ee3b2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffe0001f330e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffe0001ff912)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffe0002054f8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffe000209006)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mlock.c (ffffffe00020c05c)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffe00021133c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000213d9e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe0002205ac)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffe000221e36)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffe000222a16)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffe000225328)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffe00022e538)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffe000236564)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffe00023fe00)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/memcontrol.c (ffffffe000245764)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In fs/buffer.c (ffffffe000291096)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffe0002d3236)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffe0002e32ea)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81142d32)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81212a09)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121c6c0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81224bb1)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8122a9a4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81235968)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff81238504)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff8123df24)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff8124b071)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81254434)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff8125a038)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125ee32)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffff812665ff)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126c831)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8127cfd0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8127e7f2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8127f440)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81282272)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128b9fe)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff81290c6b)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8129aee6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a45d0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812aab67)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b227c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b65c6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812bcf6c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812c457c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff813181c7)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff81367bfe)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8137a50f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81136092)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81205783)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8120f8a4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81217d61)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8121dac4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812289d2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff8122b506)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff81230f24)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff8123e011)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81247084)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff8124c4d0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mlock.c (ffffffff81251262)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffff81258ce1)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125e88a)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8126ee3a)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81270622)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81271260)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81273d92)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8127d82e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff812828eb)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff8128caa6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812960a0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff8129c4c4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812a360c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a779c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812ae0ac)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812b55bc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81308db7)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8135889e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8136afdf)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81140be2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812107a9)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8121a460)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81222951)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81228744)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81233708)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff812362a4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff8123bcc4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff81248e11)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff812521d4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff81257dd8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8125cbd2)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffff8126439f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126a5d1)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8127ad70)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8127c592)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8127d1e0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81280082)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128980e)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8128ea7b)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff81298cf6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812a23e0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812a8977)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812b008c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b43d6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812bad7c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812c238c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81315c97)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813656ce)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81377fdf)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8114de3d)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121f6ba)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/filemap.c (ffffffff8122952c)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page-writeback.c (ffffffff81231b31)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81237ab4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:__pagevec_lru_add_fn
  - mm/swap.c:lru_add_page_tail
  - mm/swap.c:release_pages
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:mark_page_accessed
  - mm/swap.c:__page_cache_release
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81242c3f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/vmscan.c:check_move_unevictable_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_page
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:perf_trace_mm_vmscan_writepage
  - mm/vmscan.c:trace_event_raw_event_mm_vmscan_writepage
```
```
In mm/shmem.c (ffffffff8124657f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff8124b3d4)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/compaction.c (ffffffff8125865a)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/gup.c (ffffffff81261b84)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffff812677c8)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/mlock.c (ffffffff8126c5b2)
Location: include/linux/page-flags.h:340
Inline: True
```
```
In mm/mprotect.c (ffffffff81273d5f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81279faf)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_add_file_rmap
```
```
In mm/madvise.c (ffffffff8128a949)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8128c162)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8128cda0)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128fd72)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812995ee)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/mempolicy.c (ffffffff8129e97b)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_page_add
```
```
In mm/ksm.c (ffffffff812a8ad6)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/memory_hotplug.c (ffffffff812b2740)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/migrate.c (ffffffff812b8c97)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:putback_movable_pages
```
```
In mm/huge_memory.c (ffffffff812c03cc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c48a2)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_page
```
```
In mm/memcontrol.c (ffffffff812cb4cc)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812d2e17)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81327897)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff81378dae)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8138ba8f)
Location: include/linux/page-flags.h:340
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
