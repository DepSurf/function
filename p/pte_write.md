# Function: <code>pte_write</code>

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
In arch/x86/mm/fault.c (ffffffff8106a1bf)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
```
```
In mm/memory.c (ffffffff811bf5cb)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:follow_phys
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
```
```
In mm/rmap.c (ffffffff811cb33a)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:120
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/memory.c (ffffffff811dd87a)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/rmap.c (ffffffff811e86bf)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/memory.c (ffffffff811ed3ac)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/rmap.c (ffffffff811f9974)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:131
Inline: True
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
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In mm/memory.c (ffffffff811f5b86)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In mm/rmap.c (ffffffff81204541)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:153
Inline: True
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
In arch/x86/mm/fault.c (ffffffff81071c2f)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault_check
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In mm/memory.c (ffffffff8120d671)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In mm/rmap.c (ffffffff8121d34f)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81234b9d)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In mm/migrate.c (ffffffff8124b6f6)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812597dc)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/hmm.c (ffffffff8126e91b)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
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
In arch/x86/mm/fault.c (ffffffff81074a1f)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault_check
```
```
In mm/gup.c (ffffffff812263e7)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81230f7c)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
```
```
In mm/mprotect.c (ffffffff812391ba)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8123f218)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812580a8)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff812602dc)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126e00f)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8127d04e)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff8129353e)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:163
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107ab5f)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
```
```
In mm/gup.c (ffffffff8123a743)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81244748)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
```
```
In mm/mprotect.c (ffffffff8124d742)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125391e)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8126c787)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff81274a19)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282e7f)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81291bbf)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812a7a9c)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:165
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107e8cf)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/gup.c (ffffffff8124ba5c)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81256709)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8125f74f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81265b4a)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81287b11)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff8128eec4)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/migrate.c (ffffffff8129dedc)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812abe76)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812c3d2a)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107f95f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/gup.c (ffffffff81259f4c)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81264c99)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126df5f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff81274469)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81297720)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff8129ec40)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/migrate.c (ffffffff812aec55)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812bd686)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812d5a84)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
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
In arch/x86/mm/fault.c (ffffffff81086aff)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
```
```
In mm/gup.c (ffffffff8128845a)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81295067)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_one_pte
```
```
In mm/mprotect.c (ffffffff8129e7f8)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812a5714)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812cac8f)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff812d37a0)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812e4266)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812f2dac)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8130b6ea)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c785)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff813745a7)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:184
Inline: True
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
In arch/x86/mm/fault.c (ffffffff810873df)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In mm/gup.c (ffffffff8129213a)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129fed7)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a9bae)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b0add)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812d68af)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff812df1c3)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812efd0a)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812fd3e8)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff813175b2)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff813186c5)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff813824f7)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c7f5d)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ac9e1)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
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
In arch/x86/mm/fault.c (ffffffff81087fff)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In mm/gup.c (ffffffff81297da0)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a577b)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812af039)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812b61ca)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812dda62)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff812e699d)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff812f5687)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81304147)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8131d2b3)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e8b5)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff8138957d)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813cef8d)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188fb1c)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
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
In arch/x86/mm/fault.c (ffffffff8109737f)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
```
```
In mm/gup.c (ffffffff812d87e0)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e6c6b)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812f0832)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff812f8cf9)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (ffffffff81324c36)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff8132e8bd)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff8133fc8e)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8134de77)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8136a64e)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bc95)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff813d6877)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8142046d)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923677)
Location: arch/x86/include/asm/pgtable.h:154
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
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
In arch/x86/mm/fault.c (ffffffff810a9a2f)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault_check
```
```
In mm/gup.c (ffffffff81338258)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133da19)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81353ba7)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8135f2dc)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (ffffffff813934f2)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff813a0670)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff813b1c51)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b72e2)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c70ba)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff813e8211)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9e75)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff8145da12)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8149a876)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a796bc)
Location: arch/x86/include/asm/pgtable.h:157
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
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
In arch/x86/mm/fault.c (ffffffff810c2e7f)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault_check
```
```
In mm/gup.c (ffffffff813afa22)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b6b19)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff813ce1eb)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff813da197)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (ffffffff81411c77)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff8141ff27)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff814326fc)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438de6)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144af46)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8147011e)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471f05)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff814ed443)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152ed96)
Location: arch/x86/include/asm/pgtable.h:158
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
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
In arch/x86/mm/fault.c (ffffffff810c657f)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault_check
```
```
In mm/gup.c (ffffffff813e4175)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813eb4d9)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff81402a9f)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8140e8d7)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (ffffffff8144519c)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff81454a65)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81467ebd)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f62d)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147ec79)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff814a48f4)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6848)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff815241d3)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff815670a6)
Location: arch/x86/include/asm/pgtable.h:159
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pte_write(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810ce9ff)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault_check
```
```
In mm/gup.c (ffffffff8140e9fa)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814154aa)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_present_pte
Direct callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff8142f336)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8143b0b5)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
```
```
In mm/hugetlb.c (ffffffff8147b5e7)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff8148fc55)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate.c (ffffffff81497ba7)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149e145)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814af943)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff814d5924)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d76a3)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In fs/userfaultfd.c (ffffffff81558824)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159cc15)
Location: arch/x86/include/asm/pgtable.h:173
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:clear_soft_dirty
```
**Symbols:**

```
ffffffff814141c0-ffffffff81414210: pte_write (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/ioremap.c (c0000000000894f4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - arch/powerpc/mm/ioremap.c:ioremap_prot
```
```
In arch/powerpc/xmon/xmon.c (c00000000010ae7c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:format_pte
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011cabc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In mm/gup.c (c0000000003b7770)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c6a00)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (c0000000003d24b0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d9790)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/hugetlb.c (c00000000040f588)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (c000000000419e8c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
```
```
In mm/migrate.c (c0000000004348a8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000044418c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (c000000000447fc8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (c00000000046fb90)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c00000000050167c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c00000000051268c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:416
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
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
In mm/gup.c (ffffffe00020475a)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
```
```
In mm/memory.c (ffffffe000209964)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mprotect.c (ffffffe000211306)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffe000213f64)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffe000231d2a)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (0)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
```
```
In mm/hmm.c (ffffffe000252200)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffe0002a8808)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (0)
Location: arch/riscv/include/asm/pgtable.h:214
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107e95f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/gup.c (ffffffff8125259c)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d2e9)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff812665af)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126cab9)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128fd00)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff81297220)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/migrate.c (ffffffff812a7235)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812b5c66)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812ce064)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8106dd0f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/gup.c (ffffffff81245338)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124f743)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff81258c83)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff8125eb19)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff812819c5)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff81288e30)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/migrate.c (ffffffff81298c3b)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812a6e2a)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812beeda)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
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
In arch/x86/mm/fault.c (ffffffff8107e90f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/gup.c (ffffffff8125033c)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b089)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff8126434f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8126a859)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8128db10)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff81295030)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/migrate.c (ffffffff812a5045)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812b3a76)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812cbe74)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
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
In arch/x86/mm/fault.c (ffffffff810809ff)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/gup.c (ffffffff8125fcc7)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126aa5b)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mprotect.c (ffffffff81273d0f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/rmap.c (ffffffff8127a1d3)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8129d8c7)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff812a4e94)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In mm/migrate.c (ffffffff812b5b9f)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812c3ebd)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812dcbd2)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:182
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
