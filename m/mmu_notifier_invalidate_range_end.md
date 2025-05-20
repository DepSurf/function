# Function: <code>mmu_notifier_invalidate_range_end</code>

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
In kernel/events/uprobes.c (ffffffff811878f6)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bc724)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:zap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811c8aa3)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811c9783)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/hugetlb.c (ffffffff811dd975)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff811e544f)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff811f34dc)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f5139)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In fs/proc/task_mmu.c (ffffffff812771e0)
Location: include/linux/mmu_notifier.h:285
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
In kernel/events/uprobes.c (ffffffff81199f2d)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811d73c1)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811e4ce5)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5bac)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811ee7a0)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff811fc5d3)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8120406e)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
```
In mm/migrate.c (ffffffff812132ba)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81215e72)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8121a0ae)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a377d)
Location: include/linux/mmu_notifier.h:285
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
In kernel/events/uprobes.c (ffffffff811a9693)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811e707c)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff811f4d14)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5d8f)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/madvise.c (ffffffff811ff0f0)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8120d0bf)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81215fe2)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81225622)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81228491)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8122e44e)
Location: include/linux/mmu_notifier.h:285
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff812b915f)
Location: include/linux/mmu_notifier.h:285
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
In kernel/events/uprobes.c (ffffffff811b0b86)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811f1c1e)
Location: include/linux/mmu_notifier.h:265
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
In mm/mprotect.c (ffffffff811ffb62)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200b89)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81204743)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81209c6f)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81218ea2)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812217da)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81230d5e)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812348ac)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff8123825c)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812aa89e)
Location: include/linux/mmu_notifier.h:265
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c73ab)
Location: include/linux/mmu_notifier.h:265
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
In kernel/events/uprobes.c (ffffffff811c46e6)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff81208a8f)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812183cf)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219237)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8121d6a1)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81222d9f)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81233e45)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8123c9ea)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8124eda2)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81255aa5)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/khugepaged.c (ffffffff81258cfe)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff812ce13b)
Location: include/linux/mmu_notifier.h:268
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb1cb)
Location: include/linux/mmu_notifier.h:268
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
In kernel/events/uprobes.c (ffffffff811e4c57)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/oom_kill.c (ffffffff811f2e27)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81229992)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81239d90)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123ae50)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123f4cb)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81244bdd)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81256eb1)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812603b3)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81272c4b)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81279945)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff8127c10f)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812f86d9)
Location: include/linux/mmu_notifier.h:287
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81317369)
Location: include/linux/mmu_notifier.h:287
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
In kernel/events/uprobes.c (ffffffff811f52d8)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81204de3)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8123ceb8)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8124d963)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f02d)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81253767)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81258fa7)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8126b4b3)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81274afe)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff812817f7)
Location: include/linux/mmu_notifier.h:288
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128840c)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290794)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8130c45c)
Location: include/linux/mmu_notifier.h:288
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132e7dc)
Location: include/linux/mmu_notifier.h:288
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
In kernel/events/uprobes.c (ffffffff8120cfc2)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8121c940)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8124eb22)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8125fec7)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126138f)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812659bc)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812747bf)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81286786)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8128f855)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812a3015)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812ab96c)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133399e)
Location: include/linux/mmu_notifier.h:330
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8135745f)
Location: include/linux/mmu_notifier.h:330
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
In kernel/events/uprobes.c (ffffffff8121a2ba)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8122a346)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8125d0ce)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8126e87b)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126fb32)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812742d1)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128375f)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8129636b)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8129f5da)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812afee6)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812b4511)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bd171)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81347563)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136efb2)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (ffffffff81246c3f)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81257116)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8128d6f2)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8129ed5f)
Location: include/linux/mmu_notifier.h:467
Inline: True
```
```
In mm/mremap.c (ffffffff812a05ae)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812a556b)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b55c2)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812c98ec)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812d3c28)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e2240)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/khugepaged.c (ffffffff812f2886)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c3b7)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff8138d946)
Location: include/linux/mmu_notifier.h:467
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b72f7)
Location: include/linux/mmu_notifier.h:467
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
In kernel/events/uprobes.c (ffffffff812512af)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81261cf6)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8129fba3)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812aa128)
Location: include/linux/mmu_notifier.h:473
Inline: True
```
```
In mm/mremap.c (ffffffff812aba8f)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b09f9)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c0882)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812d547a)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812df622)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812ed546)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/khugepaged.c (ffffffff812fceaf)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813182f7)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff8139f3c6)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c8baa)
Location: include/linux/mmu_notifier.h:473
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
In kernel/events/uprobes.c (ffffffff812553a9)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812667b8)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812a5433)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812af5a7)
Location: include/linux/mmu_notifier.h:473
Inline: True
```
```
In mm/mremap.c (ffffffff812b0e8b)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b602b)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c780b)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812de9d9)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e7f5e)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f52bc)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff81303c24)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e4e7)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff813a6133)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cfbe9)
Location: include/linux/mmu_notifier.h:473
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290de8)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812a2d88)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812dee81)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
Direct callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
```
```
In mm/mprotect.c (ffffffff812f0dd6)
Location: include/linux/mmu_notifier.h:479
Inline: True
```
```
In mm/mremap.c (ffffffff812f2960)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f8d0d)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130c5cb)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81325dbe)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8132fe6c)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8133f8bc)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff8134d95f)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b8c7)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/dax.c (ffffffff813f5ba3)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420fc6)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812dd120-ffffffff812dd168: mmu_notifier_invalidate_range_end (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff812e60c7)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812fabc6)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8133ee44)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
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
In mm/mprotect.c (ffffffff8135472f)
Location: include/linux/mmu_notifier.h:479
Inline: True
```
```
In mm/mremap.c (ffffffff8135659c)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f2ee)
Location: include/linux/mmu_notifier.h:479
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
In mm/madvise.c (ffffffff81375bc4)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81394b29)
Location: include/linux/mmu_notifier.h:479
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
In mm/ksm.c (ffffffff813a023d)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b6d1c)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff813c6bc6)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9a4b)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81498e5c)
Location: include/linux/mmu_notifier.h:479
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
In kernel/events/uprobes.c (ffffffff8134fd1b)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81362cfd)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff813b612a)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
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
In mm/mprotect.c (ffffffff813cec51)
Location: include/linux/mmu_notifier.h:479
Inline: True
```
```
In mm/mremap.c (ffffffff813d0bc6)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813da1a9)
Location: include/linux/mmu_notifier.h:479
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
In mm/madvise.c (ffffffff813f3152)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8140de89)
Location: include/linux/mmu_notifier.h:479
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
In mm/ksm.c (ffffffff8141f12b)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8143871e)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff8144731e)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471a8b)
Location: include/linux/mmu_notifier.h:479
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152d1c9)
Location: include/linux/mmu_notifier.h:479
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
In kernel/events/uprobes.c (ffffffff81380eb4)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81395131)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff813ea9ae)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8140353e)
Location: include/linux/mmu_notifier.h:478
Inline: True
```
```
In mm/mremap.c (ffffffff81405602)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140e8e9)
Location: include/linux/mmu_notifier.h:478
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
In mm/madvise.c (ffffffff81426ba7)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81441269)
Location: include/linux/mmu_notifier.h:478
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
In mm/ksm.c (ffffffff81453c82)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146e40f)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/khugepaged.c (ffffffff8147c9f5)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a63db)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff81564ef7)
Location: include/linux/mmu_notifier.h:478
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aa280)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff813beef0)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff814170d8)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8142face)
Location: include/linux/mmu_notifier.h:484
Inline: True
```
```
In mm/mremap.c (ffffffff81431b27)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143b10d)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814607ea)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8147b368)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8148e539)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149d994)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814a5e65)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acd01)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
Direct callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
```
```
In mm/userfaultfd.c (ffffffff814d2d0e)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d732b)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159bf3a)
Location: include/linux/mmu_notifier.h:484
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff814aa580-ffffffff814aa5d1: mmu_notifier_invalidate_range_end (STB_LOCAL)
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
In kernel/events/uprobes.c (ffff8000102a56cc)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffff8000102b8300)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffff8000102f457c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffff80001030552c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305fd4)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff800010309ef8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffff80001031def4)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffff800010335a70)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffff80001033ec54)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffff800010355adc)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e48c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffff8000104076fc)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffff80001043939c)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (c04d4b50)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (c04e4ab0)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (c051971c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c0523578)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c052409c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0526740)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0537580)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/ksm.c (c0545094)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In fs/proc/task_mmu.c (c0600310)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (c00000000035844c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (c0000000003703d8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (c0000000003bb0ec)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c0000000003d2a90)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3e60)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0000000003d98c8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0000000003f1ac8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (c00000000040fdf8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (c00000000041ae08)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000435e8c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (c00000000043d30c)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000447958)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (c0000000005126f8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (c00000000054c204)
Location: include/linux/mmu_notifier.h:371
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
In mm/oom_kill.c (ffffffe0001dc07e)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffe0002066f0)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffe0002114b0)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211cfa)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000213e58)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffe000220ef4)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffe000230da4)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffe000234a34)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/dax.c (ffffffe0002b2d30)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffe0002d30da)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (ffffffff8121290a)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81222996)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8125571e)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81266ecb)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81268182)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126c921)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127bdaf)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128e94b)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81297bba)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a84c6)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812acaf1)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b5751)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133fb43)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81367592)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (ffffffff81205672)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81215b46)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81247e12)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8125925a)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a3a9)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125e973)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126dc8f)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812806f8)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81289743)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81299e86)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff8129eb3a)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a6797)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81330755)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81358232)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (ffffffff812106aa)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81220736)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812534be)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81264c6b)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81265f22)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126a6c1)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81279b4f)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128c75b)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812959ca)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a62d6)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812aa901)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3561)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff8133d613)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365062)
Location: include/linux/mmu_notifier.h:371
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
In kernel/events/uprobes.c (ffffffff8121f5ea)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8122f830)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81262ec3)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81274535)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812758c4)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8127a09f)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128973a)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8129c543)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812a57e2)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b65fe)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812bac59)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c39bf)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff81350527)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81378093)
Location: include/linux/mmu_notifier.h:371
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
