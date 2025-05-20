# Function: <code>flush_tlb_mm_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int vmflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810728e0)
Location: arch/x86/mm/tlb.c:186
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - arch/x86/mm/pgtable.c:pmdp_splitting_flush
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff810728e0-ffffffff81072a33: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int vmflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810728b0)
Location: arch/x86/mm/tlb.c:306
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff810728b0-ffffffff810729f6: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int vmflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076460)
Location: arch/x86/mm/tlb.c:321
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:move_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81076460-ffffffff810765a7: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int vmflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074b80)
Location: arch/x86/mm/tlb.c:242
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81074b80-ffffffff81074c6d: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int vmflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107acf0)
Location: arch/x86/mm/tlb.c:605
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/memory.c:zap_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8107acf0-ffffffff8107adf8: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, long unsigned int vmflag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107daa0)
Location: arch/x86/mm/tlb.c:618
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:copy_mm
  - kernel/fork.c:copy_mm
  - mm/memory.c:zap_page_range
  - mm/mprotect.c:change_protection
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8107daa0-ffffffff8107dbb6: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81084610)
Location: arch/x86/mm/tlb.c:728
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81084610-ffffffff8108472e: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810882e0)
Location: arch/x86/mm/tlb.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff810882e0-ffffffff810883bf: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088f90)
Location: arch/x86/mm/tlb.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81088f90-ffffffff8108906f: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b690)
Location: arch/x86/mm/tlb.c:949
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:unmap_ldt_struct
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_normal_pmd
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
```
**Symbols:**

```
ffffffff8108b690-ffffffff8108b777: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b6e0)
Location: arch/x86/mm/tlb.c:885
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8108b6e0-ffffffff8108b7c7: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c2c0)
Location: arch/x86/mm/tlb.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff8108c2c0-ffffffff8108c3b4: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:984
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81ca11f5-ffffffff81ca1219: flush_tlb_mm_range.cold (STB_LOCAL)
ffffffff8109bae0-ffffffff8109bc00: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:958
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff81e50801-ffffffff81e50825: flush_tlb_mm_range.cold (STB_LOCAL)
ffffffff810aef50-ffffffff810af0a4: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:981
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff82054c86-ffffffff82054caa: flush_tlb_mm_range.cold (STB_LOCAL)
ffffffff810c92f0-ffffffff810c9462: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff820d325e-ffffffff820d327f: flush_tlb_mm_range.cold (STB_LOCAL)
ffffffff810cc980-ffffffff810ccaf9: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:1001
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:do_wp_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - mm/mapping_dirty_helpers.c:wp_clean_post_vma
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:pagemap_scan_pmd_entry
  - fs/proc/task_mmu.c:clear_refs_write
```
**Symbols:**

```
ffffffff821ae0cc-ffffffff821ae0ed: flush_tlb_mm_range.cold (STB_LOCAL)
ffffffff810d5010-ffffffff810d51bd: flush_tlb_mm_range (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087f50)
Location: arch/x86/mm/tlb.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81087f50-ffffffff8108802f: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076bb0)
Location: arch/x86/mm/tlb.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81076bb0-ffffffff81076c83: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087f00)
Location: arch/x86/mm/tlb.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff81087f00-ffffffff81087fdf: flush_tlb_mm_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a150)
Location: arch/x86/mm/tlb.c:767
Inline: False
Direct callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
  - kernel/fork.c:dup_mmap
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/pgtable-generic.c:pmdp_collapse_flush
  - mm/pgtable-generic.c:pmdp_invalidate
  - mm/pgtable-generic.c:pudp_huge_clear_flush
  - mm/pgtable-generic.c:pmdp_huge_clear_flush
  - mm/pgtable-generic.c:ptep_clear_flush
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:flush_tlb_batched_pending
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
**Symbols:**

```
ffffffff8108a150-ffffffff8108a24f: flush_tlb_mm_range (STB_GLOBAL)
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
<code>unsigned int stride_shift</code>
</li>
<li>
<b>Param added. </b>
<code>bool freed_tables</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int vmflag</code>
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
