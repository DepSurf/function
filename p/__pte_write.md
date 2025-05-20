# Function: <code>__pte_write</code>

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
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - arch/powerpc/mm/ioremap.c:ioremap_prot
```
```
In arch/powerpc/xmon/xmon.c (c00000000010ae7c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:format_pte
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011cabc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In mm/gup.c (c0000000003b7770)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
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
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
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
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (c0000000003d9790)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/hugetlb.c (c00000000040f588)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (c000000000419e8c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
```
```
In mm/migrate.c (c0000000004348a8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000044418c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (c000000000447fc8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (c00000000046fb90)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c00000000050167c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c00000000051268c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:390
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
```
</details>
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
