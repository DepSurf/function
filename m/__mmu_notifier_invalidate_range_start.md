# Function: <code>__mmu_notifier_invalidate_range_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_start(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3990)
Location: mm/mmu_notifier.c:190
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:zap_page_range
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff811e3990-ffffffff811e3a07: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_start(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202410)
Location: mm/mmu_notifier.c:190
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81202410-ffffffff81202487: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_start(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81214250)
Location: mm/mmu_notifier.c:190
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81214250-ffffffff812142c7: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_start(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121f6e0)
Location: mm/mmu_notifier.c:177
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8121f6e0-ffffffff8121f757: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_start(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123a8e0)
Location: mm/mmu_notifier.c:177
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8123a8e0-ffffffff8123a95a: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_start(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125de40)
Location: mm/mmu_notifier.c:177
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8125de40-ffffffff8125deba: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:170
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81272e77-ffffffff81272ead: __mmu_notifier_invalidate_range_start.cold.5 (STB_LOCAL)
ffffffff812727d0-ffffffff81272863: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:168
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8128e677-ffffffff8128e6aa: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff8128e1c0-ffffffff8128e25e: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8129e437-ffffffff8129e483: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff8129e220-ffffffff8129e2be: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d2840)
Location: mm/mmu_notifier.c:513
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812d2840-ffffffff812d2891: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812de270)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812de270-ffffffff812de2c1: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e59c0)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812e59c0-ffffffff812e5aaf: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81cc084d-ffffffff81cc08b7: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff8132d7f0-ffffffff8132d98d: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81e72ceb-ffffffff81e72d57: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff8139d9f0-ffffffff8139db94: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8206729c-ffffffff820672b1: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff8141cf00-ffffffff8141d0f6: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff820e6b5e-ffffffff820e6b73: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff814504c0-ffffffff814506b5: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:536
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:move_pages_pte
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff821c3c40-ffffffff821c3c55: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff8148a1f0-ffffffff8148a3e5: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033d6d0)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffff80001033d6d0-ffff80001033d7e0: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c0543d04)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c0543d04-c0543e5c: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c000000000418e00)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c000000000418e00-c000000000418f94: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe000232db8)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:try_to_merge_one_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffe000232db8-ffffffe000232e9a: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81296a17-ffffffff81296a63: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff81296800-ffffffff8129689e: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81288627-ffffffff81288673: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff81288410-ffffffff812884ae: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81294827-ffffffff81294873: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff81294610-ffffffff812946ae: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __mmu_notifier_invalidate_range_start(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:162
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_free_single_vma
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812a4697-ffffffff812a46e3: __mmu_notifier_invalidate_range_start.cold (STB_LOCAL)
ffffffff812a4480-ffffffff812a451e: __mmu_notifier_invalidate_range_start (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier_range *range</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
