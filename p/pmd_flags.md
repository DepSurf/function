# Function: <code>pmd_flags</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62a49)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810346eb)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb24)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068d16)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:vmemmap_populate
```
```
In arch/x86/mm/fault.c (ffffffff8106a2ed)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c690)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/pgtable.c (ffffffff81071009)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In arch/x86/mm/gup.c (ffffffff81071728)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In mm/gup.c (ffffffff811ba3f2)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bc2a2)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff811c2768)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811c8b05)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/rmap.c (ffffffff811ca8d8)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811ce461)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
```
```
In mm/pagewalk.c (ffffffff811cffc0)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
```
```
In mm/madvise.c (ffffffff811d14ec)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811d434c)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811df7e4)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff811e006d)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff811f61f5)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:split_huge_page_address
```
```
In mm/memcontrol.c (ffffffff811fafce)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
```
In fs/userfaultfd.c (ffffffff8125af93)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812782f3)
Location: arch/x86/include/asm/pgtable_types.h:310
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu.c (ffffffff81f8ab51)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810338ac)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bc14)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81896ca1)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81069f57)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106d718)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81071298)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/gup.c (ffffffff81071c54)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81074110)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811d52ab)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811dad47)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff811de34c)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811e4989)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811e5c4b)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e77d2)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811eae06)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ed162)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In mm/madvise.c (ffffffff811eeaf7)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff811f2151)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff811fde69)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff811fed83)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff812160b7)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812210c7)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/userfaultfd.c (ffffffff81283b59)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812a5549)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81760884)
Location: arch/x86/include/asm/pgtable_types.h:348
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
In arch/x86/xen/mmu.c (ffffffff81fc5f3f)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810334d9)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb8e)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818cb38c)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106daf7)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810713a4)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81074e18)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/gup.c (ffffffff810757c4)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pud_range
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81077c88)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811e52c6)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811ea90f)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff811ee15c)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811f497b)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff811f5ed3)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff811f6f57)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff811f7552)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In mm/rmap.c (ffffffff811f8b62)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff811fc066)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In mm/madvise.c (ffffffff811ff437)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81202b49)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff8120e94c)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/mempolicy.c (ffffffff812105bf)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff81228679)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8123380d)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/userfaultfd.c (ffffffff8129774c)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8129bb68)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff812bae99)
Location: arch/x86/include/asm/pgtable_types.h:348
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d9e4)
Location: arch/x86/include/asm/pgtable_types.h:348
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
In arch/x86/xen/mmu_pv.c (ffffffff820a6e14)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103169c)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e22d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819029b0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d825)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81070dae)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810743c8)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810765a6)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff811f0d80)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff811f1b21)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff811f9169)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff811ff8ce)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81200ccb)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81201e4f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81202366)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In mm/rmap.c (ffffffff8120323e)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812057ad)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8120a0e9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8120dbfd)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/mempolicy.c (ffffffff8121bfb7)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/huge_memory.c (ffffffff81231ce6)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8123f0b3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/userfaultfd.c (ffffffff812a5085)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812aaab5)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812c8019)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abbc3)
Location: arch/x86/include/asm/pgtable_types.h:385
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
In arch/x86/xen/mmu_pv.c (ffffffff826acff6)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:pmd_large
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033911)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061f10)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81071533)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff81072245)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810764d9)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81079e5f)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c875)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/pti.c (ffffffff826c581b)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5e82)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In mm/gup.c (ffffffff81205483)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81208955)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff81211412)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217e67)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219139)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a9c4)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b3de)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In mm/rmap.c (ffffffff8121bd2a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f7a1)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81223315)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228e30)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232cdd)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81237237)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b598)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81255bb8)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8125eb69)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/hmm.c (ffffffff8126e5d5)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812c84bf)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812ce7b7)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff812eb8dc)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff81823181)
Location: arch/x86/include/asm/pgtable_types.h:410
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
In arch/x86/xen/mmu_pv.c (ffffffff826d683c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034c8f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064fc0)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e921c)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810752a3)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81079184)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff8107cacf)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f523)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fdfb)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff826ef917)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efc4d)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0363)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff812269ff)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812299bd)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff812321ab)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239bb8)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123aae4)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123cb1b)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d3cd)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8123d8c0)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8123dc32)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240f12)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81246182)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a11a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255d16)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8125a76f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e2a5)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81279a53)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81282ece)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81288b11)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff81293212)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff812f1850)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812f869a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
```
```
In fs/proc/task_mmu.c (ffffffff81318d99)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d479)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c785)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035e6f)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ac30)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a24b62)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b0a3)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107fa3f)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
```
```
In arch/x86/mm/pgtable.c (ffffffff810834ff)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108611c)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kmmio.c (ffffffff8108693b)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108a338)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a690a)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a706b)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81239adc)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123cee0)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff8124597b)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d60f)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ecf0)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250ff1)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812517ee)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251e70)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff81252217)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254c22)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8125a5a2)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e75a)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a166)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8126e5ef)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81283133)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128e033)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81298f1e)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8129d814)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812a75e4)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81306210)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8130c41f)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8132fe49)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8188f44e)
Location: arch/x86/include/asm/pgtable_types.h:433
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a08f93)
Location: arch/x86/include/asm/pgtable_types.h:433
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3c25)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037fcf)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e3e9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94f35)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea11)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810833fa)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff8108716f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089b50)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a54b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108e081)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828befbc)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf725)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124ad22)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124eb4b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81257ac7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125fcce)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81261046)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812632d8)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81263ac7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81264151)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff81264a7c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266fd2)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81275683)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127b9af)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128529c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81289c2f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f616)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a89bd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812b42ff)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b8ae6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4714)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8132776b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81333962)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81357c79)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818d944e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a7889f)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/xen/mmu_pv.c (ffffffff828a6cbf)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103879f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f999)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc815)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107faa1)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810844ca)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81087e5f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a7c0)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b1bb)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108ed2a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5435)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5ba9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81259212)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d102)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81265fd7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e58e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f7df)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81271a88)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271f64)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812729c1)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff81273303)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812758d2)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff81284653)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128b48f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294e3c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8129979f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aecec)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b9f3d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812c5c1f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812ca9c6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d613e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a54b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81347527)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff8136fea9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8190b44e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81aafc4f)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/xen/mmu_pv.c (ffffffff82ccc3ad)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:pmd_large
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b066)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ea9)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108577e)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81086c84)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a2ff)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c88f)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff81092465)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81094a40)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8646)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff8109527f)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pmd_large
```
```
In mm/gup.c (ffffffff8128934d)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8128d75a)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81296327)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e4cb)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a0348)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812a1e25)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2708)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812a3784)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff812a3ed3)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a72f0)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff812b67f0)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bdeb9)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812cec8b)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e42f9)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812eeb1d)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812fb90f)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130080e)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b35f)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c8a6)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff8130cc6b)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81372384)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
```
```
In fs/dax.c (ffffffff8138f4c2)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813b7ed9)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff815e9b08)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc47e)
Location: arch/x86/include/asm/pgtable_types.h:456
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff82fb81eb)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:pmd_large
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b876)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810774d9)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108682e)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81088564)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a57f)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c291)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff81091b05)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff81093e00)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6064)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bda2ee)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pmd_large
```
```
In kernel/events/core.c (ffffffff8123cb63)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129302d)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8129fc0b)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812a1294)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a988b)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab868)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812ad64f)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae048)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812af064)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff812afbe0)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b2570)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/ioremap.c (ffffffff812b85e6)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/madvise.c (ffffffff812c2a40)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c99dd)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da5cb)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812eff72)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fa17d)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8130755f)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130c9ae)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131721f)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813187e6)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff81318bab)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813801d4)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
```
```
In fs/dax.c (ffffffff813a0b4c)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813c9d99)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bd145e)
Location: arch/x86/include/asm/pgtable_types.h:457
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff831c2859)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:pmd_large
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d215)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f60)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087581)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810891e3)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b1df)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d531)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff81092645)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff810947c0)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0acc)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81bcc412)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pmd_large
```
```
In kernel/events/core.c (ffffffff81243e78)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8125fafd)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8129a887)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff812a54a3)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812a6a95)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aed1b)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0c60)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812b2d61)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3437)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812b4110)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/rmap.c (ffffffff812b5181)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8ca1)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c98c0)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812d0649)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1e3b)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5a07)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81300f2e)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8130dcdf)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8131311d)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131d518)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e9d6)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff8131ed9b)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81387559)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In fs/dax.c (ffffffff813a7d33)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813d13f9)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3468)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff832a3265)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:pmd_large
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042d53)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8108576b)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810968cf)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8109863c)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a77f)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cdaf)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2365)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff810a46e0)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c41ab)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca2528)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pmd_large
```
```
In kernel/events/core.c (ffffffff8127e7e3)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8129c46d)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812db240)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff812e699a)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff812e7f75)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f050b)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2697)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812f4921)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4fc4)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff812f5cf0)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/rmap.c (ffffffff812f6d1d)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb255)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130e8e0)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81315b93)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81328f1e)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8132c06f)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff8133ffcb)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8134ab9e)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/memcontrol.c (ffffffff81358b3f)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f317)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136a8b8)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bdb6)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff8136c17b)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813d4830)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
```
```
In fs/dax.c (ffffffff813f7689)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff814228f9)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81c94478)
Location: arch/x86/include/asm/pgtable_types.h:453
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff834524d4)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:pmd_large
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac8f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095b35)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a91f9)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab295)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810ada1f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b05e5)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff810b69e9)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810b8f50)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51d5f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pmd_large
```
```
In kernel/events/core.c (ffffffff812d3451)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff812f35ad)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/percpu.c (ffffffff8348ba24)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133adfd)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8133d86c)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81349268)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c54f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353a3f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356801)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81358854)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358f2f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81359c20)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/rmap.c (ffffffff8135c9a9)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81362757)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376775)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8138118c)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8139817e)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/sparse-vmemmap.c (ffffffff8139c015)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_range
  - mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/migrate.c (ffffffff813b4d30)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b7509)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1d2c)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/memcontrol.c (ffffffff813d2d4a)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d99a7)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e8abc)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9fcf)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff813ea40f)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8145fcde)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
```
```
In fs/dax.c (ffffffff8146a46c)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff81499a09)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff81e434a2)
Location: arch/x86/include/asm/pgtable_types.h:455
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6fa4c)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056a70)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab77b)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c7589)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810c363f)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7c1f)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cac9d)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1c30)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810d4d05)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0c7e)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8133b6ce)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8135d903)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8137fc50)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83ebc938)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2577)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813b688c)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff813c163b)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c50ef)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cded8)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0e12)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2f51)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d378d)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff813d45f0)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_mkinvalid
```
```
In mm/rmap.c (ffffffff813d6115)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In mm/vmalloc.c (ffffffff813de0ee)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f40ca)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff813ff926)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb_vmemmap.c (ffffffff8141411c)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff81417efe)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8141eef5)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81433ee0)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81439074)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443f0c)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (ffffffff81447463)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8145853b)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fd47)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff81470a45)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8147207e)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff81472510)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff814ef5c9)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
```
```
In fs/dax.c (ffffffff814faf19)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8152dc39)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8201e548)
Location: arch/x86/include/asm/pgtable_types.h:434
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff83690806)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057a3f)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af33b)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b619)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e89)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb35f)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce2cd)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff810d50e0)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff810d8205)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4d8e)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff8136d0d7)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b11d2)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff836e4fb8)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e769b)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813f4aa9)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff813f65e3)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f955d)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81403360)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
```
```
In mm/mremap.c (ffffffff814057c2)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81407bda)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814081e8)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409793)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8140b219)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
```
```
In mm/vmalloc.c (ffffffff81412948)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81428195)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff8144767c)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
  - mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd
```
```
In mm/mempolicy.c (ffffffff8144b559)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff81453b29)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81469830)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8146f31f)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147948c)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff8147cb33)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8148e283)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495531)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff814a4fb9)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a693d)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff814a6c70)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81524d96)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
```
```
In fs/dax.c (ffffffff8153236c)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff81566091)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8209e542)
Location: arch/x86/include/asm/pgtable_types.h:435
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/xen/mmu_pv.c (ffffffff838c02d6)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ecdf)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5ecb)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222e0c9)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_check_pmd
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf34d)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d38af)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
  - arch/x86/mm/pgtable.c:pmdp_invalidate_ad
  - arch/x86/mm/pgtable.c:pmdp_clear_flush_young
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d69ad)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:unmap_pmd_range
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd7eb)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pmd_presence
```
```
In arch/x86/mm/pti.c (ffffffff810e0a85)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt_amd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f598e)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd
```
```
In kernel/events/core.c (ffffffff81396317)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da752)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff839177c9)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412319)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff814210fa)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_pmd_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff81422293)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814250ff)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f8f0)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
```
```
In mm/mremap.c (ffffffff81431cfc)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8143429e)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434908)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435fd6)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:__pte_offset_map
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff81437b56)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
```
```
In mm/vmalloc.c (ffffffff8143f3b8)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81461986)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb_vmemmap.c (ffffffff81480de5)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_pmd_entry
  - mm/hugetlb_vmemmap.c:vmemmap_split_pmd
```
```
In mm/mempolicy.c (ffffffff81484f3b)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/ksm.c (ffffffff8148e36c)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81498760)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149de1e)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a8a1f)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:can_change_pmd_writable
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff814ac1d3)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff814bdaf3)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4d11)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d354b)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
```
```
In mm/hmm.c (ffffffff814d6078)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d79cd)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In mm/ptdump.c (ffffffff814d7c70)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81558a27)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
```
```
In fs/dax.c (ffffffff8156725c)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8159e079)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff82176542)
Location: arch/x86/include/asm/pgtable_types.h:463
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82894cc8)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810388ff)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e939)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b685)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107eaa1)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810834ca)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e5f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089780)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a17b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108dcea)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b03cd)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0b41)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81251862)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255752)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8125e627)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266bde)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267e2f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8126a0d8)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a5b4)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff8126b011)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8126b953)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126df22)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127cca3)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81283a6f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d41c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81291d7f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a72cc)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b251d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812be1ff)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c2fa6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ce71e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81332b2b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133fb07)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81368489)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818ab44e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a4ea9f)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/kernel/espfix_64.c (ffffffff81028275)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eeec)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a27bdb)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106de22)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81072267)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff81075aaf)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810784f1)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kmmio.c (ffffffff81078c28)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/pti.c (ffffffff8107c80a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8cc6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff81244741)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81247e46)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mincore.c (ffffffff81250ab7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258b73)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a126)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be6c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125ca40)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8125d045)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8125d563)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125ff2e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8126eb24)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81275914)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f1d5)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff812839ef)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298d1f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a38ad)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812af323)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b4061)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bf48c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813234ad)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81330726)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff813597c9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818653e9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0bb82)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7cbf)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103875f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ede9)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad7a95)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea51)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108347a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81086e0f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089730)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a12b)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8108dc9a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c32cc)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3a40)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8124f602)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812534f2)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8125c3c7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126497e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265bcf)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267e78)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268354)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81268db1)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff812696f3)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bcc2)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8127aa43)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128187f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b22c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8128fb8f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a50dc)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b032d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812bc00f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c0db6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cc52e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813305fb)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133d5d7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81365f59)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff818fc44e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81abae8f)
Location: arch/x86/include/asm/pgtable_types.h:432
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
In arch/x86/xen/mmu_pv.c (ffffffff828a7cc5)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103975f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071069)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3f55)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81080b41)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81085181)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/pgtable.c (ffffffff81088f3f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_clear_huge
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b9d0)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c3cb)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In arch/x86/mm/pti.c (ffffffff8109007a)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pte
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6472)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c6be6)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range
  - arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte
```
```
In mm/gup.c (ffffffff8125ef72)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81262eec)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pud_range
```
```
In mm/mincore.c (ffffffff8126bdb7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81274350)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275571)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812777f7)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277cd4)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81278741)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmdp_invalidate
```
```
In mm/rmap.c (ffffffff8127920c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b6d2)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffff8128a623)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812915ad)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129b04c)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8129f01f)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5c34)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812c066d)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812cc7df)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812d1876)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dd28e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81342f49)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff813504ed)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
```
In fs/proc/task_mmu.c (ffffffff81379b49)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In arch/x86/power/hibernate.c (ffffffff8191d44e)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81ac72df)
Location: arch/x86/include/asm/pgtable_types.h:432
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
