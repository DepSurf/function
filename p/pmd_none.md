# Function: <code>pmd_none</code>

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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:515
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:515
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/gup.c (ffffffff811d4f74)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811da2c1)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/huge_memory.c (ffffffff812144c3)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:551
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
In arch/x86/xen/mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/gup.c (ffffffff811e4f94)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811e9ded)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/huge_memory.c (ffffffff812269f7)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In fs/dax.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:551
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:551
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/gup.c (ffffffff811ef5b5)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/memory.c (ffffffff811f4eee)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/huge_memory.c (ffffffff812327f7)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In fs/dax.c (ffffffff812ab7ed)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:690
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:690
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
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/mm/init_64.c (ffffffff8198c7f9)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/mm/hugetlbpage.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/gup.c (ffffffff81206604)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120dec3)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
```
```
In mm/mincore.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/huge_memory.c (ffffffff8124fec6)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In fs/dax.c (ffffffff812cef88)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/x86/include/asm/pgtable.h:700
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable.h:700
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6ba3)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddc15)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff810745b8)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff810750bb)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81077afb)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cccb)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8107e805)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f516)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826ef93f)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0237)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81227573)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
```
```
In mm/memory.c (ffffffff812299b0)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff8123219e)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239cc7)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123aec5)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8123d13c)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
```
```
In mm/vmalloc.c (ffffffff81240f4d)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8124614c)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a0ed)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255cf7)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8125a762)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff819ebe03)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8126e298)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81275e66)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c5fb)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81282ec5)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8129098b)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81293169)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1843)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812f8de2)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318d3a)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff819cfa9c)
Location: arch/x86/include/asm/pgtable.h:742
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/mmu_pv.c (ffffffff8288caec)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8289405d)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107a4a8)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107aebb)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e2ab)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff810835f6)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81085385)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108610f)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8108a362)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6f3f)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8123ad16)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In mm/memory.c (ffffffff8123ced3)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff8124596e)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d5e2)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124f09f)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81251608)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff81254c5d)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a56c)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e72d)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a147)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8126e5e2)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a27071)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81283126)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8128acc6)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290cbe)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81298f15)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812a596c)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a75bd)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81306203)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8130dde8)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132fdea)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a09095)
Location: arch/x86/include/asm/pgtable.h:767
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3f82)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab80b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e1eb)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107fdb9)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81081bb5)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087266)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088f85)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089beb)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108e0b7)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf5f5)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124bf05)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/memory.c (ffffffff8124eb3e)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff81257aba)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125fdf7)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812613f8)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81263874)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8126700d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127564d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127b98a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128527a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81289c22)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a97911)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/huge_memory.c (ffffffff812a58e6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812abaaf)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812b42f6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812c1063)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812c46ed)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8132775e)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff813346cd)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81357c1a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a78917)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7022)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae819)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107f27b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81080e49)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81082c75)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087f56)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81089bf5)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a85b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108ed54)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5a73)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125a3f6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/memory.c (ffffffff8125d0f5)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff81265fca)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e69d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126fba8)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81271d7d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127590d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128461d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128b46a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294e1a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81299792)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81acf1df)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812aecdf)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812b6da6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd2a9)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812c5c16)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812d2fb3)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812d6131)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a53e)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8134829d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136fe4a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81aafcc7)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccd4ad)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pmd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81047ab1)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81085bf6)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81087f1c)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a3f6)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c393)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810914d5)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff810950fc)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8d14)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/gup.c (ffffffff81287890)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8128d751)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault_around
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8129631a)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e484)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a05fb)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_normal_pmd
  - mm/mremap.c:get_old_pmd
```
```
In mm/pagewalk.c (ffffffff812a266d)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
```
```
In mm/vmalloc.c (ffffffff812a731c)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/madvise.c (ffffffff812b67ba)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bde94)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812cec82)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7b9d)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812e42ec)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ebf06)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f29df)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812fb906)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81308da2)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8130b352)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c843)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8137237b)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
```
```
In fs/dax.c (ffffffff8138f4b5)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813b7e7a)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff815e97e7)
Location: arch/x86/include/asm/pgtable.h:820
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb92de)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pmd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4d37)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81086cb8)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a667)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c633)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81090e05)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff81bda220)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd679a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/gup.c (ffffffff812916d0)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8129fc02)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault_around
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_set_pmd
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812a1287)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a9844)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812abb64)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812adfad)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b259c)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pte_range
```
```
In mm/ioremap.c (ffffffff812b808c)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_pte_range
```
```
In mm/madvise.c (ffffffff812c2a0a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c99b8)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da5c2)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c408c8)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812eff65)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812f6f76)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcff6)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81307556)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff81314bad)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81317212)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318783)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813801cb)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
```
```
In fs/dax.c (ffffffff813a0b43)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813c9d3a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff831c38e4)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7189)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff8108796c)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b2b7)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d04f)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810917d5)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff81bcc347)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e1202)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/filemap.c (ffffffff8125f9d7)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff81296bf0)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff812a549a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812a6a88)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aecd4)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0ff2)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812b339c)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b8c94)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c988a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812d0624)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1e32)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81c32921)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812f59fa)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812fd326)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303d6b)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff8130dcd6)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff8131ad5a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8131d50b)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e973)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8138754c)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
```
```
In fs/dax.c (ffffffff813a7d2a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813d139a)
Location: arch/x86/include/asm/pgtable.h:819
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff832a43a9)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a782)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff81096cde)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a857)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109c8cb)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810a1355)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff81ca23d9)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c4a8c)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/filemap.c (ffffffff8129c347)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812d7430)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff812e698d)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812e7f68)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f04c4)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2b08)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff812f4f2b)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In mm/vmalloc.c (ffffffff812fb248)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130e8aa)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81315b6e)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81328f15)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81d5132f)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff8133ffbe)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81346fe6)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134daca)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff81358b36)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f30a)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8136814a)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8136a8ab)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bd53)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813d4823)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In fs/dax.c (ffffffff813f767c)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8142289a)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff834536be)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49bed)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810a9786)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff810adb26)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b00ac)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810b5465)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff81e51abe)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff834774bf)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/filemap.c (ffffffff812f34e4)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff81337000)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8133d85f)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8134925b)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c542)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813539d8)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813566ef)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8135845a)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358e34)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
```
```
In mm/vmalloc.c (ffffffff8136274a)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376728)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81381168)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81398175)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81f215b9)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff813b4d27)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b74fc)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be573)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6d03)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff813d2d3d)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d999a)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff813e5972)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff813e8aaf)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9f63)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8145fcd1)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
```
```
In fs/dax.c (ffffffff8146a45f)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff814999aa)
Location: arch/x86/include/asm/pgtable.h:788
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff83e710c4)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81067f2c)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810c2b92)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7d39)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ca73e)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d03e5)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff810d4d38)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0af2)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/filemap.c (ffffffff8135d834)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff813b034c)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
```
```
In mm/memory.c (ffffffff813b687f)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff813c162e)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c50e2)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cde78)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0ce5)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2a8d)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3714)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
```
```
In mm/vmalloc.c (ffffffff813de0e1)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f407a)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813ff8fb)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81417ef5)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cbe3d)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81433ed7)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81439067)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440de5)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8144915d)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8145852e)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fd3a)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff8146d44c)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81470a38)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81472009)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff814ef5bc)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
```
```
In fs/dax.c (ffffffff814faf0c)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8152dbda)
Location: arch/x86/include/asm/pgtable.h:805
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff83691f3b)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff810697d3)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810c6272)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb479)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdd7e)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810d3a05)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff810d8238)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4c02)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/filemap.c (ffffffff8138f8ca)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff813e491c)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
```
```
In mm/memory.c (ffffffff813f4924)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff813f65d6)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f9550)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8140321f)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
```
```
In mm/mremap.c (ffffffff81405722)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff814077cd)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81408168)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409786)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8141293b)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81427d93)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b54c)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff821500ed)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81469827)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8146f316)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81476681)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e94e)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8148e276)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495524)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814a1e65)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814a4ec3)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81524dff)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
```
```
In fs/dax.c (ffffffff8153235f)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff81566026)
Location: arch/x86/include/asm/pgtable.h:806
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff838c1a4b)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:xen_pud_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81070d13)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/mm/init_64.c (ffffffff810ce6c2)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/pgtable.c (ffffffff810d39c9)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d645e)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:populate_pmd
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810dc195)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/pti.c (ffffffff810e0ab8)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5802)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In mm/filemap.c (ffffffff813b92f4)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8140f17c)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
```
```
In mm/memory.c (ffffffff81420f58)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_read_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_set_pmd
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:apply_to_pte_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vm_insert_pages
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:pmd_install
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81422286)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814250f2)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f7af)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
```
```
In mm/mremap.c (ffffffff81431c5c)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433e5b)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434888)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435fc9)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8143f3ab)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81461979)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484f2e)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/sparse-vmemmap.c (ffffffff82232f1d)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81498757)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149d22d)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5f41)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af609)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff814bdae6)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4d04)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d3542)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:move_pages_pte
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_poison
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In mm/hmm.c (ffffffff814d5f83)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81558a90)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
```
```
In fs/dax.c (ffffffff8156724f)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_pmd_load_hole
```
```
In fs/proc/task_mmu.c (ffffffff8159e016)
Location: arch/x86/include/asm/pgtable.h:1021
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/powerpc/mm/pgtable.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In arch/powerpc/mm/book3s64/hash_pgtable.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In arch/powerpc/mm/hugetlbpage.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In arch/powerpc/xmon/xmon.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/gup.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/mincore.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/mempolicy.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/khugepaged.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/memcontrol.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In mm/userfaultfd.c (c00000000046b8bc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In fs/dax.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:868
Inline: True
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
In arch/riscv/mm/init.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/gup.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/memory.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/madvise.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In mm/hmm.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/riscv/include/asm/pgtable.h:128
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
In arch/x86/xen/mmu_pv.c (ffffffff8289502b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c838)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e27b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107fe49)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81081c75)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f56)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088bb5)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108981b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dd14)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0a0b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81252a46)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/memory.c (ffffffff81255745)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff8125e61a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266ced)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812681f8)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126a3cd)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126df5d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127cc6d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81283a4a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d3fa)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81291d72)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e04f)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a72bf)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812af386)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b5889)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812be1f6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812cb593)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812ce711)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81332b1e)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8134087d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136842a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a4eb17)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/kernel/tboot.c (ffffffff82894a0c)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8106d4b6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8106db5d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810708c8)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075b84)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81077815)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810784e4)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff8107c834)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8b90)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81245ccd)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff81247e39)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_pte_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff81250aaa)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258b4d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a76a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8125c881)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/vmalloc.c (ffffffff8125ff55)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8126eafe)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812758f6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f1b3)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff812839e2)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a554)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff81298d12)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812a0876)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a6a9c)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812af319)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812bc495)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812bf480)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813234a0)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81332bd4)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8135976a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a0bc23)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a8022)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7fb)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8107e22b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff8107fdf9)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81081c25)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086f06)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81088b65)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810897cb)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff8108dcc4)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c390a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812507e6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/memory.c (ffffffff812534e5)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff8125c3ba)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81264a8d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265f98)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff8126816d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/vmalloc.c (ffffffff8126bcfd)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127aa0d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128185a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b20a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8128fb82)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ada45f)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812a50cf)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812ad196)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b3699)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812bc006)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812c93a3)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812cc521)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813305ee)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133e34d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81365efa)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81abaf07)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/x86/xen/mmu_pv.c (ffffffff828a8028)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_cleanhighmap
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af829)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/mm/init_64.c (ffffffff8108031b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:cleanup_highmap
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pte
```
```
In arch/x86/mm/fault.c (ffffffff81081ee9)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81083d45)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:populate_pmd
  - arch/x86/mm/pageattr.c:try_to_free_pmd_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81089036)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff8108ae05)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:pmd_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108ba6b)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/pti.c (ffffffff810900a4)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6ab0)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81260166)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/memory.c (ffffffff81262edf)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
```
```
In mm/mincore.c (ffffffff8126bdaa)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81274476)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8127592d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/pagewalk.c (ffffffff81277aed)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In mm/vmalloc.c (ffffffff8127b70d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a5ed)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81291588)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129b02a)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8129f012)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6915)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
```
```
In mm/migrate.c (ffffffff812b5c27)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff812bd516)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3b00)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/memcontrol.c (ffffffff812cc7d6)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/userfaultfd.c (ffffffff812da083)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812dd281)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81342f3c)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8135226d)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379aea)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff81ac7357)
Location: arch/x86/include/asm/pgtable.h:784
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
