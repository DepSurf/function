# Function: <code>pmd_present</code>

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
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810346eb)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb24)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81068d16)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pmd_init
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a2ed)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
```
```
In mm/rmap.c (ffffffff811ca8d8)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff811df7e4)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/huge_memory.c (ffffffff811f6ff3)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - mm/huge_memory.c:page_check_address_pmd
  - mm/huge_memory.c:split_huge_page_address
```
```
In fs/userfaultfd.c (ffffffff8125af93)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff8127861e)
Location: arch/x86/include/asm/pgtable.h:486
Inline: True
Inline callers:
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
In arch/x86/xen/mmu.c (ffffffff81f8a62e)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810338ac)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bc14)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818964e1)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff81069f57)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In mm/rmap.c (ffffffff811e77d2)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff811fde69)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In fs/userfaultfd.c (ffffffff81283b59)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812a5549)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In arch/x86/xen/mmu.c (ffffffff81fc5a28)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810334d9)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb8e)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff818cabf2)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106daf7)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/mm/gup.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff811f6f57)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f8b62)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:page_check_address_transhuge
  - mm/rmap.c:mm_find_pmd
```
```
In mm/hugetlb.c (ffffffff8120e94c)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_huge_pmd
```
```
In mm/huge_memory.c (ffffffff81228041)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In fs/userfaultfd.c (ffffffff8129774c)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812bae99)
Location: arch/x86/include/asm/pgtable.h:522
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
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
In arch/x86/xen/mmu_pv.c (ffffffff820a68fc)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103169c)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e22d)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819020d6)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff8106d825)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
```
```
In mm/page_vma_mapped.c (ffffffff81201e4f)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81203b13)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/huge_memory.c (ffffffff8123422f)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - mm/huge_memory.c:move_huge_pmd
```
```
In fs/userfaultfd.c (ffffffff812a5085)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (ffffffff812c8019)
Location: arch/x86/include/asm/pgtable.h:661
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_present(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff826acff6)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033911)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061f10)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8198c10d)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pud_table
```
```
In arch/x86/mm/fault.c (ffffffff81072245)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
```
```
In mm/gup.c (ffffffff81205483)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8120e76d)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81211412)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81217e67)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81219139)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a9c4)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121b3de)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
```
```
In mm/rmap.c (ffffffff8121c831)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81223315)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81228e30)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232cdd)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81237237)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8124b598)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81252ac8)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8125eb69)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In fs/userfaultfd.c (ffffffff812c84bf)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812ce7b7)
Location: arch/x86/include/asm/pgtable.h:671
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/proc/task_mmu.c (ffffffff812eb8dc)
Location: arch/x86/include/asm/pgtable.h:671
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81204fa0-ffffffff81204fde: pmd_present (STB_LOCAL)
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
In arch/x86/xen/mmu_pv.c (ffffffff826d6334)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034c8f)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064fc0)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff819e8aa8)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff810752a3)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107843d)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c98e)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f579)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff812269ff)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8122ff8e)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff812321ab)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81239bb8)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8123aae4)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c6c3)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123d3cd)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
```
```
In mm/rmap.c (ffffffff8123e601)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81246182)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8124a11a)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255d16)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8125a76f)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8126e2a5)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff81276ed6)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81282ece)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81288b11)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In fs/userfaultfd.c (ffffffff812f1850)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff812f8deb)
Location: arch/x86/include/asm/pgtable.h:713
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81318d99)
Location: arch/x86/include/asm/pgtable.h:713
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff8288c27f)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035e6f)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ac30)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a24331)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107b0a3)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8107ebed)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff810833be)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108616b)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff81239adc)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81241c84)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8124597b)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8124d60f)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124ecf0)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250ae0)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812517ee)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252b91)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8125a5a2)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8125e75a)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a166)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8126e5ef)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81283133)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff8128bc31)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff81298f1e)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8129d814)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812a75e4)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81306210)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8130df16)
Location: arch/x86/include/asm/pgtable.h:738
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8132fe49)
Location: arch/x86/include/asm/pgtable.h:738
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a08f93)
Location: arch/x86/include/asm/pgtable.h:738
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
In arch/x86/xen/mmu_pv.c (ffffffff828a3725)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037fcf)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e3e9)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94488)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea11)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff810824ca)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff8108702e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089ba4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/gup.c (ffffffff8124ad22)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812545e7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81257ac7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8125fcce)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81261046)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262dc0)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81263ac7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264f11)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81275683)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8127b9af)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128529c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81289c2f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8129f616)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a685f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812b42ff)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b8ae6)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812c4714)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8132776b)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133613e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81357c79)
Location: arch/x86/include/asm/pgtable.h:755
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a7889f)
Location: arch/x86/include/asm/pgtable.h:755
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
In arch/x86/xen/mmu_pv.c (ffffffff828a67cb)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103879f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f999)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acbd68)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107faa1)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108358a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81087d1e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a814)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/gup.c (ffffffff81259212)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262b47)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81265fd7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126e58e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8126f7df)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81271570)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81271f64)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In mm/rmap.c (ffffffff812737a1)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff81284653)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128b48f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294e3c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8129979f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812aecec)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b7d38)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812c5c1f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812ca9c6)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812d613e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a54b)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81349d3e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff8136fea9)
Location: arch/x86/include/asm/pgtable.h:755
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81aafc4f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_present(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc3ad)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b066)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ea9)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81084642)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81086c84)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a1be)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
```
```
In mm/gup.c (ffffffff8128934d)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff81294a5a)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81296327)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8129e4cb)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812a0348)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812a1e25)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2708)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
```
```
In mm/rmap.c (ffffffff812a4973)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff812b67f0)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812bdeb9)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812cec8b)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812e42f9)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ed0ae)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812fb90f)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130080e)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8130b35f)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c8f0)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81372384)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
```
```
In fs/dax.c (ffffffff8138f4c2)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813b7ed9)
Location: arch/x86/include/asm/pgtable.h:791
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff815e9b08)
Location: arch/x86/include/asm/pgtable.h:791
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
```
**Symbols:**

```
ffffffff81085fa2-ffffffff81085fcd: pmd_present (STB_LOCAL)
ffffffff812875f0-ffffffff8128761b: pmd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_present(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff82fb81eb)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b876)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810774d9)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085b22)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81088564)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a43e)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In kernel/events/core.c (ffffffff8123cb63)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129302d)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff8129f2da)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:pte_alloc_one_map
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
```
```
In mm/mincore.c (ffffffff812a1294)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812a988b)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812ab868)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812ad64f)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae048)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In mm/rmap.c (ffffffff812b0103)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/ioremap.c (ffffffff812b85e6)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/madvise.c (ffffffff812c2a40)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812c99dd)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/mempolicy.c (ffffffff812da5cb)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812eff72)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812f8312)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8130755f)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8130c9ae)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131721f)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318830)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813801d4)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In fs/dax.c (ffffffff813a0b4c)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813c9d99)
Location: arch/x86/include/asm/pgtable.h:790
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81bd8916-ffffffff81bd8941: pmd_present (STB_LOCAL)
ffffffff81291430-ffffffff8129145b: pmd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_present(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff831c2859)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d215)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f60)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086852)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810891e3)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8108b094)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In kernel/events/core.c (ffffffff81243e78)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8125fafd)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff8129a887)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff812a4281)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812a6a95)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812aed1b)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812b0c60)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812b2845)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3437)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In mm/rmap.c (ffffffff812b56f8)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b81a2)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff812c98c0)
Location: arch/x86/include/asm/pgtable.h:790
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
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff812e1e3b)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812f5a07)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812fb38a)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff8130dcdf)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8131311d)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8131d518)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131ea20)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff81387559)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
```
```
In fs/dax.c (ffffffff813a7d33)
Location: arch/x86/include/asm/pgtable.h:790
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff813d13f9)
Location: arch/x86/include/asm/pgtable.h:790
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
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81bca7be-ffffffff81bca7ed: pmd_present (STB_LOCAL)
ffffffff81296980-ffffffff812969ab: pmd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_present(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff832a3265)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042d53)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8108575d)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810968cf)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8109863c)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff8109a634)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
```
```
In kernel/events/core.c (ffffffff8127e7e3)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8129c46d)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/gup.c (ffffffff812db240)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff812e56e4)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_pmd_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff812e7f75)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff812f050b)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff812f2697)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812f446a)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f4fc4)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
```
```
In mm/rmap.c (ffffffff812f738c)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fa8f2)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff8130e8e0)
Location: arch/x86/include/asm/pgtable.h:761
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
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81328f1e)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff8133ffcb)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff813451ba)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/memcontrol.c (ffffffff81358b3f)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8135f317)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff8136a8b8)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136be00)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff813d4830)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
```
```
In fs/dax.c (ffffffff813f7689)
Location: arch/x86/include/asm/pgtable.h:761
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff814228f9)
Location: arch/x86/include/asm/pgtable.h:761
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
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81c9fc64-ffffffff81c9fc93: pmd_present (STB_LOCAL)
ffffffff812d7200-ffffffff812d722b: pmd_present (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pmd_present(pmd_t pmd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff834524d4)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104ac8f)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095b27)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a91f9)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:ident_pmd_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab295)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810ad8a8)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
```
```
In kernel/events/core.c (ffffffff812d3451)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff812f35ad)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/percpu.c (ffffffff8348ba24)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8133adfd)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:is_swap_pmd
```
```
In mm/memory.c (ffffffff81347a38)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81349268)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff8134c54f)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81353a3f)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81356801)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81358517)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81358f2f)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
```
```
In mm/rmap.c (ffffffff8135c9a9)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81361d0c)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81376775)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8138118c)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff8139817e)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff813b4d30)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff813b7509)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813be580)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/memcontrol.c (ffffffff813d2d4a)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff813d99a7)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff813e8abc)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff813ea018)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff8145fcde)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
```
```
In fs/dax.c (ffffffff8146a46c)
Location: arch/x86/include/asm/pgtable.h:759
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff81499a09)
Location: arch/x86/include/asm/pgtable.h:759
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
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff810a7e80-ffffffff810a7eb3: pmd_present (STB_LOCAL)
ffffffff81336b70-ffffffff81336ba3: pmd_present (STB_LOCAL)
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
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056a70)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab76d)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c574e)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810c363f)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810c7a58)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In kernel/events/core.c (ffffffff8133b6ce)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/filemap.c (ffffffff8135d903)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pmd
```
```
In mm/vmscan.c (ffffffff8137facc)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff83ebc938)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b0d37)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813bfdee)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_fault
  - mm/memory.c:finish_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff813c163b)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813c50ef)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff813cded8)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813d0e12)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff813d2be9)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d378d)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In mm/vmalloc.c (ffffffff813dd6c7)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff813f40ca)
Location: arch/x86/include/asm/pgtable.h:776
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
In mm/swapfile.c (ffffffff813ff926)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/mempolicy.c (ffffffff81417efe)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/ksm.c (ffffffff8141eef5)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81433ee0)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff81439074)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81440df2)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In mm/khugepaged.c (ffffffff81447463)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8145853b)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff8145fd47)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff81470a45)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814720ca)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
```
```
In fs/userfaultfd.c (ffffffff814ef5c9)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
```
```
In fs/dax.c (ffffffff814faf19)
Location: arch/x86/include/asm/pgtable.h:776
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8152dc39)
Location: arch/x86/include/asm/pgtable.h:776
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
In arch/x86/xen/mmu_pv.c (ffffffff83690806)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057a3f)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af32d)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff821497be)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6e89)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810cb1a0)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
```
```
In kernel/events/core.c (ffffffff8136d0d7)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b10a3)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff836e4fb8)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e769b)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff813f4aa9)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff813f65e3)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff813f955d)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff81403360)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
```
```
In mm/mremap.c (ffffffff814057c2)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff814077dd)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814081e8)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81409793)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff81411f1b)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81428195)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff8144b559)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
```
```
In mm/ksm.c (ffffffff81453b29)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81469830)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8146f31f)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147668e)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff8147cb33)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff8148e283)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff81495531)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/hmm.c (ffffffff814a4fb9)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81524d96)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
```
```
In fs/dax.c (ffffffff8153236c)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff81566091)
Location: arch/x86/include/asm/pgtable.h:777
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/x86/xen/mmu_pv.c (ffffffff838c02d6)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ecdf)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5ebd)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222c27e)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:ident_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf34d)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pgtable.c (ffffffff810d36f0)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
```
```
In kernel/events/core.c (ffffffff81396317)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da623)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/percpu.c (ffffffff839177c9)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff81412319)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
```
```
In mm/memory.c (ffffffff814210fa)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:vm_normal_page_pmd
```
```
In mm/mincore.c (ffffffff81422293)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mlock.c (ffffffff814250ff)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/mlock.c:mlock_pte_range
  - mm/mlock.c:mlock_pte_range
```
```
In mm/mprotect.c (ffffffff8142f8f0)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
```
```
In mm/mremap.c (ffffffff81431cfc)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81433ea2)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434908)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
```
```
In mm/pgtable-generic.c (ffffffff81435fd6)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/pgtable-generic.c:__pte_offset_map
```
```
In mm/vmalloc.c (ffffffff8143e77c)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/madvise.c (ffffffff81461986)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/mempolicy.c (ffffffff81484f3b)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_pte_range
  - mm/mempolicy.c:queue_folios_pmd
```
```
In mm/ksm.c (ffffffff8148e36c)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81498760)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/migrate_device.c (ffffffff8149de1e)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a5f4e)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:move_pages_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In mm/khugepaged.c (ffffffff814ac1d3)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
```
In mm/memcontrol.c (ffffffff814bdaf3)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff814c4d11)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_pte_range
  - mm/memory-failure.c:hwpoison_pte_range
```
```
In mm/userfaultfd.c (ffffffff814d354b)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
  - mm/userfaultfd.c:move_pages
```
```
In mm/hmm.c (ffffffff814d6078)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81558a27)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
```
```
In fs/dax.c (ffffffff8156725c)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
```
```
In fs/proc/task_mmu.c (ffffffff8159e079)
Location: arch/x86/include/asm/pgtable.h:992
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:gather_pte_stats
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:clear_refs_pte_range
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
In arch/powerpc/mm/pgtable.c (c000000000087aa0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable.c:__find_linux_pte
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000eebdfc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable
  - arch/powerpc/mm/book3s64/radix_pgtable.c:__map_kernel_page
```
```
In arch/powerpc/mm/book3s64/subpage_prot.c (c00000000009f6b0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry
```
```
In mm/filemap.c (c000000000364f28)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/filemap.c:filemap_map_pages
```
```
In mm/gup.c (c0000000003b6914)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (c0000000003c3c38)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (c0000000003c83c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (c0000000003d20d0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (c0000000003d43b4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (c0000000003d57f0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (c0000000003d6a8c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
```
```
In mm/rmap.c (c0000000003d87cc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (c0000000003f2e94)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (c0000000003fcfe4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/mempolicy.c (c0000000004130c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (c000000000434aa4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (c000000000440e14)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (c000000000456a70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (c00000000045eaa8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (c00000000046be1c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c0000000004704e8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (c000000000501988)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (c000000000515dd4)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
```
```
In fs/proc/task_mmu.c (c00000000054d478)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
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
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (c000000000eca178)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:873
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
In arch/riscv/mm/fault.c (ffffffe0000b9e14)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In arch/riscv/mm/hugetlbpage.c (ffffffe0000ba60a)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - arch/riscv/mm/hugetlbpage.c:pmd_huge
```
```
In mm/gup.c (ffffffe000204604)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
```
```
In mm/memory.c (ffffffe000206716)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:do_fault
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffe000211186)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/page_vma_mapped.c (ffffffe00021270e)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffe00021377c)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffe00021521c)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/madvise.c (ffffffe000220958)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffe00022695c)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffe00022fc22)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/hmm.c (ffffffe000251f30)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffe0002a8794)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/proc/task_mmu.c (0)
Location: arch/riscv/include/asm/pgtable.h:123
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/riscv/include/asm/pgtable.h:123
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
In arch/x86/xen/mmu_pv.c (ffffffff828947d4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810388ff)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e939)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6abd8)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107eaa1)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108258a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81086d1e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810897d4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/gup.c (ffffffff81251862)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125b197)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8125e627)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81266bde)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81267e2f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269bc0)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a5b4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In mm/rmap.c (ffffffff8126bdf1)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8127cca3)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81283a6f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d41c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff81291d7f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a72cc)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812b0318)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812be1ff)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c2fa6)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812ce71e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81332b2b)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8134231e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81368489)
Location: arch/x86/include/asm/pgtable.h:755
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a4ea9f)
Location: arch/x86/include/asm/pgtable.h:755
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
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eeec)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a26fcd)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8106de22)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff81071354)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (ffffffff8107598e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81078548)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In mm/gup.c (ffffffff81244741)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_pmd_mask
```
```
In mm/memory.c (ffffffff8124d3b4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff81250ab7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81258b73)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8125a126)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125be6c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125ca40)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de5e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8126eb24)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff81275914)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f1d5)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff812839ef)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff81298d1f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812a17b3)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812af323)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812b4061)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/hmm.c (ffffffff812bf48c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813234ad)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff81332c95)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813597c9)
Location: arch/x86/include/asm/pgtable.h:755
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81a0bb82)
Location: arch/x86/include/asm/pgtable.h:755
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
In arch/x86/xen/mmu_pv.c (ffffffff828a77cb)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103875f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ede9)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad6fe8)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff8107ea51)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108253a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81086cce)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089784)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/gup.c (ffffffff8124f602)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81258f37)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8125c3c7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff8126497e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81265bcf)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81267960)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268354)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In mm/rmap.c (ffffffff81269b91)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8127aa43)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff8128187f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b22c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8128fb8f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812a50dc)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812ae128)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812bc00f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812c0db6)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812cc52e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff813305fb)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff8133fdee)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81365f59)
Location: arch/x86/include/asm/pgtable.h:755
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
```
In lib/ioremap.c (ffffffff81abae8f)
Location: arch/x86/include/asm/pgtable.h:755
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
In arch/x86/xen/mmu_pv.c (ffffffff828a77d1)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103975f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071069)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae34a8)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:phys_pmd_init
  - arch/x86/mm/init_64.c:phys_pmd_init
```
```
In arch/x86/mm/fault.c (ffffffff81080b41)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8108465a)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In arch/x86/mm/pgtable.c (ffffffff81088dfe)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_set_huge
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108ba24)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In mm/gup.c (ffffffff8125ef72)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81268937)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:copy_page_range
```
```
In mm/mincore.c (ffffffff8126bdb7)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mincore.c:mincore_pte_range
  - mm/mincore.c:mincore_pte_range
```
```
In mm/mprotect.c (ffffffff81274350)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81275571)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812772f6)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277cd4)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In mm/rmap.c (ffffffff81279501)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/madvise.c (ffffffff8128a623)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swapfile.c (ffffffff812915ad)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129b04c)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
```
```
In mm/mempolicy.c (ffffffff8129f01f)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
  - mm/mempolicy.c:queue_pages_pte_range
```
```
In mm/migrate.c (ffffffff812b5c34)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:pmd_migration_entry_wait
```
```
In mm/huge_memory.c (ffffffff812be47d)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:move_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/memcontrol.c (ffffffff812cc7df)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
  - mm/memcontrol.c:mem_cgroup_count_precharge_pte_range
```
```
In mm/memory-failure.c (ffffffff812d1876)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/hmm.c (ffffffff812dd28e)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_pmd
```
```
In fs/userfaultfd.c (ffffffff81342f49)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In fs/dax.c (ffffffff813523ae)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff81379b49)
Location: arch/x86/include/asm/pgtable.h:755
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
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
```
In lib/ioremap.c (ffffffff81ac72df)
Location: arch/x86/include/asm/pgtable.h:755
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_pud_range
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
</ul>
