# Function: <code>swp_entry</code>

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
In kernel/power/swap.c (0)
Location: include/linux/swapops.h:26
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/swapops.h:26
Inline: True
```
```
In mm/memory.c (ffffffff811bd94b)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c28ff)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c897f)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811cb373)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811d163b)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (0)
Location: include/linux/swapops.h:26
Inline: True
```
```
In mm/swapfile.c (ffffffff811d4aa4)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:try_to_unuse
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:26
Inline: True
```
```
In mm/hugetlb.c (ffffffff811de246)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff811f0cad)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/memcontrol.c (ffffffff811fa96c)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81278103)
Location: include/linux/swapops.h:26
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
In kernel/power/swap.c (ffffffff810d9a68)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff811d4bb0)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811d9a9d)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811de4b4)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e465d)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e8703)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811eebf7)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff811f0b69)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff811f34e1)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:scan_swap_map
```
```
In mm/zswap.c (ffffffff811f6d2a)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff811fc614)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812117f0)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812162b4)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8121e898)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a4fdd)
Location: include/linux/swapops.h:26
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
In kernel/power/swap.c (ffffffff810e0548)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff811e4be0)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811e95d3)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811ee2cb)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4c66)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6bb9)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f99b4)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff811ff528)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81201569)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81203f7a)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_page
  - mm/swapfile.c:scan_swap_map
```
```
In mm/zswap.c (ffffffff812076db)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8120d100)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff812239b0)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228868)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81230eb9)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812ba942)
Location: include/linux/swapops.h:26
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
In kernel/power/swap.c (ffffffff810df67c)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff811ef2c7)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f4743)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811f9291)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff622)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81201b22)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81204586)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8120a1df)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8120c41d)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8120f613)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff81212e23)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81218f5e)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/migrate.c (ffffffff8122f321)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231e6c)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffffffff8123c720)
Location: include/linux/swapops.h:26
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812c8521)
Location: include/linux/swapops.h:26
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
In kernel/power/swap.c (ffffffff810e790c)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff81206680)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8120e7b8)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81211689)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218257)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8121abb0)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121d3bf)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81223428)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812260a7)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swap_readahead_detect
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8122ae83)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8122d8ca)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81233f0f)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81237592)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b3ff)
Location: include/linux/swapops.h:27
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
In mm/huge_memory.c (ffffffff81255bfd)
Location: include/linux/swapops.h:27
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
In mm/memcontrol.c (ffffffff8125c3aa)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (0)
Location: include/linux/swapops.h:27
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ec4c1)
Location: include/linux/swapops.h:27
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
In kernel/power/swap.c (ffffffff810eed88)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff81226701)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8122ffcd)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8123241d)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239381)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123cb43)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123f541)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812462a6)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248478)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/swapfile.c (ffffffff8124d112)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8125068a)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81256eff)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8125aa91)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e430)
Location: include/linux/swapops.h:27
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
In mm/huge_memory.c (ffffffff81279a9a)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8127fc0c)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff81293698)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81319b04)
Location: include/linux/swapops.h:27
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
In kernel/power/swap.c (ffffffff810fa408)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff8123aa41)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81241cbf)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81245bf0)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124daeb)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81251019)
Location: include/linux/swapops.h:27
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
In mm/rmap.c (ffffffff81253c47)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8125a6c6)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ca48)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
```
```
In mm/swapfile.c (ffffffff81261512)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff81264b5a)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8126b575)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8126e9cc)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812832be)
Location: include/linux/swapops.h:27
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
In mm/huge_memory.c (ffffffff8128e07a)
Location: include/linux/swapops.h:27
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8129457c)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812a7c3e)
Location: include/linux/swapops.h:27
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81330bdd)
Location: include/linux/swapops.h:27
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
In kernel/power/swap.c (ffffffff81102ab8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff8124bcf4)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81254626)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81257d52)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125f921)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81263305)
Location: include/linux/swapops.h:29
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
In mm/rmap.c (ffffffff81265e6a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812757a6)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277c3d)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff8127c482)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8127f77a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81286834)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81289e3a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f671)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a89fd)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b092f)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812c47d6)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813589fe)
Location: include/linux/swapops.h:29
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
In kernel/power/swap.c (ffffffff8110ef08)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff8125a1e4)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262b86)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff81266262)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e131)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81271ab5)
Location: include/linux/swapops.h:29
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
In mm/rmap.c (ffffffff81274797)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81284776)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128772d)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff8128bf62)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8128f56a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81296423)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812999aa)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aea1d)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812b9f7d)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c238f)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812d61f9)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81370c4e)
Location: include/linux/swapops.h:29
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
In kernel/power/swap.c (ffffffff8111a198)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff812886ec)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81294a9b)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
```
```
In mm/mincore.c (ffffffff812965bb)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e772)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a1e65)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff812a5af0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812b691f)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b9891)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_ra_info
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff812bee62)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812c220a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812c99c6)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812cebe6)
Location: include/linux/swapops.h:29
Inline: True
```
```
In mm/migrate.c (ffffffff812e4154)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812eeb57)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812f5d59)
Location: include/linux/swapops.h:29
Inline: True
```
```
In mm/hmm.c (ffffffff8130b41b)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813b8706)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In kernel/power/swap.c (ffffffff81115be8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff812923d2)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129f31b)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a152e)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9b32)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad92a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff812b0f6b)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c2b6f)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c52fa)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff812caa82)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:swap_alloc_cluster
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812cdf03)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812d53c7)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812da526)
Location: include/linux/swapops.h:29
Inline: True
```
```
In mm/migrate.c (ffffffff812f0189)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812fa1b7)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81301829)
Location: include/linux/swapops.h:29
Inline: True
```
```
In mm/hmm.c (ffffffff813172db)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813ca136)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In kernel/power/swap.c (ffffffff81116168)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff81297d2e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a42d9)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (ffffffff812a6d21)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aefbd)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2d9c)
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
In mm/rmap.c (ffffffff812b6533)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff812c99eb)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbfa8)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff812d1562)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff812d45a3)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812dc399)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812e1d82)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/migrate.c (ffffffff812f5866)
Location: include/linux/swapops.h:39
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
In mm/huge_memory.c (ffffffff81300f72)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/memcontrol.c (ffffffff81308019)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/hmm.c (ffffffff8131d5f6)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813d0cfc)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In kernel/power/swap.c (ffffffff81136408)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff812d876e)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e5736)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff812e8201)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f07ad)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f495c)
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
In mm/rmap.c (ffffffff812f8b78)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8130ea0b)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311178)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81316c62)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff8131a8ba)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81323538)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81328e60)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/migrate.c (ffffffff8133fe32)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134abe2)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/memcontrol.c (ffffffff813521a9)
Location: include/linux/swapops.h:39
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135ebb9)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a996)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff814224b6)
Location: include/linux/swapops.h:39
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In kernel/power/swap.c (ffffffff811588a8)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (0)
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/gup.c (ffffffff813386ef)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81347a8a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff81349573)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81353e60)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81358892)
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
In mm/rmap.c (ffffffff8135f288)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81376bc6)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c1b5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81382281)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff81385ea5)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81390fe4)
Location: include/linux/swapops.h:41
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
Location: include/linux/swapops.h:41
Inline: True
```
```
In mm/migrate.c (ffffffff813b4d73)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b73bb)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1d77)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff813ce873)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813d905a)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff813e44a9)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8b18)
Location: include/linux/swapops.h:41
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8145da80)
Location: include/linux/swapops.h:41
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff814995b1)
Location: include/linux/swapops.h:41
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8118a9d8)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (0)
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/memory.c (ffffffff813bfe40)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813c195d)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813ce30a)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2f93)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813da140)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f4390)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f9955)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff81400ab1)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:arch_max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff81403ce5)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff814127f5)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
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
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/ksm.c (ffffffff81421ab9)
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/migrate.c (ffffffff81433f23)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438f07)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443f57)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81453454)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8145f04f)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf7a)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff81470a9d)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff814ed4ad)
Location: include/linux/swapops.h:86
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152e859)
Location: include/linux/swapops.h:86
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
In kernel/power/swap.c (ffffffff8119c138)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (0)
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/memory.c (ffffffff813f4afb)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff813f67f6)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff81402be7)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81407bf3)
Location: include/linux/swapops.h:86
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
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/rmap.c (ffffffff8140e882)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81427a7d)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c7ec)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8143395a)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffff8143717a)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff81445e03)
Location: include/linux/swapops.h:86
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
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/ksm.c (ffffffff81456861)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81469877)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f742)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814794d9)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/khugepaged.c (ffffffff8147f02d)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff8148918d)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81494fff)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0cd5)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a5011)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff815241b4)
Location: include/linux/swapops.h:86
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81566b67)
Location: include/linux/swapops.h:86
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
In kernel/power/swap.c (ffffffff811ab278)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/shmem.c (0)
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/memory.c (ffffffff8142114c)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mincore.c (ffffffff814224a6)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8142f1fa)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814342b7)
Location: include/linux/swapops.h:86
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
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/rmap.c (ffffffff8143af4c)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81461290)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f34)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:clear_shadow_from_swap_cache
```
```
In mm/swapfile.c (ffffffff8146cd4a)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (0)
Location: include/linux/swapops.h:86
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147f83b)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8148517e)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/ksm.c (ffffffff81491357)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff814987a7)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d5fb)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8a6c)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814afd05)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b9046)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c48ff)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d2eef)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814d60d0)
Location: include/linux/swapops.h:86
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/userfaultfd.c (ffffffff81558701)
Location: include/linux/swapops.h:86
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159d333)
Location: include/linux/swapops.h:86
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
In mm/gup.c (ffff8000102f1d10)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f8340)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffff8000102fd04c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffff800010305418)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffff800010307068)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffff80001030a0ac)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffff80001031eac8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff800010322244)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffff800010326954)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffff80001032bf30)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffff800010335ddc)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffff800010350d50)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff80001035608c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/memcontrol.c (ffff800010363e4c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffff80001037b778)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffff8000104396e8)
Location: include/linux/swapops.h:29
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
In kernel/power/swap.c (c03c2880)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (c0514228)
Location: include/linux/swapops.h:29
Inline: True
```
```
In mm/memory.c (c051ab1c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c051c634)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0523410)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0524dd8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0526780)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0537710)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053a900)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (c053e12c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c0542278)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/migrate.c (c0552408)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c0556188)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (c05664d0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c0601380)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In mm/gup.c (c0000000003b7df0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c3c64)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (c0000000003c86fc)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d2670)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (c0000000003d57f8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d97e0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (c0000000003f3118)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7c84)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (c0000000003fd390)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c000000000402acc)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (c00000000040fe60)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (c000000000413120)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434d20)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (c0000000004443a0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (c000000000450e88)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (c0000000004704f0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (c00000000054cafc)
Location: include/linux/swapops.h:29
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
In mm/gup.c (ffffffe00020462e)
Location: include/linux/swapops.h:29
Inline: True
```
```
In mm/memory.c (ffffffe0002088c2)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffe00020bb7c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffe000211256)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffe0002125fc)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffe000213f92)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffe000220562)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffe00022325a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffe000226780)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffe00022ab50)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffe000231eba)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffe00023f720)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffe000241cfc)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffe000251f6e)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffe0002d353c)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In kernel/power/swap.c (ffffffff81107498)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff81252834)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b1d6)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125e8b2)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266781)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8126a105)
Location: include/linux/swapops.h:29
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
In mm/rmap.c (ffffffff8126cde7)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127cdc6)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fcf7)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff81284542)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff81287b4a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8128ea03)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81291f8a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a6ffd)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812b255d)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812ba96f)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812ce7d9)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8136922e)
Location: include/linux/swapops.h:29
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
In kernel/power/swap.c (ffffffff810f83c8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff8124589b)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124d88a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mincore.c (ffffffff81250c62)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258e33)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8125bf96)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125ee23)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8126ec29)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81271b37)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff81275aed)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff812799aa)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff812807b3)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81283d93)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298a3a)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812a38e1)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812abb1b)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812bf4af)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff813594f6)
Location: include/linux/swapops.h:29
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
In kernel/power/swap.c (ffffffff811053d8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff812505d4)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81258f76)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8125c652)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264521)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267ea5)
Location: include/linux/swapops.h:29
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
In mm/rmap.c (ffffffff8126ab87)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8127ab66)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127db1d)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff81282352)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8128595a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8128c813)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8128fd9a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a4e0d)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812b036d)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812b877f)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812cc5e9)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff81366cfe)
Location: include/linux/swapops.h:29
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
In kernel/power/swap.c (ffffffff811107b8)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In mm/gup.c (ffffffff8125ff54)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81268976)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In mm/mincore.c (ffffffff8126c039)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81273edf)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81277827)
Location: include/linux/swapops.h:29
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
In mm/rmap.c (ffffffff8127a4f0)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff8128a747)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d6cd)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:total_swapcache_pages
```
```
In mm/swapfile.c (ffffffff81292042)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:swapdev_block
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/zswap.c (ffffffff8129567a)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
```
```
In mm/hugetlb.c (ffffffff8129c5f1)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8129f233)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5969)
Location: include/linux/swapops.h:29
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
In mm/huge_memory.c (ffffffff812c06ad)
Location: include/linux/swapops.h:29
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
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
```
In mm/memcontrol.c (ffffffff812c8dbf)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812dd349)
Location: include/linux/swapops.h:29
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/proc/task_mmu.c (ffffffff8137a34e)
Location: include/linux/swapops.h:29
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
