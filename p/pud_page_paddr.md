# Function: <code>pud_page_paddr</code>

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
In arch/arm64/mm/fault.c (ffff8000100ad4bc)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:show_pte
```
```
In arch/arm64/mm/mmu.c (ffff8000100af4e0)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:pud_free_pmd_page
  - arch/arm64/mm/mmu.c:vmemmap_populate
  - arch/arm64/mm/mmu.c:kern_addr_valid
  - arch/arm64/mm/mmu.c:init_pmd
  - arch/arm64/mm/mmu.c:init_pmd
```
```
In arch/arm64/mm/pageattr.c (ffff8000100b0708)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - arch/arm64/mm/pageattr.c:kernel_page_present
```
```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1098)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:huge_pte_offset
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:huge_pte_alloc
  - arch/arm64/mm/hugetlbpage.c:find_num_contig
```
```
In arch/arm64/mm/dump.c (ffff8000100b1dc0)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
```
```
In virt/kvm/arm/mmu.c (ffff8000100cb284)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:stage2_wp_range
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_get_leaf_entry
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/gup.c (ffff8000102f1080)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffff8000102f44d0)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffff80001030502c)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffff800010305ef0)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffff800010307298)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffff8000103079a4)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
```
```
In mm/rmap.c (ffff8000103092f4)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffff80001030bd1c)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffff800010326750)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffff8000103335d4)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/sparse-vmemmap.c (ffff800010da0e38)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffff80001035910c)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (0)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
```
```
In mm/userfaultfd.c (ffff800010377da0)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffff8000103f9410)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In lib/ioremap.c (ffff800010d89660)
Location: arch/arm64/include/asm/pgtable.h:552
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
```
</details>
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
