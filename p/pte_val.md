# Function: <code>pte_val</code>

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
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff81f6230f)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_set_pte_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/xen/p2m.c (ffffffff81024688)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:get_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
```
```
In arch/x86/xen/trace.c (ffffffff81026c80)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
```
```
In arch/x86/mm/init_64.c (ffffffff8181bab7)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:phys_pte_init
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
```
```
In arch/x86/mm/fault.c (ffffffff8106a86b)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d396)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
```
In arch/x86/mm/gup.c (ffffffff8107155d)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/kmmio.c (ffffffff81073037)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81074269)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In mm/gup.c (ffffffff811ba4d2)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff811bbf64)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:follow_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:follow_phys
```
```
In mm/mincore.c (ffffffff811c28f5)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c888d)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811ca9fe)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811cc65b)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff811d1631)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d649c)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff811db0e6)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_huge_pud
```
```
In mm/mempolicy.c (ffffffff811dfe4d)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8181f1c6)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
```
```
In mm/migrate.c (ffffffff811f0ca6)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:__migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff811f4a9d)
Location: arch/x86/include/asm/paravirt.h:418
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
In mm/memcontrol.c (ffffffff811fa965)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff81276aa1)
Location: arch/x86/include/asm/paravirt.h:418
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff81f8abf2)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81024677)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/trace.c (ffffffff81028250)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff81069bd5)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a89b)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e215)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/gup.c (ffffffff8107184e)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/kmmio.c (ffffffff810745fd)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81075847)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In mm/gup.c (ffffffff811d596c)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811dd891)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff811de4aa)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4c35)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811e78f8)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811e96c5)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff811eebed)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f456e)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff811fdfbb)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff811fec1a)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8189986a)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
```
```
In mm/migrate.c (ffffffff812117e9)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8121bef5)
Location: arch/x86/include/asm/paravirt.h:391
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
In mm/memcontrol.c (ffffffff8121e891)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/proc/task_mmu.c (ffffffff812a47e1)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760961)
Location: arch/x86/include/asm/paravirt.h:391
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_load_gdt
  - arch/x86/xen/enlighten.c:set_aliased_prot
```
```
In arch/x86/xen/mmu.c (ffffffff81fc5fe0)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/xen/p2m.c (ffffffff81024da7)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:__set_phys_to_machine
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:xen_alloc_p2m_entry
  - arch/x86/xen/p2m.c:get_phys_to_machine
```
```
In arch/x86/xen/trace.c (ffffffff810289a0)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8106d798)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106e43b)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81071e97)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/gup.c (ffffffff810753de)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In arch/x86/mm/kmmio.c (ffffffff8107817d)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810793c7)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In mm/gup.c (ffffffff811e596c)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811ed3c3)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff811ee2c1)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f4b77)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff811f6bb2)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff811f8c87)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:__page_check_address
```
```
In mm/vmalloc.c (ffffffff811faa15)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff811ff51e)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81205097)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff8120ea9b)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8121045b)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff818cdf1c)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
```
```
In mm/migrate.c (ffffffff812239a9)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8122e972)
Location: arch/x86/include/asm/paravirt.h:382
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
In mm/memcontrol.c (ffffffff81230eb2)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff8129bab4)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812ba161)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178dad6)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
Location: arch/x86/include/asm/paravirt.h:390
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
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6e7f)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/xen/trace.c (ffffffff81026dd3)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8106cdec)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff8106dbb7)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107155f)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:slow_virt_to_phys
```
```
In arch/x86/mm/kmmio.c (ffffffff810769ee)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81077c98)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In mm/gup.c (ffffffff811f0c8c)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f83d6)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff811f9287)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ffbaa)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81201b1b)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81204267)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81205816)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8120a1d5)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81210908)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
```
```
In mm/hugetlb.c (ffffffff8121a46b)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8121a98b)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff819053b1)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
```
```
In mm/migrate.c (ffffffff8122f31a)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81239f25)
Location: arch/x86/include/asm/paravirt.h:390
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
In mm/memcontrol.c (ffffffff8123c719)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In fs/dax.c (ffffffff812aa92a)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c78b1)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abc84)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/p2m.c (ffffffff8101ec8e)
Location: arch/x86/include/asm/paravirt.h:376
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
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025651)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff81027323)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff81071a6a)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff81072b8d)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81076ccc)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush_range
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cd9f)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8107dff8)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5e04)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff812056da)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81210590)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:_vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8121167f)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81218166)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff8121a585)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8121d00c)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8121f83a)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8122341e)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812260a0)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/swap_state.c:do_swap_page_readahead
  - mm/swap_state.c:swap_readahead_detect
```
```
In mm/swapfile.c (ffffffff81227e06)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
```
```
In mm/hugetlb.c (ffffffff812355cb)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81235be4)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8198f3c8)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
```
```
In mm/migrate.c (ffffffff8124b409)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812596dd)
Location: arch/x86/include/asm/paravirt.h:376
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
In mm/memcontrol.c (ffffffff8125c3a3)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff8126e904)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812ce1e0)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb4d0)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823244)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/p2m.c (ffffffff8101f72e)
Location: arch/x86/include/asm/paravirt.h:376
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
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102638e)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff81027df3)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff81074747)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8107560f)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810797c3)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush_range
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd56)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810810d7)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efbaf)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81226ac5)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
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
In mm/memory.c (ffffffff81230f84)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:_vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81232416)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812397da)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8123c34c)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8123eeda)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81240fac)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8124629c)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81248471)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8124d105)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
```
```
In mm/hugetlb.c (ffffffff812584fa)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8125a643)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff819ebc1a)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/migrate.c (ffffffff8126e0c7)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8127cfda)
Location: arch/x86/include/asm/paravirt.h:376
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
In mm/memcontrol.c (ffffffff8127fc05)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff8129368e)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff812f87b2)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff813187e3)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d504)
Location: arch/x86/include/asm/paravirt.h:376
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/p2m.c (ffffffff8101efe6)
Location: arch/x86/include/asm/paravirt.h:386
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
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f3e)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff810283d3)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8107a637)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8107b40f)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107f876)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff81086896)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81087ce7)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a686c)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81239bc6)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81244750)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:_vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81245be9)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d11a)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffff81250f67)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812534b5)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff81254cbc)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a6bc)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8125ca41)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81261505)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
```
```
In mm/hugetlb.c (ffffffff8126cbca)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8126e4c3)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a26e88)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/migrate.c (ffffffff81282f37)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff81291b4f)
Location: arch/x86/include/asm/paravirt.h:386
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
In mm/memcontrol.c (ffffffff81294575)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812a7c34)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/dax.c (ffffffff8130c4b5)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132fa43)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8188f4d9)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/p2m.c (ffffffff81020b46)
Location: arch/x86/include/asm/paravirt.h:386
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
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027c3e)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102a054)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8107e386)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff8107ef3c)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81084b02)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a4a6)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b8c5)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bef1e)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8120ced9)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8124adf6)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81256711)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff81257d4b)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126024a)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81263206)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126572e)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126706c)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127579c)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81277c36)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8127c475)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81287ffa)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81289afc)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a9772e)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8128f7d1)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8129f3dd)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812abe09)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b0928)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812c3d99)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813339f4)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813578a3)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818d94d9)
Location: arch/x86/include/asm/paravirt.h:386
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/p2m.c (ffffffff810214a6)
Location: arch/x86/include/asm/paravirt.h:374
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
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028573)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102a954)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8107f416)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff8107ffcc)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81085802)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b116)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108c535)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5397)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121a1c5)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff812592e6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81264ca1)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8126625b)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126dc4a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812719b6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81274043)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8127596c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128476c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81287726)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff8128bf55)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81297bfa)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8129966c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81aceff5)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8129f559)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812ae904)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812bd619)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c2388)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812d5aed)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff813475ba)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136fad3)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8190b4d9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81023c76)
Location: arch/x86/include/asm/paravirt.h:388
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
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a4ca)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102c764)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff81085dab)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pte_table
```
```
In arch/x86/mm/fault.c (ffffffff8108705d)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f5ca)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff81092578)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093850)
Location: arch/x86/include/asm/paravirt.h:388
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:print_pte
  - arch/x86/mm/mmio-mod.c:print_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce85a8)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81246b3e)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81287ff0)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
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
In mm/memory.c (ffffffff8129506f)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_one_pte
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:print_bad_pte
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812965b4)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e29a)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812a191e)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff812a52c3)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812a7375)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812b6915)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812b988a)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
  - mm/swap_state.c:swap_ra_info
```
```
In mm/swapfile.c (ffffffff812bee55)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812cb2a1)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812ce96f)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81bc79b6)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812d3ba7)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e4013)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812f2d34)
Location: arch/x86/include/asm/paravirt.h:388
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
In mm/memcontrol.c (ffffffff812f5d52)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
```
```
In mm/hmm.c (ffffffff8130b731)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff8130cbe2)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/dax.c (ffffffff8138d9be)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b6f73)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc4d1)
Location: arch/x86/include/asm/paravirt.h:388
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81085e29-ffffffff81085e36: pte_val (STB_LOCAL)
ffffffff81093850-ffffffff8109385d: pte_val (STB_LOCAL)
ffffffff8128b8c0-ffffffff8128b8cd: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81024246)
Location: arch/x86/include/asm/paravirt.h:377
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
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2c26)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102d714)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/sev-es.c (ffffffff810836fe)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81086e40)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pte_table
```
```
In arch/x86/mm/fault.c (ffffffff810876dd)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f38a)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff81091c18)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81092da0)
Location: arch/x86/include/asm/paravirt.h:377
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:print_pte
  - arch/x86/mm/mmio-mod.c:print_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd5fc6)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812511a1)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81291cd0)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
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
In mm/memory.c (ffffffff8129fedf)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_shared
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812a1527)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a97da)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812ad1db)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff812b0787)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b25f5)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c2b65)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812c52f3)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812caa75)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812d6eb1)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812da2af)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81c406ec)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812df5a7)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812efcba)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812fd36b)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff81301822)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
```
```
In mm/hmm.c (ffffffff8131761d)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff81318b22)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/dax.c (ffffffff8139f43e)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c8613)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ac9ed)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
```
In arch/x86/power/hibernate.c (ffffffff81bd14b1)
Location: arch/x86/include/asm/paravirt.h:377
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bd87db-ffffffff81bd87e8: pte_val (STB_LOCAL)
ffffffff81092da0-ffffffff81092dad: pte_val (STB_LOCAL)
ffffffff81296890-ffffffff8129689d: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81026466)
Location: arch/x86/include/asm/paravirt.h:396
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
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4df2)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102e2ac)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/sev.c (ffffffff81083c6a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81087af6)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff8108831f)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ff1a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff81092505)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff81093870)
Location: arch/x86/include/asm/paravirt.h:396
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0a34)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812552a1)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff812977f0)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812a574c)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:wp_page_reuse
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812a6d1a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aec1a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812b2c8d)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812b5db1)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff812b8d36)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812c99e1)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff812cbfa1)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff812d1555)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812de0d1)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff812e1b0f)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81c3275b)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812e7ee3)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f563a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff813040d7)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff81308012)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
```
```
In mm/hmm.c (ffffffff8131d31e)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff8131ed12)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/dax.c (ffffffff813a61ab)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813cf653)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188fb28)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
```
In arch/x86/power/hibernate.c (ffffffff81bc34bb)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81bca682-ffffffff81bca68f: pte_val (STB_LOCAL)
ffffffff81093870-ffffffff8109387d: pte_val (STB_LOCAL)
ffffffff8129c230-ffffffff8129c23d: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102a976)
Location: arch/x86/include/asm/paravirt.h:396
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
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c975ce)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff81032c4c)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/sev.c (ffffffff81092e15)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff81096e78)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff810976a8)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109fa04)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810a22f5)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810a3640)
Location: arch/x86/include/asm/paravirt.h:396
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4113)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81290ce3)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff812d81b0)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812e6c3c)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff812e81fa)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f045a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff812f484e)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff812f8c0b)
Location: arch/x86/include/asm/paravirt.h:396
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
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8130ea01)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81311171)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81316c55)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff813252e6)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81328bea)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8132c4dc)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/ksm.c (ffffffff8132fdf4)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff8133be1e)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_unprotect
  - mm/kfence/core.c:kfence_protect
```
```
In mm/migrate.c (ffffffff8133fc3b)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff8134de07)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813521a2)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
```
```
In mm/memory-failure.c (ffffffff8135ebb2)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/hmm.c (ffffffff8136a6b9)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff8136c0f2)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/dax.c (ffffffff813f5c1b)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81420a33)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923683)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn
```
```
In arch/x86/power/hibernate.c (ffffffff81c944cb)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81c9fb28-ffffffff81c9fb35: pte_val (STB_LOCAL)
ffffffff810a3640-ffffffff810a364d: pte_val (STB_LOCAL)
ffffffff812dcd30-ffffffff812dcd3d: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8102f3c7)
Location: arch/x86/include/asm/paravirt.h:402
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
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e46a6d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8103957e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/sev.c (ffffffff810a534b)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810a9895)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff810aa1c7)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b3834)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6895)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810b7ca0)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b97db)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff812e5fe7)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff813380aa)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8133d9eb)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8134956a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8135395a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813586ad)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8135f1ef)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813627f2)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81376bbd)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8137c1af)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81382275)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81393c46)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81397e37)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8139c46e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_restore_pte
  - mm/sparse-vmemmap.c:vmemmap_remap_pte
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
```
```
In mm/ksm.c (ffffffff813a01c2)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff813aea6a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/migrate.c (ffffffff813b4ba5)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7a1d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c7068)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff813ce86d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff813d9054)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff813e44a3)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff813e8280)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff813ea371)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff8145da7a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81499922)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a79716)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns
```
```
In arch/x86/power/hibernate.c (ffffffff81e434fc)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810a7c30-ffffffff810a7c42: pte_val (STB_LOCAL)
ffffffff810b7ca0-ffffffff810b7cb2: pte_val (STB_LOCAL)
ffffffff8133c990-ffffffff8133c9a2: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff8103673a)
Location: arch/x86/include/asm/paravirt.h:402
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
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6fb1c)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/xen/trace.c (ffffffff8104182e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/sev.c (ffffffff810bdada)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810c2cae)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff810c3a75)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce434)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1ad5)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d32d0)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d5468)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff8134fc20)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/vmscan.c (ffffffff81387505)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_look_around
  - mm/vmscan.c:lru_gen_look_around
```
```
In mm/gup.c (ffffffff813af84d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
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
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_set_pte
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
```
```
In mm/mincore.c (ffffffff813c1954)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff813cdcca)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff813d2e25)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff813da0a7)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff813de18e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff813f4387)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff813f994f)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81400aa5)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/swapfile.c:arch_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff814127ef)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/hugetlb_vmemmap.c (ffffffff814141f5)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/mempolicy.c (ffffffff81417ac2)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff820cbb09)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8141f0a9)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/kfence/core.c (ffffffff8142ef9e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_protect_page
  - mm/kfence/core.c:kfence_protect_page
```
```
In mm/migrate.c (ffffffff81433d35)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/migrate.c:__migration_entry_wait_huge
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81438e80)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144aee1)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff8145344e)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff8145f049)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff8146bf74)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff8147018b)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In mm/ptdump.c (ffffffff81472461)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff814ed4a7)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8152db36)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6631)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
```
In arch/x86/power/hibernate.c (ffffffff8201e5a3)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810d32d0-ffffffff810d32e8: pte_val (STB_LOCAL)
ffffffff813b46d0-ffffffff813b46e8: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff810366aa)
Location: arch/x86/include/asm/paravirt.h:397
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
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff836908d6)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/xen/trace.c (ffffffff8104196e)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/sev.c (ffffffff810c114a)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810c638e)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff810c72bf)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d19f4)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810d4f85)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810d66b0)
Location: arch/x86/include/asm/paravirt.h:397
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d8992)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff81380de6)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/vmscan.c (ffffffff813aba45)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
```
```
In mm/gup.c (ffffffff813e3fcb)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
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
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff813f67ed)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (ffffffff8140261d)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff814073c7)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8140e7eb)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff814129e8)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81427a74)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8142c7e6)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff81433954)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81445dfd)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447755)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/mempolicy.c (ffffffff8144b045)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff8214fdbc)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81453d31)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/kfence/core.c (ffffffff814647d3)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
```
```
In mm/migrate.c (ffffffff81469707)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146f6bf)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147ec18)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff81489187)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff81494ff9)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814a0ccf)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In mm/hmm.c (ffffffff814a4967)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/ptdump.c (ffffffff814a6bc1)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff815241ae)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81565f66)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff8162e6f7)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
```
In arch/x86/power/hibernate.c (ffffffff8209e59d)
Location: arch/x86/include/asm/paravirt.h:397
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810d66b0-ffffffff810d66c8: pte_val (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pteval_t pte_val(pte_t pte);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/xen/p2m.c (ffffffff8103c8aa)
Location: arch/x86/include/asm/paravirt.h:398
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
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c03a6)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/xen/trace.c (ffffffff81047e3e)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/kernel/ldt.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/kernel/paravirt.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810c85aa)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff810ce7de)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_set_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff810cf78f)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810da124)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:kernel_page_present
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:slow_virt_to_phys
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd725)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810deee0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e1212)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn
```
```
In kernel/events/uprobes.c (ffffffff813aa1ae)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/vmscan.c (ffffffff813d6165)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In mm/gup.c (ffffffff8140e82b)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
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
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_swap_page
  - mm/memory.c:handle_pte_marker
  - mm/memory.c:vm_normal_page
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_numa_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_nonpresent_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8142249d)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mlock.c (ffffffff8142528a)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142ecbd)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81433a37)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:map_pte
```
```
In mm/rmap.c (ffffffff8143aff7)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (ffffffff8143f458)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81461287)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff81465f2e)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146cd44)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/swapfile.c:generic_max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147f835)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/hugetlb_vmemmap.c (ffffffff814811d1)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_restore_pte
  - mm/hugetlb_vmemmap.c:vmemmap_remap_pte
  - mm/hugetlb_vmemmap.c:vmemmap_pte_entry
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
```
```
In mm/mempolicy.c (ffffffff81484a1d)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff82232bec)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_populate_compound_pages
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff8148e4ac)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:break_ksm_pmd_entry
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/kfence/core.c (ffffffff814938fe)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In mm/migrate.c (ffffffff81498637)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:migration_entry_wait
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d48d)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In mm/khugepaged.c (ffffffff814af900)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/memcontrol.c (ffffffff814b9040)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffffffff814c48f9)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:check_hwpoisoned_entry
```
```
In mm/userfaultfd.c (ffffffff814d2ee9)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_install_pte
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814d598f)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/ptdump.c (ffffffff814d7bc1)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
  - mm/ptdump.c:ptdump_pte_entry
```
```
In fs/userfaultfd.c (ffffffff815586fb)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8159df36)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81667bc7)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
```
```
In drivers/xen/xlate_mmu.c (0)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8217659d)
Location: arch/x86/include/asm/paravirt.h:398
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810deee0-ffffffff810deef8: pte_val (STB_LOCAL)
ffffffff81414030-ffffffff81414048: pte_val (STB_LOCAL)
ffffffff814cfad0-ffffffff814cfae8: pte_val (STB_LOCAL)
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
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce_power.c:addr_to_pfn
```
```
In arch/powerpc/kernel/eeh.c (c000000000044438)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
```
```
In arch/powerpc/mm/pgtable.c (c000000000087820)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:maybe_pte_to_page
```
```
In arch/powerpc/mm/pgtable_64.c (0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
```
```
In arch/powerpc/mm/ioremap.c (c000000000089514)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/ioremap.c:ioremap_prot
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008dde8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
  - arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm
  - arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache
```
```
In arch/powerpc/mm/book3s64/hash_tlb.c (c000000000091ef4)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range
  - arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000095770)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_set_access_flags
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_set_access_flags
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
```
```
In arch/powerpc/mm/book3s64/hash_64k.c (c00000000009de8c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_64K
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e43c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:__hash_page_huge
```
```
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (c00000000009f054)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit
```
```
In arch/powerpc/mm/book3s64/hash_hugepage.c (0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a6300)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:follow_huge_pd
```
```
In arch/powerpc/xmon/xmon.c (c00000000010d51c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:show_pte
```
```
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118e84)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011ca74)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr
```
```
In arch/powerpc/perf/callchain.c (c000000000125010)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - arch/powerpc/perf/callchain.c:read_user_stack_slow
```
```
In mm/shmem.c (c000000000391bd8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (c0000000003b6e28)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c695c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_page
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (c0000000003c86fc)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_hugetlb
  - mm/mincore.c:mincore_hugetlb
```
```
In mm/mprotect.c (c0000000003d2670)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d3880)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
```
```
In mm/page_vma_mapped.c (c0000000003d5850)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (c0000000003d9688)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/vmalloc.c (c0000000003dbbfc)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_page_range_noflush
  - mm/vmalloc.c:vmap_page_range_noflush
```
```
In mm/madvise.c (c0000000003f3118)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/madvise.c:swapin_walk_pmd_entry
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c0000000003f7c84)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (c0000000003fc4c0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (c0000000004106b8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:is_hugetlb_entry_migration
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (c0000000004110ac)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (c000000000eedbb8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/migrate.c (c000000000434830)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c0000000004443a0)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (c00000000044a340)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_swapin
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (c000000000450e4c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/userfaultfd.c (c00000000046b9d8)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c00000000046fb2c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c00000000050166c)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c000000000512654)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (c00000000054c7dc)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (c000000000eca278)
Location: arch/powerpc/include/asm/pgtable-be-types.h:11
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
  - lib/ioremap.c:ioremap_pud_range
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021606)
Location: arch/x86/include/asm/paravirt.h:374
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
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810286d3)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102aab4)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8107e416)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff8107efcc)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81084802)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0d6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b4f5)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b032f)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff81212815)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff81251936)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d2f1)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8125e8ab)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126629a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff8126a006)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126c693)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126dfbc)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127cdbc)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127fcf0)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81284535)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff812901da)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff81291c4c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81a6de65)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81297b39)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a6ee4)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812b5bf9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812ba968)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812ce0cd)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133fb9a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813680b3)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818ab4d9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/p2m.c (ffffffff81021466)
Location: arch/x86/include/asm/paravirt.h:374
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
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028533)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102a914)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff8107e3c6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff8107ef7c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810847b2)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a086)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108b4a5)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c322e)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff812105b5)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8124f6d6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125b091)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8125c64b)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126403a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81267da6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff8126a433)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8126bd5c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127ab5c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8127db16)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81282345)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8128dfea)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8128fa5c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81ada275)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff81295949)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a4cf4)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812b3a09)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812b8778)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812cbedd)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8133d66a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365b83)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818fc4d9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/p2m.c (ffffffff810216b6)
Location: arch/x86/include/asm/paravirt.h:374
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
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_load_gdt
  - arch/x86/xen/enlighten_pv.c:set_aliased_prot
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810291c3)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:pte_pfn
```
```
In arch/x86/xen/trace.c (ffffffff8102b704)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at
  - arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte
```
```
In arch/x86/mm/init_64.c (ffffffff810804b6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/fault.c (ffffffff8108106c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81086902)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_page_present
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:cpa_flush
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c326)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
```
```
In arch/x86/mm/mmio-mod.c (ffffffff8108d7d4)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:pre
  - arch/x86/mm/mmio-mod.c:pre
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c63d4)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In kernel/events/uprobes.c (ffffffff8121f4f8)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__replace_page
```
```
In mm/gup.c (ffffffff8125f046)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8126aa63)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pfn
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
  - mm/memory.c:print_bad_pte
```
```
In mm/mincore.c (ffffffff8126c032)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812739fa)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_vma_mapped.c (ffffffff81277769)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
```
```
In mm/rmap.c (ffffffff81279d9e)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/vmalloc.c (ffffffff8127b76c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a73d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffffffff8128d6c6)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swapin_readahead
```
```
In mm/swapfile.c (ffffffff81292035)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/swapfile.c:max_swapfile_size
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8129dd8a)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pgd
  - mm/hugetlb.c:follow_huge_pud
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:is_hugetlb_entry_hwpoisoned
  - mm/hugetlb.c:is_hugetlb_entry_migration
```
```
In mm/mempolicy.c (ffffffff8129e2aa)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/sparse-vmemmap.c (ffffffff81ae672b)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_verify
```
```
In mm/ksm.c (ffffffff812a5761)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b5850)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:__migration_entry_wait
  - mm/migrate.c:remove_migration_pte
```
```
In mm/khugepaged.c (ffffffff812c3e4c)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff812c8db8)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/hmm.c (ffffffff812dcc62)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/dax.c (ffffffff8135057d)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81379213)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_hugetlb_stats
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_hugetlb_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In arch/x86/power/hibernate.c (ffffffff8191d4d9)
Location: arch/x86/include/asm/paravirt.h:374
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
