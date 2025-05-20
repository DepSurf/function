# Function: <code>swp_type</code>

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
In mm/util.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/gup.c (ffffffff811ba4d9)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811bd965)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c2913)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/madvise.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/swapfile.c (ffffffff811d2f70)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:swap_info_get
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:free_swap_and_cache
```
```
In mm/frontswap.c (ffffffff811d763d)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/hugetlb.c (ffffffff811db0ed)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff811f0cc7)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffff811fa98e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8127811d)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/util.c (ffffffff811c4831)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff811d4bb4)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d9ab8)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de4cf)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff811e4c5a)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e870b)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811eec12)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff811f0846)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff811f0da5)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_info_get
  - mm/swapfile.c:scan_swap_map
```
```
In mm/frontswap.c (ffffffff811f5b86)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fc62f)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8121180e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812162cc)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8121e83e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff81225295)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In fs/proc/task_mmu.c (ffffffff812a5005)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/util.c (ffffffff811d491f)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff811e4be4)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e95ee)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee2e6)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff811f4c81)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6bd7)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f99bc)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ff543)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81201236)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81201715)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_info_get
  - mm/swapfile.c:scan_swap_map
```
```
In mm/frontswap.c (ffffffff812066b6)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120d11b)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812239ce)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8122887d)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81230e6e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff81237885)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In fs/proc/task_mmu.c (ffffffff812ba96a)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/util.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/gup.c (ffffffff811ef2cb)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f475e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f92ac)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ffbcf)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81201b40)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8120458e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a1fa)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/swapfile.c (ffffffff8120c6c5)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:__swap_info_get
```
```
In mm/frontswap.c (ffffffff81211e46)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/hugetlb.c (ffffffff81218f79)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8122f33f)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231f00)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff8123c744)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff81243555)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In fs/proc/task_mmu.c (ffffffff812c86b6)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/util.c (0)
Location: include/linux/swapops.h:40
Inline: True
```
```
In mm/gup.c (ffffffff812067e9)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120e7bc)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff812116a4)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218272)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8121abb4)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121d3c6)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81223443)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812260c5)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swap_readahead_detect
```
```
In mm/swapfile.c (ffffffff812262f5)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:__swap_info_get
```
```
In mm/frontswap.c (ffffffff8122c816)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:40
Inline: True
```
```
In mm/hugetlb.c (ffffffff81233f2a)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81237596)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b779)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81255c91)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8125c3ce)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812633a5)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:40
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec4e9)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/util.c (ffffffff81214173)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff81226701)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122ffcd)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8123243c)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8123939a)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123c703)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123f29b)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812462bf)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248478)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:__add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81248905)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:__swap_info_get
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/frontswap.c (ffffffff8124f4cb)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81250345)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81256f18)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8125aa91)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e440)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81279b3a)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8127fc2e)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff81287685)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812936ae)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319b26)
Location: include/linux/swapops.h:40
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/util.c (ffffffff81227043)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff8123aa41)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81241cbf)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245c0f)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8124db04)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81250e67)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812539a1)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8125a6df)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ca48)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8125cee5)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:__swap_info_get
```
```
In mm/frontswap.c (ffffffff8126341b)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81264815)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8126b58e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8126e9cc)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812832ce)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128e117)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8129459e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff8129c5d5)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812a7c54)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81330bff)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff81235ef7)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff81236e0c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff8124bcf4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81254626)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257d6b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8125f93a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81263144)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81265bd5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812757bf)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277c3d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81278075)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffffffff8127e356)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8127fd85)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128684d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81289e3a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f671)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8a99)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b08a9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812b7785)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812c47d6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81358a20)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff81244137)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff81244fcc)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff8125a1e4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262b86)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126627b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8126e14a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812718f4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812744f4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128478f)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128772d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81287b65)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffffffff8128ddb6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8128f215)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129643c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812999aa)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aea2d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ba019)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c2309)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812c9665)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812d61f9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81370c70)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8126e024)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff81272c7c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff812886ec)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81294a9b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff812965d4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8129e78e)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a1e65)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff812a5799)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812b6938)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b98aa)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_ra_info
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812b9f25)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff812c0af6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812c1ec5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812c99df)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812cebe6)
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/migrate.c (ffffffff812e4164)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812eebf7)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812f925a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812fecd5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff8130b41b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813b8ac9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/shmem.c (ffffffff8127c224)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff8127d32c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff812923d2)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129f31b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a1547)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9b4b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad92a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff812b0b5c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c2b88)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c5313)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812c5995)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff812cc516)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812cdaa5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812d53e0)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812da526)
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/migrate.c (ffffffff812f0199)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fa257)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130184b)
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8130b015)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff813172db)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813ca4fd)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/shmem.c (ffffffff812813e4)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff812824c0)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff81297d2e)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a42d9)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a6d3f)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aefd6)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2dc2)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b624c)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c9a04)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbfc1)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812cc645)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff812d2f46)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812d4d78)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812dc3b2)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812e1d82)
Location: include/linux/swapops.h:51
Inline: True
```
```
In mm/migrate.c (ffffffff812f5876)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81301022)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8130803b)
Location: include/linux/swapops.h:51
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff81311675)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff8131d5f6)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d0d1d)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/shmem.c (ffffffff812bc9b9)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff812c0530)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff812d876e)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e5736)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff812e821f)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f07c6)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f4982)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f8ba0)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8130ea24)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311191)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81311975)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff8131894a)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff8131a351)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81323551)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81328e60)
Location: include/linux/swapops.h:51
Inline: True
```
```
In mm/migrate.c (ffffffff8133fe3f)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134ac92)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813521cb)
Location: include/linux/swapops.h:51
Inline: True
```
```
In mm/swap_cgroup.c (ffffffff8135c9d5)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff8135ebd2)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a996)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff814224f6)
Location: include/linux/swapops.h:51
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
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
In mm/filemap.c (ffffffff812f59d8)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/shmem.c (ffffffff813185ad)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff8131d557)
Location: include/linux/swapops.h:53
Inline: True
```
```
In mm/gup.c (ffffffff813386ef)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81347a8a)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff81349591)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353e79)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813588ab)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135f17c)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81376bdf)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c1ce)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:find_get_incore_page
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8137caf5)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff81384049)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff813857f9)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81391015)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81397fee)
Location: include/linux/swapops.h:53
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d73)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b73d7)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1e21)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813ce873)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff813d6685)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff813d9073)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff813e44a9)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8b18)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8145da80)
Location: include/linux/swapops.h:53
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814995ca)
Location: include/linux/swapops.h:53
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/filemap.c (ffffffff8135f98b)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/shmem.c (ffffffff8138c4a8)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff81391207)
Location: include/linux/swapops.h:98
Inline: True
```
```
In mm/memory.c (ffffffff813bfe40)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813c197b)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce323)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2fac)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813da034)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f43a9)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:force_shm_swapin_readahead
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f996e)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff813fa315)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff81401b4f)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81403576)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff81412827)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81417d68)
Location: include/linux/swapops.h:98
Inline: True
```
```
In mm/ksm.c (ffffffff81421ad2)
Location: include/linux/swapops.h:98
Inline: True
```
```
In mm/migrate.c (ffffffff81433f23)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438f3b)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81444044)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81453454)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff8145c135)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff8145f068)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf7a)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470a9d)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff814ed4ad)
Location: include/linux/swapops.h:98
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e872)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/filemap.c (ffffffff8139095c)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/shmem.c (ffffffff813bea9e)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff813c3bc7)
Location: include/linux/swapops.h:98
Inline: True
```
```
In mm/memory.c (ffffffff813f4afb)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mincore.c (ffffffff813f6814)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402c00)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81407c0c)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pgtable-generic.c (ffffffff814098c3)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/rmap.c (ffffffff8140e763)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427a96)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c805)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8142d245)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_page_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffff81434a42)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81437b2c)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/zswap.c:shrink_worker
```
```
In mm/hugetlb.c (ffffffff81445e35)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8144b4a3)
Location: include/linux/swapops.h:98
Inline: True
```
```
In mm/ksm.c (ffffffff8145687a)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81469877)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f77b)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147958d)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8147f046)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff8148918d)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff81491dd5)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff81495018)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0cd5)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a5011)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815241b4)
Location: include/linux/swapops.h:98
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566b80)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/filemap.c (ffffffff813ba5dc)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/shmem.c (ffffffff813e9ab0)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_replace_folio
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff813ee777)
Location: include/linux/swapops.h:98
Inline: True
```
```
In mm/memory.c (ffffffff8142114c)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mincore.c (ffffffff814224c4)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f213)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814342d0)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/pgtable-generic.c (ffffffff81436124)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/rmap.c (ffffffff8143af6a)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814612a9)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:shmem_swapin_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f50)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:filemap_get_incore_folio
  - mm/swap_state.c:swap_cache_get_folio
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:get_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff814669e5)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_mapping
  - mm/swapfile.c:__swap_duplicate
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:__swap_count
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:swap_folio_sector
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff81471333)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/zswap.c:zswap_load
  - mm/zswap.c:zswap_store
  - mm/zswap.c:shrink_memcg_cb
```
```
In mm/hugetlb.c (ffffffff8147f86d)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8148517e)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/ksm.c (ffffffff81491370)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814987a7)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d620)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8b1b)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814afd1e)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b9046)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff814c17e5)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/memory-failure.c (ffffffff814c4918)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d2eef)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d60d0)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81558701)
Location: include/linux/swapops.h:98
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d363)
Location: include/linux/swapops.h:98
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/shmem.c (ffff8000102d637c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffff8000102d8018)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffff8000102f1d10)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f834c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffff8000102fd05c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffff800010305424)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffff800010307074)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffff80001030a0b4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031eadc)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff800010322244)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffff800010322910)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffff80001032aa00)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffff80001032c4f8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff800010335ddc)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffff800010350d5c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010354c8c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffff800010363dd4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffff80001036cd28)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffff80001037b778)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffff80001043970c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (c04fe61c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (c04ff480)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (c0514228)
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/memory.c (c051ab2c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c051c650)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (c0523420)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0524de4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0526780)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0537720)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053a900)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c053ae74)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (c054099c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c0542808)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/migrate.c (c0552414)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c0556108)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (c055da78)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup
```
```
In mm/hmm.c (c05664d0)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c0600a0c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
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
In mm/shmem.c (c0000000003965d8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (c000000000397b20)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (c0000000003b7df0)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c3c64)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c870c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (c0000000003d26a4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0000000003d57f8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d9800)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0000000003f312c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7c84)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (c0000000003f8340)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (c0000000004012c8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (c000000000403f18)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (c00000000040fe70)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (c000000000413120)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434d20)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000044443c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (c000000000450ea8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (c00000000045cc30)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (c0000000004704f0)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c00000000054ce30)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffe0001f1c08)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffe0001f28ce)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffe0002046e4)
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/memory.c (ffffffe0002088d0)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bba4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffe000211264)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffe00021260a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffe000213f92)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe000220576)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe00022325a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffe0002236e6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_page
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/frontswap.c (ffffffe0002295d8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffe00022b0b4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffe000231efe)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffe00023f72e)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffe000241cac)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffe000249b84)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffe000251f90)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffe0002d28f2)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8123c787)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff8123d61c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff81252834)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b1d6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e8cb)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8126679a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81269f44)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126cb44)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127cddf)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fcf7)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81280145)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffffffff81286396)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff812877f5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128ea1c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81291f8a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a700d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b25f9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812ba8e9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812c1c45)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812ce7d9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81369250)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8122f787)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff8123061c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff8124589b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124d88a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c7b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff81258e4c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8125bf96)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125eb94)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8126ec49)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271b37)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff81271fb5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffffffff812781f6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81279655)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff812807cf)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81283d93)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298a4a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3984)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812abaa7)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812b2c95)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812bf4af)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81359518)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff8123a527)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff8123b3bc)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff812505d4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81258f76)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125c66b)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff8126453a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267ce4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126a8e4)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127ab7f)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127db1d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8127df55)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffffffff812841a6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81285605)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8128c82c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8128fd9a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a4e1d)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b0409)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b86f9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812bfa55)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812cc5e9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81366d20)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In mm/shmem.c (ffffffff81249c1c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse_inode
```
```
In mm/util.c (ffffffff8124aacc)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff8125ff54)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81268976)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126c052)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_page
```
```
In mm/mprotect.c (ffffffff81273ef8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8127767c)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8127a25e)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128a760)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d6cd)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:lookup_swap_cache
  - mm/swap_state.c:delete_from_swap_cache
  - mm/swap_state.c:__delete_from_swap_cache
  - mm/swap_state.c:add_to_swap_cache
```
```
In mm/swapfile.c (ffffffff8128db05)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:__page_file_mapping
  - mm/swapfile.c:map_swap_entry
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:swp_entry_cmp
  - mm/swapfile.c:get_swap_device
  - mm/swapfile.c:_swap_info_get
```
```
In mm/frontswap.c (ffffffff81293e86)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/frontswap.c:__frontswap_load
  - mm/frontswap.c:__frontswap_store
```
```
In mm/zswap.c (ffffffff81294bf5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffffffff8129c60a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8129f233)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5979)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812c0749)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c8d39)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/swap_cgroup.c (ffffffff812d04b5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_cgroup.c:lookup_swap_cgroup_id
  - mm/swap_cgroup.c:swap_cgroup_record
  - mm/swap_cgroup.c:swap_cgroup_cmpxchg
```
```
In mm/hmm.c (ffffffff812dd349)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8137a370)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
</details>
</li>
</ul>

## Differences
