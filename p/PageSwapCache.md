# Function: <code>PageSwapCache</code>

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
In kernel/futex.c (ffffffff810ffad0)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff8119aa11)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/page-writeback.c:__set_page_dirty_nobuffers
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8119c59c)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811a0298)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811a917c)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811ac0f0)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff811bfa6b)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/page_io.c (ffffffff811d1f21)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
```
```
In mm/swap_state.c (ffffffff811d298a)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/swap_state.c:free_pages_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811d3375)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff811dc60f)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff811e4b80)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f1694)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff811f4cb1)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81200147)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_commit_charge
```
```
In mm/memory-failure.c (ffffffff812027d3)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8124288e)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff81276a1e)
Location: include/linux/page-flags.h:260
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
In kernel/futex.c (ffffffff8110772f)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff811add83)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811b1e3c)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811b9626)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811c0aea)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811c480d)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff811d9c1a)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/madvise.c (ffffffff811eedee)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff811f0295)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/page_io.c:swap_set_page_dirty
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff811f077c)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff811f36a5)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff811fa86f)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff81203fcc)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8121070d)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81217a84)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8121c026)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81224784)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff81226e7a)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8126abb2)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812a4712)
Location: include/linux/page-flags.h:317
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
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
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff811be3a7)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811c2474)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811c9c52)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811d10d1)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811d48fe)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff811e9749)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/madvise.c (ffffffff811ff71d)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81200971)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81201152)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81204170)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8120b29f)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812161d2)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81222862)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8122a034)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122e687)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81236d54)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff81239416)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8127dcd7)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812ba072)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff812cadde)
Location: include/linux/page-flags.h:327
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
In kernel/futex.c (ffffffff8111021a)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff811c7796)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811ca8f4)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811d2649)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811d9b0c)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811dd67e)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff811f4896)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff81204394)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a268)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8120b5ca)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8120bf91)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8120f819)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812167fd)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812216f8)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8122e2e8)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81235b83)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8123a0c1)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812427f7)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812456f6)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8128b8b7)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812c77b1)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff812d8291)
Location: include/linux/page-flags.h:327
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
In kernel/futex.c (ffffffff8111b973)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff811dc5d7)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff811e15a5)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811e7b40)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff811ef7fe)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff811f30fe)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8120c670)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8121d166)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812234cb)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81224aac)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812255c1)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8122b0b7)
Location: include/linux/page-flags.h:328
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
In mm/hugetlb.c (ffffffff812314ad)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff8123ca2a)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812493bc)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8125492e)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff81259798)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81262637)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff81265618)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff812ae467)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff812eb3b1)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff812fc991)
Location: include/linux/page-flags.h:328
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
In kernel/futex.c (ffffffff811284b8)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff811fe90b)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81202ce9)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81208f94)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81210ce5)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff812149f5)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8122d2b7)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8123f063)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8124633f)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812470df)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81247b62)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8124c31e)
Location: include/linux/page-flags.h:335
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
In mm/hugetlb.c (ffffffff812543ad)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812602e4)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8126ce3d)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81278711)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff8127d18f)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812867f7)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff8128908d)
Location: include/linux/page-flags.h:335
Inline: True
```
```
In fs/buffer.c (ffffffff812d6137)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813186e1)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8132a5b2)
Location: include/linux/page-flags.h:335
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
In kernel/futex.c (ffffffff81133d9a)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff8120ef23)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81215679)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8121bc74)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81222d0b)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
```
```
In mm/util.c (ffffffff812278d5)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8124084d)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff8125367a)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8125a761)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8125b537)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8125c132)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81260821)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8126878d)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff81274a21)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81281669)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8128cd95)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
```
```
In mm/khugepaged.c (ffffffff81291d08)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8129b767)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff8129dfdd)
Location: include/linux/page-flags.h:347
Inline: True
```
```
In fs/buffer.c (ffffffff812eb507)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8132f5f3)
Location: include/linux/page-flags.h:347
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8134190c)
Location: include/linux/page-flags.h:347
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
In kernel/futex.c (ffffffff8113ecd9)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff8121eab6)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81225085)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122b930)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81233107)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff81237675)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff81252aef)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff812658e5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127598d)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812766a1)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81277301)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8127a1a7)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128386f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff81292b65)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8129d8fb)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a7a83)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812abf89)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b6c0a)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812b9192)
Location: include/linux/page-flags.h:380
Inline: True
```
```
In fs/buffer.c (ffffffff8130cc07)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8135703f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81369d01)
Location: include/linux/page-flags.h:380
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
In kernel/futex.c (ffffffff8114a703)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff8122c556)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81232f05)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812397f9)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81241327)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff812458c5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8126104f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff812741fa)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128495d)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81286191)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81286de1)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81289c87)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8129340f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812a28e5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812ad219)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b9c91)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812bd799)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c8ada)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812cbf8d)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8131fbd7)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8136f60f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81381f21)
Location: include/linux/page-flags.h:380
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
In kernel/futex.c (ffffffff8115b257)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81259e66)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81260489)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81265f09)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:pageout
```
```
In mm/shmem.c (ffffffff8126db81)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812735f5)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff812914cd)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff812a547b)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812b6b56)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812b83a2)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812b9360)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812bcb61)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812c692d)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812d7065)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812e2d53)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812ee831)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page_tail
```
```
In mm/khugepaged.c (ffffffff812f0926)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff812fe0b6)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_charge
```
```
In mm/memory-failure.c (ffffffff81302141)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81359f10)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813b6e60)
Location: include/linux/page-flags.h:388
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff813cc551)
Location: include/linux/page-flags.h:388
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
In kernel/futex.c (ffffffff81157394)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81265618)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126a5b9)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812708a2)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812798c1)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8127ddb5)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8129be3d)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812b0910)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c2da7)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812c3a6f)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812c4cf0)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812c8691)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812d246d)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812df1cc)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812ee183)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812f9ea5)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812fc09d)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff8130a554)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_charge
  - mm/memcontrol.c:mem_cgroup_charge
```
```
In mm/memory-failure.c (ffffffff8130e92d)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81368040)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813c8500)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff813de199)
Location: include/linux/page-flags.h:396
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
In kernel/futex.c (ffffffff811587a8)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff8126a116)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8126f6ee)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812752e8)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8127ea19)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff81282472)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff812a10d6)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812b5f42)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c9c20)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff812ca839)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff812cb980)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff812cf041)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff812d8f1d)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff812e69a6)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812f3c73)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff81300c4c)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8130306e)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81314df2)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff8136eb00)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813cf53f)
Location: include/linux/page-flags.h:396
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff813e4f80)
Location: include/linux/page-flags.h:396
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
In kernel/futex.c (ffffffff8117d6b5)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff812a6da9)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
  - mm/page-writeback.c:__set_page_dirty
```
```
In mm/swap.c (ffffffff812ac83e)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b2e7f)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff812bc598)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff812c04e2)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff812e2055)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/rmap.c (ffffffff812f7b55)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8130ec40)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8130f839)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81310985)
Location: include/linux/page-flags.h:410
Inline: True
```
```
In mm/swapfile.c (ffffffff813145e1)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:page_trans_huge_map_swapcount
  - mm/swapfile.c:page_trans_huge_map_swapcount
```
```
In mm/hugetlb.c (ffffffff8131f91f)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff8132e8c6)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff8133e613)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff8134a8ec)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8134cdde)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81360e92)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8142091f)
Location: include/linux/page-flags.h:410
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81436b50)
Location: include/linux/page-flags.h:410
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
In kernel/futex/core.c (ffffffff811b2734)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/swap.c (ffffffff81306b83)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
```
```
In mm/memory.c (ffffffff81343ca4)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/madvise.c (ffffffff813768d9)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8137a0a4)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8137b6b5)
Location: include/linux/page-flags.h:566
Inline: True
```
```
In mm/swapfile.c (ffffffff8137fa45)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/hugetlb.c (ffffffff8138c39a)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff813a067d)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b4e7f)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/migrate.c:migrate_huge_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff813c170f)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c4147)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff813da3c3)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8149966e)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff814b12f2)
Location: include/linux/page-flags.h:566
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff811f35d4)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page_io.c (ffffffff813f7b94)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/hugetlb.c (ffffffff8140ae6c)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff8141fe61)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/huge_memory.c (ffffffff814437c3)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff81448065)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff81461a93)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8152d824)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81547cb2)
Location: include/linux/page-flags.h:545
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff81207d8a)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page_io.c (ffffffff8142ad54)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/hugetlb.c (ffffffff8143e516)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff81454a73)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/huge_memory.c (ffffffff814722c6)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff8147da45)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff814972cd)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81565c54)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8157f8c7)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/page_io.c (ffffffff814644f8)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/ksm.c (ffffffff8148fc5d)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/huge_memory.c (ffffffff814a2561)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/memory-failure.c (ffffffff814c8bd9)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159dc31)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff815b82e8)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffff8000102bbfcc)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffff8000102c2f90)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102ca6f8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffff8000102d3710)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffff8000102d8e88)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffff8000102f83f8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffff800010309e20)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031eb48)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffff8000103207d0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffff800010321794)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010324c28)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffff800010331438)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffff800010342324)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffff80001034f52c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffff80001035a50c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffff80001035ec94)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffff80001036ba1c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffff80001036f618)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffff8000103d824c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffff800010438d0c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffff800010450148)
Location: include/linux/page-flags.h:380
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
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (c04e6ec0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (c04ee0d0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (c04f455c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c04fb9d8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (c0500074)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (c051abf4)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (c0526658)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0537764)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c05391ac)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (c0539f80)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053c724)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/ksm.c (c0548068)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (c05514b4)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (c055d034)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/buffer.c (c05b131c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/page.c (c06133d4)
Location: include/linux/page-flags.h:380
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
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (c000000000373758)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (c00000000037d278)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (c000000000387290)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (c0000000003927b0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (c0000000003989a0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (c0000000003c176c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (c0000000003d9a80)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0000000003f3364)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (c0000000003f5a50)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (c0000000003f6ecc)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fad40)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (c00000000040a194)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (c00000000041fcd0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (c0000000004319b0)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (c000000000443fb8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (c0000000004480d4)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c00000000045b530)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (c000000000461184)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (c0000000004dbfa4)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (c00000000054c5fc)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (c00000000056812c)
Location: include/linux/page-flags.h:380
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
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffe0001de102)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffe0001e4268)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffe0001e979e)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffe0001ef7ca)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffe0001f330e)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffe00020894c)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffe000213dac)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe0002205ac)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffe000221e36)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffe000222a16)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffe000225328)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffe00022e538)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffe000236564)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffe00023e524)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/memcontrol.c (ffffffe000248fbc)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In fs/buffer.c (ffffffe000291096)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/page.c (ffffffe0002e32ea)
Location: include/linux/page-flags.h:380
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
In kernel/futex.c (ffffffff81142d23)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81224ba6)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8122b555)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81231e49)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81239977)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff8123df15)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8125969f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff8126c84a)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127cfad)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8127e7e1)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8127f431)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81282267)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8128b9ef)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff8129aec5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812a57f9)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b2271)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b5d79)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c10ba)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812c456d)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff813181b7)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff81367bef)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8137a501)
Location: include/linux/page-flags.h:380
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
In kernel/futex.c (ffffffff81136083)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81217d56)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff8121e645)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81224f09)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff8122c9a7)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff81230f15)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8124bb15)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff8125e8a3)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8126ee23)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff81270611)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff81271251)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81273d87)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff8127d81f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff8128ca85)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812972c9)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812a3601)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812a6f34)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b210e)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812b55ad)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81308da7)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff8135888f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8136afd1)
Location: include/linux/page-flags.h:380
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
In kernel/futex.c (ffffffff81140bd3)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81222946)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff812292f5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122fbe9)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81237717)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff8123bcb5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff8125743f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff8126a5ea)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127ad4d)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8127c581)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8127d1d1)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff81280077)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812897ff)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff81298cd5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812a3609)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812b0081)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812b3b89)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812beeca)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812c237d)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81315c87)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff813656bf)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81377fd1)
Location: include/linux/page-flags.h:380
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
In kernel/futex.c (ffffffff8114de2e)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81231b26)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/swap.c (ffffffff81238695)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123f02f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff81246c51)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/util.c (ffffffff8124b3c5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/util.c:page_mapping_file
  - mm/util.c:page_mapping
```
```
In mm/memory.c (ffffffff81266e23)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff81279fc8)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128a926)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8128c151)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_slot_free_notify
```
```
In mm/swap_state.c (ffffffff8128cd91)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swap_state.c:free_pages_and_swap_cache
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffff8128fd67)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
  - mm/swapfile.c:reuse_swap_page
```
```
In mm/hugetlb.c (ffffffff812995df)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/hugetlb.c:__basepage_index
  - mm/hugetlb.c:__basepage_index
```
```
In mm/ksm.c (ffffffff812a8ab5)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/ksm.c:reuse_ksm_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff812b3e19)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
```
In mm/huge_memory.c (ffffffff812c03c1)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
```
```
In mm/khugepaged.c (ffffffff812c3fcb)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812cf94a)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_commit_charge
  - mm/memcontrol.c:mem_cgroup_try_charge
```
```
In mm/memory-failure.c (ffffffff812d2e08)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/buffer.c (ffffffff81327887)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty
```
```
In fs/proc/task_mmu.c (ffffffff81378d9f)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8138ba81)
Location: include/linux/page-flags.h:380
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
