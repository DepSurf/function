# Function: <code>__mmu_notifier_invalidate_range_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3a10)
Location: mm/mmu_notifier.c:205
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
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff811e3a10-ffffffff811e3aa3: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202490)
Location: mm/mmu_notifier.c:205
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
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81202490-ffffffff81202523: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812142d0)
Location: mm/mmu_notifier.c:205
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
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812142d0-ffffffff81214363: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121f760)
Location: mm/mmu_notifier.c:192
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_writeback_mapping_range
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8121f760-ffffffff8121f7f3: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct *mm, long unsigned int start, long unsigned int end, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123a960)
Location: mm/mmu_notifier.c:192
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/khugepaged.c:khugepaged
  - fs/dax.c:dax_writeback_mapping_range
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8123a960-ffffffff8123aa0a: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct *mm, long unsigned int start, long unsigned int end, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125dec0)
Location: mm/mmu_notifier.c:192
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_writeback_mapping_range
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8125dec0-ffffffff8125df66: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812726b0)
Location: mm/mmu_notifier.c:194
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
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_vma
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812726b0-ffffffff81272744: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128e260)
Location: mm/mmu_notifier.c:192
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8128e260-ffffffff8128e303: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129e2c0)
Location: mm/mmu_notifier.c:193
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8129e2c0-ffffffff8129e363: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d28a0)
Location: mm/mmu_notifier.c:569
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812d28a0-ffffffff812d2962: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812de2d0)
Location: mm/mmu_notifier.c:592
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812de2d0-ffffffff812de392: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5ab0)
Location: mm/mmu_notifier.c:592
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812e5ab0-ffffffff812e5b72: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:592
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81cc08b7-ffffffff81cc08cc: __mmu_notifier_invalidate_range_end.cold (STB_LOCAL)
ffffffff8132d990-ffffffff8132da61: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:592
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81e72d57-ffffffff81e72d6c: __mmu_notifier_invalidate_range_end.cold (STB_LOCAL)
ffffffff8139dba0-ffffffff8139dc80: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:592
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff820672b1-ffffffff820672c6: __mmu_notifier_invalidate_range_end.cold (STB_LOCAL)
ffffffff8141d110-ffffffff8141d1f0: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:592
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff820e6b73-ffffffff820e6b88: __mmu_notifier_invalidate_range_end.cold (STB_LOCAL)
ffffffff814506d0-ffffffff814507ae: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:574
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
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:do_pagemap_scan
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff821c3c55-ffffffff821c3c6a: __mmu_notifier_invalidate_range_end.cold (STB_LOCAL)
ffffffff8148a400-ffffffff8148a4a3: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033d7e0)
Location: mm/mmu_notifier.c:193
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffff80001033d7e0-ffff80001033d8b4: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c0543e5c)
Location: mm/mmu_notifier.c:193
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
c0543e5c-c0543f3c: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c000000000418fa0)
Location: mm/mmu_notifier.c:193
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
c000000000418fa0-c0000000004190fc: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe000232e9a)
Location: mm/mmu_notifier.c:193
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
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffe000232e9a-ffffffe000232f2e: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812968a0)
Location: mm/mmu_notifier.c:193
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812968a0-ffffffff81296943: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812884b0)
Location: mm/mmu_notifier.c:193
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812884b0-ffffffff81288553: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812946b0)
Location: mm/mmu_notifier.c:193
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812946b0-ffffffff81294753: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range *range, bool only_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a4520)
Location: mm/mmu_notifier.c:193
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/oom_kill.c:__oom_reap_task_mm
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:wp_page_copy
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
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/khugepaged.c:collapse_huge_page
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff812a4520-ffffffff812a45c3: __mmu_notifier_invalidate_range_end (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool only_end</code>
</li>
</ul>
</details>
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
<b>Param reordered. </b>
<code>mm, start, end, only_end</code> ➡️ <code>range, only_end</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool only_end</code>
</li>
</ul>
</details>
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
