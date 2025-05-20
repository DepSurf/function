# Function: <code>mmu_notifier_range_init</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f50ca)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81204e45)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8123ce05)
Location: include/linux/mmu_notifier.h:320
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
In mm/mprotect.c (ffffffff8124d554)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ea5f)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125341a)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81258efc)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8126b239)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812749c9)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8128497c)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
```
```
In mm/huge_memory.c (ffffffff8128ba5c)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff81290704)
Location: include/linux/mmu_notifier.h:320
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8132e790)
Location: include/linux/mmu_notifier.h:320
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
In kernel/events/uprobes.c (ffffffff8120cdb7)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8121c8d5)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8124ea66)
Location: include/linux/mmu_notifier.h:362
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
In mm/mprotect.c (ffffffff8125fd12)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260daf)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126567e)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127470c)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128650b)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8128f67a)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/huge_memory.c (ffffffff812a6695)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812ab8e1)
Location: include/linux/mmu_notifier.h:362
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8135740a)
Location: include/linux/mmu_notifier.h:362
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
In kernel/events/uprobes.c (ffffffff8121a0bc)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8122a2db)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8125d007)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffffffff8126e800)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f53f)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81273f8e)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128369c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812960eb)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8129f3f6)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812af710)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812b7b5b)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812bd020)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff8136ef47)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (ffffffff81246a4c)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812570ab)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8128d62e)
Location: include/linux/mmu_notifier.h:502
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
In mm/mprotect.c (ffffffff8129ec15)
Location: include/linux/mmu_notifier.h:502
Inline: True
```
```
In mm/mremap.c (ffffffff812a02b5)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812a520e)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b54ff)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812c9628)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812d3a46)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e5782)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/huge_memory.c (ffffffff812ecd2c)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff812f2736)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c4b5)
Location: include/linux/mmu_notifier.h:502
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813b728c)
Location: include/linux/mmu_notifier.h:502
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
In kernel/events/uprobes.c (ffffffff812510ac)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81261c8f)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8129fae0)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812a9fd8)
Location: include/linux/mmu_notifier.h:508
Inline: True
```
```
In mm/mremap.c (ffffffff812ab71b)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b06cf)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c07bf)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812d524f)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812df446)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f0b5b)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_collect
```
```
In mm/huge_memory.c (ffffffff812f7f7d)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff812fcd5a)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813183f5)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813c8b50)
Location: include/linux/mmu_notifier.h:508
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
In kernel/events/uprobes.c (ffffffff812551ac)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81266751)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812a5349)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812af457)
Location: include/linux/mmu_notifier.h:508
Inline: True
```
```
In mm/mremap.c (ffffffff812b0b1b)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b5d0a)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c775c)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff812de89a)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812e7d66)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f6ead)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812fe52d)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff81303acf)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e5e5)
Location: include/linux/mmu_notifier.h:508
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff813cfb8f)
Location: include/linux/mmu_notifier.h:508
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
In kernel/events/uprobes.c (ffffffff81290bec)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812a2d21)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812e689e)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff812f0c86)
Location: include/linux/mmu_notifier.h:514
Inline: True
```
```
In mm/mremap.c (ffffffff812f24ab)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f8b28)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130c51c)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81325c74)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8132fc96)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8134150d)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff813480cd)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff8134d808)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136b9c5)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81420f6c)
Location: include/linux/mmu_notifier.h:514
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
In kernel/events/uprobes.c (ffffffff812e5e71)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812fab6d)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff8133ed66)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff813545b1)
Location: include/linux/mmu_notifier.h:514
Inline: True
```
```
In mm/mremap.c (ffffffff813562a8)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f107)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81375ab4)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff813949e2)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a0062)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b8461)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff813be3c1)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff813c6a6e)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9b53)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81498e02)
Location: include/linux/mmu_notifier.h:514
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
In kernel/events/uprobes.c (ffffffff8134fab4)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81362ca4)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff813b604b)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff813ceacb)
Location: include/linux/mmu_notifier.h:514
Inline: True
```
```
In mm/mremap.c (ffffffff813d08d6)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813d9fbf)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff813f3051)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8140dd08)
Location: include/linux/mmu_notifier.h:514
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
In mm/ksm.c (ffffffff8141ef3c)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8143a22f)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff81440c21)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff814472d0)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471ba3)
Location: include/linux/mmu_notifier.h:514
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff8152d15b)
Location: include/linux/mmu_notifier.h:514
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
In kernel/events/uprobes.c (ffffffff81380c99)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff813950ea)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff813ea916)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff81403410)
Location: include/linux/mmu_notifier.h:513
Inline: True
```
```
In mm/mremap.c (ffffffff814052fe)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140e6e4)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff81426ab7)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff814410e6)
Location: include/linux/mmu_notifier.h:513
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
In mm/ksm.c (ffffffff81453b78)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146ee9a)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814764cf)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
```
```
In mm/khugepaged.c (ffffffff8147c9ae)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_and_free_pmd
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a64ef)
Location: include/linux/mmu_notifier.h:513
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff81564e94)
Location: include/linux/mmu_notifier.h:513
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
In kernel/events/uprobes.c (ffffffff813aa066)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff813beea9)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81417039)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffff8142f9a0)
Location: include/linux/mmu_notifier.h:512
Inline: True
```
```
In mm/mremap.c (ffffffff814317fd)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143aec9)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814606f7)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8147b218)
Location: include/linux/mmu_notifier.h:512
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
In mm/ksm.c (ffffffff8148e3bb)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149d941)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff814a5d5f)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814acbca)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814d2a20)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d743f)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pre_vma
```
```
In fs/proc/task_mmu.c (ffffffff8159bdcc)
Location: include/linux/mmu_notifier.h:512
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:do_pagemap_scan
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
In kernel/events/uprobes.c (ffff8000102a54d4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffff8000102b82c8)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffff8000102f44f8)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffff800010305498)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305e4c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff800010309c78)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffff80001031de68)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffff800010335830)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffff80001033ebb4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffff800010358460)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffff80001035e3c4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffff800010439358)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (c04d48e8)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (c04e4a68)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (c0516de4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_page_range_single
  - mm/memory.c:zap_page_range
  - mm/memory.c:unmap_vmas
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (c05232b4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0523d84)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c05264b8)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c05374e4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/ksm.c (c0544ebc)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
```
In fs/proc/task_mmu.c (c06002bc)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (c0000000003581f8)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (c000000000370388)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (c0000000003bb04c)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (c0000000003d2944)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3ac0)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0000000003d95ac)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0000000003f1a10)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (c00000000040fb1c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (c00000000041ac00)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000433b24)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (c000000000440d14)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (c000000000447864)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (c00000000054c1a8)
Location: include/linux/mmu_notifier.h:406
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
In mm/oom_kill.c (ffffffe0001dc0b4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffe000206650)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffffffe0002113c4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffe000211a82)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000213c3c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffe000220e5e)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffe000230c5e)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffe0002348e4)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/proc/task_mmu.c (ffffffe0002d3092)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (ffffffff8121270c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8122292b)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81255657)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffffffff81266e50)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267b8f)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126c5de)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127bcec)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128e6cb)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812979d6)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a7cf0)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812b013b)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b5600)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81367527)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (ffffffff8120549c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff81215adb)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81247d57)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffffffff81258f76)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259edc)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8125e64e)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126dbcc)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff81280488)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812895c6)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812996b0)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812a15fb)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812a6680)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff813581c7)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (ffffffff812104ac)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff812206cb)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff812533f7)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffffffff81264bf0)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126592f)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8126a37e)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81279a8c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8128c4db)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812957e6)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a5b00)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812adf4b)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812b3410)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81364ff7)
Location: include/linux/mmu_notifier.h:406
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
In kernel/events/uprobes.c (ffffffff8121f3fc)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/oom_kill.c (ffffffff8122f7c5)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_reap_task_mm
```
```
In mm/memory.c (ffffffff81262e07)
Location: include/linux/mmu_notifier.h:406
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
In mm/mprotect.c (ffffffff8127439a)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812752e2)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81279cee)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128967c)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
```
```
In mm/hugetlb.c (ffffffff8129c2cb)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812a560e)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b51b0)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
```
```
In mm/huge_memory.c (ffffffff812be2b5)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
```
In mm/khugepaged.c (ffffffff812c3878)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff81378034)
Location: include/linux/mmu_notifier.h:406
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_refs_write
```
</details>
</li>
</ul>

## Differences
