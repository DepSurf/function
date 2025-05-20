# Function: <code>folio_test_anon</code>

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
In kernel/futex/core.c (ffffffff811b26ab)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812e6bd6)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff81306b5d)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8130e2cf)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8131df63)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/util.c:folio_mapcount
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81e6daa1)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8133a7e0)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343d9e)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81354138)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813600ab)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/swapfile.c (ffffffff8137e990)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81391036)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:free_huge_page
```
```
In mm/ksm.c (ffffffff813a1748)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff813b3c42)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b738e)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1e50)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff813c71e7)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff813ce808)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813dbb6c)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff813e4302)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff813e6501)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff813e7c2b)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff814996f8)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff814b180f)
Location: include/linux/page-flags.h:663
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff811f354b)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff813506c5)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff81370faa)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81379c65)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/vmscan.c:isolate_folio
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/debug.c (ffffffff813adc92)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813b22ca)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813bbf4f)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff813ce6f5)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff813db016)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff813f51b7)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd322)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8141291f)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:free_huge_page
```
```
In mm/ksm.c (ffffffff81420719)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81434890)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438e9e)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8144406b)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/khugepaged.c (ffffffff8144b0a7)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff8145326c)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff81462849)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff8146bdae)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff8146dfb2)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff8146fa68)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff8152d8b3)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81548272)
Location: include/linux/page-flags.h:654
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff81207cb7)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81381a10)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff813a315a)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813ad9cd)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/debug.c (ffffffff813e2023)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e464a)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f097e)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81402f28)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8140f760)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:folio_add_new_anon_rmap
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff81427eec)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff814305ff)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445f49)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:free_huge_page
```
```
In mm/ksm.c (ffffffff814553e9)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8146a0e5)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f6dc)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814795ff)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/khugepaged.c (ffffffff8147edb7)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff81488ec8)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814985c9)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff814a0b7d)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff814a2850)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff814a4248)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff81565ce3)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8157fe45)
Location: include/linux/page-flags.h:648
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff8121eea1)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff813aae27)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff813ccdca)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/swap.c:folio_mark_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff813d6ddd)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:walk_pte_range
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/debug.c (ffffffff8140c834)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8140eff5)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814201e9)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff8142f4f2)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff81438411)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_pmd
  - mm/rmap.c:folio_remove_rmap_ptes
  - mm/rmap.c:folio_remove_rmap_ptes
  - mm/rmap.c:folio_add_anon_rmap_pmd
  - mm/rmap.c:folio_add_anon_rmap_ptes
  - mm/rmap.c:folio_mkclean
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:folio_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/madvise.c (ffffffff81461b56)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f94e)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:free_huge_folio
```
```
In mm/ksm.c (ffffffff8148f2fd)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff814990b2)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_unmap
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d88f)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8b93)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_folio
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/khugepaged.c (ffffffff814afa4d)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff814b8dc3)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff814c7bb7)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff814d2c70)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff814d36ed)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_clear_pte_refs
```
```
In mm/memremap.c (ffffffff814d5098)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff8159dcc0)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff815b8834)
Location: include/linux/page-flags.h:650
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
