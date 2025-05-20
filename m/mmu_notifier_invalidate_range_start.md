# Function: <code>mmu_notifier_invalidate_range_start</code>

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
In kernel/events/uprobes.c (ffffffff8118778d)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bc586)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:zap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c86c8)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c92fa)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff811dd80f)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff811e53f5)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f32fb)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f50a4)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/proc/task_mmu.c (ffffffff812771c3)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81199d8d)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811d71cc)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811e48bc)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e56d4)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811ee752)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff811fc3e8)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81203f87)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff812130e0)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81215dcd)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a028)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a375d)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff811a94ea)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811e6e76)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811f48dc)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5901)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811ff0a2)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8120ced8)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81215f94)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81225450)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812283ec)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e3c7)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812b9140)
Location: include/linux/mmu_notifier.h:278
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff811b0a1a)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811f1b66)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811ff82a)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812006de)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81204219)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81209c4f)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81218d38)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812216bd)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81230b2c)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81234808)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff812381e0)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812c738b)
Location: include/linux/mmu_notifier.h:258
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff811c458b)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff812089af)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81217e34)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218ed1)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8121cfb5)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81222d7f)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81233ce8)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8123c9cb)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124c730)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255976)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81258c7b)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812eb1ab)
Location: include/linux/mmu_notifier.h:261
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff811e4aa6)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/oom_kill.c (ffffffff811f2df6)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81229a29)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81239bf6)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a875)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123ee91)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81244bae)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81256cc0)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812602a7)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812702c6)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279826)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127c093)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8131733c)
Location: include/linux/mmu_notifier.h:280
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff811f5153)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8123ce13)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8124d56c)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ea73)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81253443)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81258f64)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8126b254)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812749e6)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81284997)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
```
```
In mm/huge_memory.c (ffffffff8128ba77)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290710)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8132e7b5)
Location: include/linux/mmu_notifier.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8120ce58)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8124ea86)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8125fd38)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260dcf)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812656bc)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127478c)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81286534)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8128f6ac)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812a66b8)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812ab8fc)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8135744b)
Location: include/linux/mmu_notifier.h:311
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8121a136)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8125d027)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8126e81e)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f557)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81273fcc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81283720)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81296114)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8129f41c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812af732)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812b7b80)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bd04c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8136ef80)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81246abc)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8128d64e)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8129ec33)
Location: include/linux/mmu_notifier.h:440
Inline: True
```
```
In mm/mremap.c (ffffffff812a02cd)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812a524c)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b5583)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812c968b)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812d3a6b)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e57a4)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/huge_memory.c (ffffffff812ecd51)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff812f275f)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c4d7)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813b72c5)
Location: include/linux/mmu_notifier.h:440
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8125111f)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8129fb00)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812a9ff6)
Location: include/linux/mmu_notifier.h:446
Inline: True
```
```
In mm/mremap.c (ffffffff812ab733)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b0710)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c0843)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812d5274)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812df46b)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f0b79)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/huge_memory.c (ffffffff812f7fa2)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff812fcd86)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318417)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813c8b7a)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8125521f)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812a5369)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812af475)
Location: include/linux/mmu_notifier.h:446
Inline: True
```
```
In mm/mremap.c (ffffffff812b0b33)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b5d3a)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c77d0)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812de8b8)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e7d8b)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f6ecb)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812fe552)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff81303afb)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e607)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813cfbb9)
Location: include/linux/mmu_notifier.h:446
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81290c61)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff812e68be)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812f0ca4)
Location: include/linux/mmu_notifier.h:452
Inline: True
```
```
In mm/mremap.c (ffffffff812f24c3)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f8b5d)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130c590)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81325c92)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8132fcbb)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8134152b)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff813480f2)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff8134d831)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b9e7)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81420f96)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff812e5f5e)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff8133ed86)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff813545cf)
Location: include/linux/mmu_notifier.h:452
Inline: True
```
```
In mm/mremap.c (ffffffff813562bc)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f138)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81375b24)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81394a00)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a0088)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b847f)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff813be3e1)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff813c6a9a)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9b70)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81498e2c)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8134fbb5)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813b606b)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff813ceae9)
Location: include/linux/mmu_notifier.h:452
Inline: True
```
```
In mm/mremap.c (ffffffff813d08ea)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813d9ff0)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f30c1)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8140dd26)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8141ef62)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8143a243)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81440c41)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff814472f1)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471bc0)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152d194)
Location: include/linux/mmu_notifier.h:452
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81380d74)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff813ea936)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81403433)
Location: include/linux/mmu_notifier.h:451
Inline: True
```
```
In mm/mremap.c (ffffffff8140530a)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140e71c)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426b20)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81441100)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81453b9a)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146eeb8)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814764e5)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff8147c9c8)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6508)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81564ec2)
Location: include/linux/mmu_notifier.h:451
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff813aa135)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81417059)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8142f9c3)
Location: include/linux/mmu_notifier.h:450
Inline: True
```
```
In mm/mremap.c (ffffffff81431815)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143aefd)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81460760)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8147b232)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8148e3dd)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149d963)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814a5d75)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acbe4)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814d2a24)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7458)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159bdf2)
Location: include/linux/mmu_notifier.h:450
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffff8000102a554c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffff8000102f450c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffff8000103054a8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305e58)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff800010309ca0)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffff80001031dec0)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffff80001033584c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffff80001033ebc8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffff800010358474)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e3d8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffff80001043936c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (c04d4960)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (c0516df8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c05232bc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0523d98)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c05264d8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0537538)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/ksm.c (c0544ed8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In fs/proc/task_mmu.c (c06002e0)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (c000000000358270)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (c0000000003bb058)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c0000000003d295c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3ad4)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0000000003d95e8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0000000003f1a90)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (c00000000040fb28)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (c00000000041ac18)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000433b3c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (c000000000440d20)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000447868)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (c00000000054c1cc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In mm/memory.c (ffffffe00020666e)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffe0002113dc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211a96)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000213c68)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffe000220ebc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffe000230c8a)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffe0002348fe)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/proc/task_mmu.c (ffffffe0002d30a8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81212786)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81255677)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81266e6e)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267ba7)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126c61c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127bd70)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128e6f4)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812979fc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a7d12)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812b0160)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b562c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81367560)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81205516)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81247d77)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81258f98)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259ef4)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125e68c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126dc50)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812804b5)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812895eb)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812996d2)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812a1620)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a66ac)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81358200)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff81210526)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81253417)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81264c0e)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265947)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126a3bc)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81279b10)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128c504)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8129580c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a5b22)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812adf70)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b343c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81365030)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
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
In kernel/events/uprobes.c (ffffffff8121f46e)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/memory.c (ffffffff81262e27)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812743c0)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81275302)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81279d2c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81289700)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8129c2f4)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812a563c)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b51da)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812be2d8)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c38ad)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81378075)
Location: include/linux/mmu_notifier.h:344
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
</ul>

## Differences
