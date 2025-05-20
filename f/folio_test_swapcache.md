# Function: <code>folio_test_swapcache</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2748)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff812fefe8)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff81306b98)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/truncate.c (ffffffff81308851)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffff8130e181)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
```
```
In mm/shmem.c (ffffffff813185f4)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff8131d541)
Location: include/linux/page-flags.h:560
Inline: True
```
```
In mm/memory.c (ffffffff81343cac)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff8135d8e1)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813768ed)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8137a0b9)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8137b6ce)
Location: include/linux/page-flags.h:560
Inline: True
```
```
In mm/swapfile.c (ffffffff8137fa67)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_free_swap
```
```
In mm/hugetlb.c (ffffffff8138c3ae)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff813a0692)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff813b0959)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff813c1723)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff813c4158)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memory-failure.c (ffffffff813da3d7)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - mm/memory-failure.c:__soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81499683)
Location: include/linux/page-flags.h:560
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff814b1303)
Location: include/linux/page-flags.h:560
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
In kernel/futex/core.c (ffffffff811f35e8)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff81369777)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff81370fba)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff81379c6b)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff8138c4eb)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff813911f1)
Location: include/linux/page-flags.h:539
Inline: True
```
```
In mm/memory.c (ffffffff813bbd57)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff813c259e)
Location: include/linux/page-flags.h:539
Inline: True
```
```
In mm/rmap.c (ffffffff813d8741)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f4262)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff813f7ba9)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff813f9053)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff813fe5c5)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/hugetlb.c (ffffffff8140ae81)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff8141fe75)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff814314de)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814437d4)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_huge_page
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81448076)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff81455e74)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81461aa7)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8152d83a)
Location: include/linux/page-flags.h:539
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff81547cc3)
Location: include/linux/page-flags.h:539
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
In kernel/futex/core.c (ffffffff81207d9e)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff8139b914)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff813a316a)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813b7941)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813beafe)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_add_to_page_cache
```
```
In mm/util.c (ffffffff813c3bb1)
Location: include/linux/page-flags.h:533
Inline: True
```
```
In mm/memory.c (ffffffff813f076c)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff813f6eec)
Location: include/linux/page-flags.h:533
Inline: True
```
```
In mm/rmap.c (ffffffff8140cf2f)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814278d4)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8142ad69)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/page_io.c:swap_readpage_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff8142be23)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff81431565)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/hugetlb.c (ffffffff8143e52b)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_basepage_index
```
```
In mm/ksm.c (ffffffff81454a87)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff81466e5e)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff81478dff)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8147da56)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff8148cf48)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814972e1)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff81565c6a)
Location: include/linux/page-flags.h:533
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff8157f8d8)
Location: include/linux/page-flags.h:533
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
In kernel/futex/core.c (ffffffff8121ef1b)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/page-writeback.c (ffffffff813c4383)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_start_writeback
  - mm/page-writeback.c:__folio_end_writeback
  - mm/page-writeback.c:__folio_mark_dirty
```
```
In mm/swap.c (ffffffff813ccdda)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
  - mm/swap.c:lru_gen_add_folio
```
```
In mm/vmscan.c (ffffffff813e0926)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:__remove_mapping
  - mm/vmscan.c:lru_gen_add_folio
```
```
In mm/shmem.c (ffffffff813e9b03)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
```
```
In mm/util.c (ffffffff813ee761)
Location: include/linux/page-flags.h:535
Inline: True
```
```
In mm/memory.c (ffffffff814200e7)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
```
In mm/mlock.c (ffffffff814230ca)
Location: include/linux/page-flags.h:535
Inline: True
```
```
In mm/rmap.c (ffffffff81439644)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814610af)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/page_io.c (ffffffff8146450d)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/page_io.c:swap_read_folio_fs
  - mm/page_io.c:swap_writepage_fs
  - mm/page_io.c:sio_write_complete
```
```
In mm/swap_state.c (ffffffff81465583)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/swap_state.c:free_swap_cache
```
```
In mm/swapfile.c (ffffffff8146a955)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/swapfile.c:folio_free_swap
```
```
In mm/ksm.c (ffffffff8148fc71)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:get_ksm_page
```
```
In mm/migrate.c (ffffffff814960c1)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/migrate.c:folio_migrate_flags
  - mm/migrate.c:migrate_huge_page_move_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
```
In mm/huge_memory.c (ffffffff814a83df)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_folio
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff814aa785)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/khugepaged.c:is_refcount_suitable
```
```
In mm/memcontrol.c (ffffffff814bc882)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814c659d)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_in_use_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/task_mmu.c (ffffffff8159dc47)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
```
```
In fs/proc/page.c (ffffffff815b82f9)
Location: include/linux/page-flags.h:535
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
