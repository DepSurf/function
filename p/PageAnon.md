# Function: <code>PageAnon</code>

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
In arch/x86/mm/gup.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In kernel/futex.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/gup.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/memory.c (ffffffff811be083)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/rmap.c (ffffffff811cc2fd)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/rmap.c:page_referenced
```
```
In mm/hugetlb.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/migrate.c (ffffffff811f267c)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/memcontrol.c (ffffffff811fd2d4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In mm/page_idle.c (ffffffff8120832e)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/page-flags.h:318
Inline: True
```
```
In fs/proc/page.c (ffffffff812880b4)
Location: include/linux/page-flags.h:318
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff811076a7)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81199e1e)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/swap.c (ffffffff811b1e17)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811b98c4)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff811c493f)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/memory.c (ffffffff811d82f9)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffff811e94b6)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff811fc14a)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812053bc)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff81211f57)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81217872)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8121bff9)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812215f7)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff81227ed0)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffffffff8122dca6)
Location: include/linux/page-flags.h:384
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812a475d)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812b5734)
Location: include/linux/page-flags.h:384
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8110ee67)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811a957b)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/swap.c (ffffffff811c2452)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811c9f19)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff811d4a4f)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/memory.c (ffffffff811e9004)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffff811fa806)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8120cc16)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81216a83)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81224125)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81229e1f)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8122d7ae)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81233d67)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff8123a47a)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffffffff812401f6)
Location: include/linux/page-flags.h:400
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba0d6)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812cafb8)
Location: include/linux/page-flags.h:400
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8111010e)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811b0a86)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/swap.c (ffffffff811cc57f)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811d26e6)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff811dd86f)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/memory.c (ffffffff811f4244)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffff81205435)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff81218557)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8122248c)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8122fad1)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81235a4d)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8123a096)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8123f592)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_list
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff81245f0b)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffffffff8124c096)
Location: include/linux/page-flags.h:403
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812c7824)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812d83f2)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8111b82e)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811c45ef)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/swap.c (ffffffff811e156f)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff811e7bdd)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff811f32ef)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/memory.c (ffffffff8120bf56)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff8121e3e5)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812333eb)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8123d7c9)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124d2a5)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812547c2)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81258756)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff8125f330)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff81265f43)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffffffff8126c476)
Location: include/linux/page-flags.h:404
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812eb433)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff812fcaf2)
Location: include/linux/page-flags.h:404
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8112834e)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811e4b0d)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/swap.c (ffffffff81202cbb)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81209033)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8121452f)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/memory.c (ffffffff8122cb16)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff812402a5)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812563ab)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81260dea)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81271193)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81279b5c)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8127d164)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
```
```
In mm/memcontrol.c (ffffffff812837e9)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff8128a3b4)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff81291016)
Location: include/linux/page-flags.h:411
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318763)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff8132a70f)
Location: include/linux/page-flags.h:411
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81133c2e)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff811f51c7)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8121564b)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8121bd13)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff812273ff)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff8123943e)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81240066)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff812549a5)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8126a8ba)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812755c1)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812857aa)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128e139)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81291cdd)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff81297359)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff8129f35d)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812a6036)
Location: include/linux/page-flags.h:428
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132f675)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
```
```
In fs/proc/page.c (ffffffff81341a6c)
Location: include/linux/page-flags.h:428
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8113eb92)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8120cec0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8122504f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122b97f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff812370ef)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff8124a49e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812521a7)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff81266c55)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff81285a42)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81291fc8)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8129fa89)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8aa7)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812abf5e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812b2e85)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812b883d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812c1758)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813570a8)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81369e89)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8114a630)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121a81d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff81232ecf)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81239848)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8124535f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81258a5c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81260787)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff81275575)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8129561c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812a1d48)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b0e29)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ba027)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812bd76e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812c4955)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812cc18d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812d3688)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136f678)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813820a9)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8115b174)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81247235)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8126045b)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81266183)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
```
```
In mm/util.c (ffffffff81272eaf)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81287243)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81290f64)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
  - mm/memory.c:copy_one_pte
```
```
In mm/rmap.c (ffffffff812a6b4b)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812c8d21)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812d59fe)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812e5f09)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812eec05)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page_tail
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812f2eb4)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812fa402)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mc_handle_present_pte
```
```
In mm/memory-failure.c (ffffffff81302285)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffffffff8130913a)
Location: include/linux/page-flags.h:477
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b6ed8)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813cc6d9)
Location: include/linux/page-flags.h:477
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81157298)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812518b1)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8126a58b)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81270b3a)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:page_check_dirty_writeback
```
```
In mm/util.c (ffffffff8127d58f)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81be752e)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8129b9ec)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b1feb)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812d48a1)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812e14ce)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f135c)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fa265)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812fd4f6)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff813050b0)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff8130dd0b)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
  - mm/memory-failure.c:__get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffffffff81314faa)
Location: include/linux/page-flags.h:481
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c8578)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813de33d)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff811586ca)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81255a87)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8126f6bc)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81275451)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8128271f)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81bd93c6)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812a0ad0)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b76bb)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_munlock
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812db66f)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812e8be6)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812f765d)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81301042)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff81304255)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff8130a54b)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813143b8)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff8131b6ea)
Location: include/linux/page-flags.h:481
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cf5b9)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff813e5121)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8117d5da)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81291734)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff812ac80c)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff812b3020)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff812c083f)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81cbbe07)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812e1bf0)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:validate_page_before_insert
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/rmap.c (ffffffff812f9dcb)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:make_device_exclusive_range
  - mm/rmap.c:page_mlock
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff81322889)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81330b16)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81341cca)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:__unmap_and_move
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8134acb2)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff8134df88)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff81355cab)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
```
```
In mm/memory-failure.c (ffffffff813604d4)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:me_pagecache_clean
  - mm/memory-failure.c:collect_procs
```
```
In mm/userfaultfd.c (ffffffff81366e3b)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/page_idle.c (ffffffff813689ba)
Location: include/linux/page-flags.h:501
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81420999)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81436cf1)
Location: include/linux/page-flags.h:501
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex/core.c (ffffffff811b2697)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff812e6bc2)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff81306b48)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
```
```
In mm/util.c (ffffffff8131d7c0)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81e6da8d)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8133a7d3)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81343d96)
Location: include/linux/page-flags.h:668
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
In mm/mprotect.c (ffffffff81354125)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8136009d)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
```
```
In mm/swapfile.c (ffffffff8137e97c)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81391028)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:free_huge_page
```
```
In mm/ksm.c (ffffffff813a1737)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff813b3c2d)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/migrate_device.c (ffffffff813b737d)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1e3c)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:split_huge_page_to_list
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
In mm/khugepaged.c (ffffffff813c71d3)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff813ce7f4)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813dbb57)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff813e42ee)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/memremap.c (ffffffff813e7c1a)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff814996e3)
Location: include/linux/page-flags.h:668
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff814b17fe)
Location: include/linux/page-flags.h:668
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
In kernel/futex/core.c (ffffffff811f3537)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff813506b1)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/debug.c (ffffffff813adc7e)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813b22bd)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b6ebb)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
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
In mm/mprotect.c (ffffffff813ce6e3)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff813db008)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/rmap.c:hugepage_add_new_anon_rmap
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_rmap
```
```
In mm/madvise.c (ffffffff813f51a3)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/swapfile.c (ffffffff813fd30e)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8141291a)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81420708)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate_device.c (ffffffff81438e89)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81444056)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/khugepaged.c (ffffffff8144b085)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff81453258)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81462835)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff8146bd9a)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/memremap.c (ffffffff8146fa54)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff8152d8a0)
Location: include/linux/page-flags.h:659
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81548264)
Location: include/linux/page-flags.h:659
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
In kernel/futex/core.c (ffffffff81207ca3)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff813819fe)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/debug.c (ffffffff813e200f)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff813e4634)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813f2151)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81402f16)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8140e276)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/swapfile.c (ffffffff814305eb)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445f44)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/ksm.c (ffffffff814553d8)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate_device.c (ffffffff8146f6c8)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814795eb)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
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
In mm/khugepaged.c (ffffffff8147ed9c)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
```
```
In mm/memcontrol.c (ffffffff81488eb4)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814985b5)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:me_pagecache_clean
```
```
In mm/userfaultfd.c (ffffffff814a0b68)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/memremap.c (ffffffff814a4234)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff81565cd0)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8157fe37)
Location: include/linux/page-flags.h:653
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
In kernel/events/uprobes.c (ffffffff813aae16)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/debug.c (ffffffff8140c820)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (ffffffff8140efdf)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81418d28)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (ffffffff8142f4e0)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:can_change_pte_writable
```
```
In mm/rmap.c (ffffffff8143aa8c)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147f93c)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
```
```
In mm/ksm.c (ffffffff8148f2ec)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff814a24c6)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
```
```
In mm/memcontrol.c (ffffffff814b8daf)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c7ba3)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/userfaultfd.c (ffffffff814d036b)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/memremap.c (ffffffff814d5084)
Location: include/linux/page-flags.h:655
Inline: True
Inline callers:
  - mm/memremap.c:free_zone_device_page
```
```
In fs/proc/task_mmu.c (ffffffff8159dcad)
Location: include/linux/page-flags.h:655
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
In fs/proc/page.c (ffffffff815b8826)
Location: include/linux/page-flags.h:655
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In virt/kvm/arm/mmu.c (ffff8000100cad3c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
```
```
In kernel/futex.c (ffff8000101b7aa0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffff8000102a5c5c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffff8000102c2f5c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffff8000102ca72c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffff8000102d829c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffff8000102f0a28)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffff8000102f7ae0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffff80001030b4bc)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffff800010334334)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffff800010341594)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff800010351458)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010359568)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffff80001035ec64)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffff800010367598)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffff8000103704e4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
```
```
In mm/page_idle.c (ffff800010379018)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffff800010438d78)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffff800010450214)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (c0401840)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c04d4e80)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (c04ee098)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (c04f4598)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (c04ff3c4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (c0513e9c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/gup.c (c0514924)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c051a2bc)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (c0527938)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (c0546604)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c0552968)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (c0558ce0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/page_idle.c (c0564570)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (c0601304)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (c0613228)
Location: include/linux/page-flags.h:461
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
In kernel/futex.c (c00000000021ceb0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (c000000000358bc8)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (c00000000037d240)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (c0000000003872cc)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (c000000000397fd4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (c0000000003b53d0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0000000003c0a38)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (c0000000003db600)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:__page_set_anon_rmap
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (c00000000040d160)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (c00000000041ca40)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (c0000000004376e4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c000000000444440)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (c0000000004480a4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (c000000000454ba4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (c000000000461428)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (c00000000046c234)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054c65c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (c000000000568214)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffe00013c7d6)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/swap.c (ffffffe0001e4244)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffe0001e97d0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffe0001f2bb0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffe000204190)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffe00020804e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffe000214e70)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffe0002303b2)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffe000234f60)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffe00023fcd2)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/memcontrol.c (ffffffe000245730)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/page_idle.c (ffffffe000250854)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d2e28)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffe0002e31ac)
Location: include/linux/page-flags.h:461
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
In kernel/futex.c (ffffffff81142c50)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81212e6d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8122b51f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81231e98)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8123d9af)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff812510ac)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81258dd7)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff8126dbc5)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8128dbfc)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8129a328)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a9409)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b2607)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b5d4e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812bcf35)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812c476d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812cbc68)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81367c58)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8137a689)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81135fb0)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81205bdd)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8121e60f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff81224f58)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff812309af)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff81243fec)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8124b287)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff8125fbf5)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8127f97e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8128bee8)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8129ad69)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3995)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812a6f08)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812ae075)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812b57ad)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812bcad8)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813588f8)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8136b159)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff81140b00)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff81210c0d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff812292bf)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8122fc38)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8123b74f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff8124ee4c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81256b77)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff8126b965)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8128ba0c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81298138)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812a7219)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b0417)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812b3b5e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812bad45)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812c257d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812c9a78)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81365728)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff81378159)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/futex.c (ffffffff8114dd74)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In kernel/events/uprobes.c (ffffffff8121fb20)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/swap.c (ffffffff8123865f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/swap.c:mark_page_lazyfree
  - mm/swap.c:perf_trace_mm_lru_insertion
  - mm/swap.c:trace_event_raw_event_mm_lru_insertion
```
```
In mm/vmscan.c (ffffffff8123f07e)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/util.c (ffffffff8124ae5f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/util.c:__page_mapcount
```
```
In mm/debug.c (ffffffff8125e7cc)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812665e5)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_insert_page
```
```
In mm/rmap.c (ffffffff8127b2f5)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_locked
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:try_to_unmap
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff8129b802)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812a7ed4)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812b7524)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812c0757)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:can_split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/khugepaged.c (ffffffff812c3f9f)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
```
```
In mm/memcontrol.c (ffffffff812cb495)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:mem_cgroup_move_account
  - mm/memcontrol.c:mem_cgroup_charge_statistics
```
```
In mm/memory-failure.c (ffffffff812d3017)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_hwpoison_page
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:collect_procs
```
```
In mm/page_idle.c (ffffffff812da768)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81378e08)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_account
  - fs/proc/task_mmu.c:smaps_page_accumulate
```
```
In fs/proc/page.c (ffffffff8138bc09)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
