# Function: <code>set_pte_bit</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In arch/arm64/kernel/efi.c (ffff8000114360c0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/arm64/kernel/efi.c:set_permissions
  - arch/arm64/kernel/efi.c:set_permissions
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b0138)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:change_page_range
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b16e0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_wrprotect
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_set_access_flags
  - arch/arm64/mm/hugetlbpage.c:arch_make_huge_pte
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
  - arch/arm64/mm/hugetlbpage.c:get_clear_flush
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc4c0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
```
```
In mm/shmem.c (0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
```
```
In mm/gup.c (ffff8000102f1da0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f9ed4)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffff800010305278)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
```
```
In mm/madvise.c (ffff80001031ec4c)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/hugetlb.c (ffff80001033596c)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffff80001033ef2c)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffff800010352f5c)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffff800010355f10)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:huge_pmd_set_accessed
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:touch_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035e694)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffff800010378c48)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
```
```
In fs/dax.c (0)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
```
```
In drivers/xen/xlate_mmu.c (ffff80001083f27c)
Location: arch/arm64/include/asm/pgtable.h:132
Inline: True
Inline callers:
  - drivers/xen/xlate_mmu.c:remap_pfn_fn
  - drivers/xen/xlate_mmu.c:remap_pte_fn
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
In arch/arm/kernel/efi.c (c1506fc8)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - arch/arm/kernel/efi.c:set_permissions
  - arch/arm/kernel/efi.c:set_permissions
```
```
In arch/arm/mm/pageattr.c (c031fc04)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - arch/arm/mm/pageattr.c:change_page_range
```
```
In mm/shmem.c (0)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
```
```
In mm/gup.c (c05144a4)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
```
```
In mm/memory.c (c051be20)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (0)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
```
```
In mm/ksm.c (0)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/arm/include/asm/pgtable.h:275
Inline: True
```
</details>
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
