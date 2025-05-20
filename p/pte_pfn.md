# Function: <code>pte_pfn</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101ca6e)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff81f6230f)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/xen/p2m.c (ffffffff81024688)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
```
```
In arch/x86/mm/init_64.c (ffffffff8181c50c)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a86b)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d396)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/gup.c (ffffffff8107155d)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811ba642)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bc3de)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:follow_phys
```
```
In mm/rmap.c (ffffffff811ca9fe)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811cc65b)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff811dd8d7)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_huge_pud
```
```
In mm/mempolicy.c (ffffffff811dfe4d)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8181f1c6)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
```
```
In mm/huge_memory.c (ffffffff811f4a9d)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In fs/proc/task_mmu.c (ffffffff81276aa1)
Location: arch/x86/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/xen/enlighten.c (ffffffff8101bcd9)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff81f8abf2)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81024677)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/mm/init_64.c (ffffffff81069bd5)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a5ee)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106da20)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/gup.c (ffffffff810717ba)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811d596c)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811dd891)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_normal_page
```
```
In mm/rmap.c (ffffffff811e78f8)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811e96c5)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff811fdfbb)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff811fec1a)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8189986a)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
```
```
In mm/khugepaged.c (ffffffff8121bebe)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/task_mmu.c (ffffffff812a47e1)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/xen/enlighten.c (ffffffff8101c4e9)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff81fc5fe0)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81024da7)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/mm/init_64.c (ffffffff8106d798)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106e18e)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810716ac)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/gup.c (ffffffff8107534a)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/gup.c (ffffffff811e596c)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811ed3c3)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_normal_page
```
```
In mm/page_vma_mapped.c (ffffffff811f6bfe)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f8c87)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811faa15)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff8120ea9b)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121045b)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff818cdf1c)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
```
```
In mm/khugepaged.c (ffffffff8122e7dd)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/dax.c (ffffffff8129bab4)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba161)
Location: arch/x86/include/asm/pgtable.h:156
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/x86/xen/p2m.c (ffffffff8101df87)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f3a8)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6e7f)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8106cdec)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff8106d6d0)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070ea8)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In mm/gup.c (ffffffff811f0a99)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f83d6)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/page_vma_mapped.c (ffffffff81201a96)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81204267)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81205816)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff8121a46b)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8121a98b)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff819053b1)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
```
```
In mm/khugepaged.c (ffffffff81239f25)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/dax.c (ffffffff812aa419)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c78b1)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101ec8e)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fe4c)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102564d)
Location: arch/x86/include/asm/pgtable.h:188
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81071a6a)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff81072796)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810765f1)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5e04)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81205627)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81210590)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:_vm_normal_page
```
```
In mm/page_vma_mapped.c (ffffffff8121a511)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121d00c)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8121f83a)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff812355cb)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81235be4)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8198f3c8)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
```
```
In mm/migrate.c (ffffffff8124b409)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812596dd)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/hmm.c (ffffffff8126e904)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812cdc45)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb4d0)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff8102564d-ffffffff81025672: pte_pfn (STB_LOCAL)
ffffffff81070210-ffffffff81070235: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101f72e)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810206cd)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102638e)
Location: arch/x86/include/asm/pgtable.h:192
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff81074747)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81078f66)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efbaf)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81226b23)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81230f84)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:_vm_normal_page
```
```
In mm/mprotect.c (ffffffff812397da)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff8123c3af)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123eeda)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81240fac)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff812584fa)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8125a643)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff819ebc1a)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/migrate.c (ffffffff8126e0c7)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8127cfda)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff8129358a)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812f87b2)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff813187e3)
Location: arch/x86/include/asm/pgtable.h:192
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff8102638e-ffffffff810263c3: pte_pfn (STB_LOCAL)
ffffffff81073120-ffffffff8107314c: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8101efe6)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102013d)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f3e)
Location: arch/x86/include/asm/pgtable.h:194
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107a637)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f876)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a686c)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81239c24)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81244750)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:_vm_normal_page
```
```
In mm/mprotect.c (ffffffff8124d11a)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff812507cf)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812534b5)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81254cbc)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff8126cbca)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8126e4c3)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a26e88)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/migrate.c (ffffffff81282f37)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff81291b4f)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/hmm.c (ffffffff812a7bcd)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8130c4b5)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132fa43)
Location: arch/x86/include/asm/pgtable.h:194
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff81025f3e-ffffffff81025f73: pte_pfn (STB_LOCAL)
ffffffff810791c0-ffffffff810791ec: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81020b46)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81021c7f)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027c3e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107e386)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff8108326e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bef1e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8120ced9)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8124ae58)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81256711)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff8126024a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff81262ad7)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126572e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126706c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff81287ffa)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81289afc)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a9772e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8128f7d1)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/khugepaged.c (ffffffff812abe09)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812c3d99)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813339f4)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813578a3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff81027c3e-ffffffff81027c73: pte_pfn (STB_LOCAL)
ffffffff8107cdd0-ffffffff8107cdfc: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810214a6)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810225bf)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028573)
Location: arch/x86/include/asm/pgtable.h:211
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107f416)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff8108433e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5397)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121a1c5)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81259348)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81264ca1)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff8126dc4a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff81271287)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81274043)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8127596c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff81297bfa)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8129966c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81aceff5)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8129f559)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812aec09)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812bd619)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812d5aed)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813475ba)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136fad3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff81028573-ffffffff810285a8: pte_pfn (STB_LOCAL)
ffffffff8107de60-ffffffff8107de8c: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023c76)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81024acf)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a4ca)
Location: arch/x86/include/asm/pgtable.h:213
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/mm/init_64.c (ffffffff81085dab)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e17f)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce85a8)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81246b3e)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81288078)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129506f)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff8129e29a)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff812a1993)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812a52c3)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812a7375)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff812cb2a1)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812ce96f)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81bc79b6)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812d3ba7)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e421a)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812f2d34)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/hmm.c (ffffffff8130b731)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8138d9be)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b6f73)
Location: arch/x86/include/asm/pgtable.h:213
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
**Symbols:**

```
ffffffff8102a4ca-ffffffff8102a502: pte_pfn (STB_LOCAL)
ffffffff81086297-ffffffff810862cf: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81024246)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102524f)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2c26)
Location: arch/x86/include/asm/pgtable.h:212
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd
```
```
In arch/x86/kernel/sev-es.c (ffffffff81083712)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81086e40)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
  - arch/x86/mm/init_64.c:remove_pte_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e04f)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd5fc6)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812511a1)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81291d5f)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129fedf)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff812a97da)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff812ad251)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b0787)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b25f5)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff812d6eb1)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812da2af)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81c406ec)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812df5a7)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812efcba)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812fd36b)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/hmm.c (ffffffff8131761d)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8139f43e)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c8613)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ac9ed)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff81bd2c26-ffffffff81bd2c5e: pte_pfn (STB_LOCAL)
ffffffff81bd8bdb-ffffffff81bd8c13: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81026466)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff810273cf)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4df2)
Location: arch/x86/include/asm/pgtable.h:212
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/sev.c (ffffffff81083c7e)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81087af6)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ec11)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0a34)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812552a1)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8129787f)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a574c)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_reuse
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffff812aec1a)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff812b2393)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b5db1)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b8d36)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff812de0d1)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812e1b0f)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81c3275b)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812e7ee3)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f563a)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813040d7)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8131d31e)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813a61ab)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cf653)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188fb28)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff81bc4df2-ffffffff81bc4e24: pte_pfn (STB_LOCAL)
ffffffff81bcaa91-ffffffff81bcaac3: pte_pfn (STB_LOCAL)
ffffffff812974d0-ffffffff812974f9: pte_pfn (STB_LOCAL)
ffffffff8129cda0-ffffffff8129cdc9: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102a976)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102b9ef)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c975ce)
Location: arch/x86/include/asm/pgtable.h:183
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/sev.c (ffffffff81092e2c)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81096e78)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e6c7)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4113)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81290ce3)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff812d825a)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e6c3c)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffff812f045a)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff812f3ff7)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f8c0b)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812fb2ea)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff813252e6)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81328bea)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8132c4dc)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8132fdf4)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133fc3b)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8134de07)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff8135eb4c)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a6b9)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813f5c1b)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420a33)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923683)
Location: arch/x86/include/asm/pgtable.h:183
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
**Symbols:**

```
ffffffff81c975ce-ffffffff81c97600: pte_pfn (STB_LOCAL)
ffffffff81c9ff79-ffffffff81c9ffab: pte_pfn (STB_LOCAL)
ffffffff812d7e80-ffffffff812d7ea9: pte_pfn (STB_LOCAL)
ffffffff812ddb80-ffffffff812ddba9: pte_pfn (STB_LOCAL)
ffffffff8132bd00-ffffffff8132bd29: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102f3c7)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103028c)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e46a6d)
Location: arch/x86/include/asm/pgtable.h:186
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
```
```
In arch/x86/kernel/sev.c (ffffffff810a5361)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810a9895)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b20af)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b97db)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff812e5fe7)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8133815f)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133d9eb)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffff8135395a)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813580a5)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135f1ef)
Location: arch/x86/include/asm/pgtable.h:186
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
In mm/vmalloc.c (ffffffff813627f2)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff81393c46)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81397e37)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8139c46e)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
Direct callers:
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:__populate_section_memmap
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff813a01c2)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff813b7a1d)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c7068)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff813d8fcd)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff813e8280)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81499922)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79716)
Location: arch/x86/include/asm/pgtable.h:186
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
**Symbols:**

```
ffffffff81e46a6d-ffffffff81e46aa2: pte_pfn (STB_LOCAL)
ffffffff810a7fb0-ffffffff810a7fe1: pte_pfn (STB_LOCAL)
ffffffff81337690-ffffffff813376c1: pte_pfn (STB_LOCAL)
ffffffff8133db20-ffffffff8133db51: pte_pfn (STB_LOCAL)
ffffffff8139ba20-ffffffff8139ba51: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103673a)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103763c)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6fb1c)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/sev.c (ffffffff810bdaf0)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810c2cae)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc905)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d5468)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff8134fc20)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/vmscan.c (ffffffff81387505)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/gup.c (ffffffff813af90a)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b6aeb)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffff813cdcca)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d26dd)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813da0a7)
Location: arch/x86/include/asm/pgtable.h:187
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
In mm/vmalloc.c (ffffffff813de18e)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff81411d9f)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814141f5)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/mempolicy.c (ffffffff81417ac2)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff820cbb09)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8141f0a9)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff81438e80)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144aee1)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memory-failure.c (ffffffff8145efc1)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8147018b)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152db36)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6631)
Location: arch/x86/include/asm/pgtable.h:187
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
**Symbols:**

```
ffffffff813b5100-ffffffff813b5135: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810366aa)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103757c)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836908d6)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/sev.c (ffffffff810c1160)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810c638e)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cff25)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d8992)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff81380de6)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/vmscan.c (ffffffff813aba45)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
```
```
In mm/gup.c (ffffffff813e4083)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813eb4ab)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffff8140261d)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814074d9)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8140e7eb)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff814129e8)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff814453e0)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447755)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/mempolicy.c (ffffffff8144b045)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8214fdbc)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81453d31)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8146f6bf)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147ec18)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memory-failure.c (ffffffff81494f71)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff814a4967)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff81565f66)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6f7)
Location: arch/x86/include/asm/pgtable.h:188
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
**Symbols:**

```
ffffffff813e9ea0-ffffffff813e9ed5: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103c8aa)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8103d8cc)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c03a6)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/sev.c (ffffffff810c85c0)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810ce7de)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d8605)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e1212)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff813aa1ae)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/vmscan.c (ffffffff813d6165)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
```
```
In mm/gup.c (ffffffff8140e8e8)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81415475)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
```
```
In mm/mlock.c (ffffffff8142528a)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142ecbd)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81433b49)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8143aff7)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143f458)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff8147b5a3)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff814811d1)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_pte_entry
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
```
```
In mm/mempolicy.c (ffffffff81484a1d)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff82232bec)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8148e4ac)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8149d48d)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814af900)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memory-failure.c (ffffffff814c4871)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff814d598f)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159df36)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81667bc7)
Location: arch/x86/include/asm/pgtable.h:224
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
**Symbols:**

```
ffffffff81415760-ffffffff81415795: pte_pfn (STB_LOCAL)
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
In arch/powerpc/kernel/mce_power.c (c00000000003a4d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
```
```
In arch/powerpc/kernel/eeh.c (c000000000044438)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
```
```
In arch/powerpc/mm/pgtable.c (c000000000087820)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/pgtable_64.c (c000000000089010)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable_64.c:pmd_page
  - arch/powerpc/mm/pgtable_64.c:pud_page
  - arch/powerpc/mm/pgtable_64.c:pgd_page
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008cf08)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/mm/book3s64/hash_64k.c (c00000000009da40)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_hugepage.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6300)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118e84)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011cb1c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr
```
```
In arch/powerpc/perf/callchain.c (c000000000125010)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_slow
```
```
In mm/gup.c (c0000000003b6e28)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb4ec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d5320)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d9688)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dbbfc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (c0000000004106b8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (c0000000004110ac)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (c000000000eedaec)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/migrate.c (c000000000434870)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (c00000000043e6c4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (c000000000447fa8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (c00000000046fc70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (c000000000512654)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (c00000000054c7dc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:617
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
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
In arch/riscv/mm/cacheflush.c (ffffffe0000ba10c)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - arch/riscv/mm/cacheflush.c:flush_icache_pte
```
```
In mm/gup.c (ffffffe0002048ae)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
```
```
In mm/memory.c (ffffffe000206900)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (0)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffe00021262e)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffe000213cc8)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffe00021523e)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffe000232068)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/sparse-vmemmap.c (ffffffe000048f56)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (0)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
```
```
In mm/hmm.c (ffffffe000252258)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffe0002b2d9a)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffe0002d2e18)
Location: arch/riscv/include/asm/pgtable.h:179
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021606)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102271f)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810286d3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107e416)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff8108333e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b032f)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81212815)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81251998)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d2f1)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff8126629a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff812698d7)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126c693)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126dfbc)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff812901da)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff81291c4c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a6de65)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81297b39)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a71e9)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812b5bf9)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812ce0cd)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133fb9a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813680b3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff810286d3-ffffffff81028708: pte_pfn (STB_LOCAL)
ffffffff8107ce60-ffffffff8107ce8c: pte_pfn (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff8106d541)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81071ff3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8517)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (0)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
```
```
In mm/gup.c (ffffffff8124485a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124f74b)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff812586b9)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff8125bc42)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8125e706)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8125ff86)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff81281e81)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff812838b8)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a3c3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
```
```
In mm/migrate.c (ffffffff81298c01)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812a6de5)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812bef4e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133084a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813589b7)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021466)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102257f)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028533)
Location: arch/x86/include/asm/pgtable.h:211
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff8107e3c6)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff810832ee)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c322e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812105b5)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8124f738)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b091)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff8126403a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff81267677)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126a433)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126bd5c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff8128dfea)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8128fa5c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81ada275)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81295949)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a4ff9)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812b3a09)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812cbedd)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133d66a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365b83)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff81028533-ffffffff81028568: pte_pfn (STB_LOCAL)
ffffffff8107ce10-ffffffff8107ce3c: pte_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int pte_pfn(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810216b6)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8102288f)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810291c3)
Location: arch/x86/include/asm/pgtable.h:211
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/mm/init_64.c (ffffffff810804b6)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81085544)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c63d4)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121f4f8)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8125f0a8)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126aa63)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/mprotect.c (ffffffff812739fa)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
```
In mm/page_vma_mapped.c (ffffffff81277007)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81279d9e)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8127b76c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/hugetlb.c (ffffffff8129dd8a)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (ffffffff8129e2aa)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81ae672b)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812a5761)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b5b53)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812c3e4c)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff812dcc62)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8135057d)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81379213)
Location: arch/x86/include/asm/pgtable.h:211
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
**Symbols:**

```
ffffffff810291c3-ffffffff810291f8: pte_pfn (STB_LOCAL)
ffffffff8107ef00-ffffffff8107ef2c: pte_pfn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
