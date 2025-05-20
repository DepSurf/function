# Function: <code>p4d_pfn_mask</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/fault.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/mm/kaslr.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/gup.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/mremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/page_vma_mapped.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/pagewalk.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/vmalloc.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/hugetlb.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
Inline: True
```
```
In lib/ioremap.c (0)
Location: arch/x86/include/asm/pgtable_types.h:338
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6418)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad49e)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826b43a6)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e19)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810717c1)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81072151)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c34aa)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107765c)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c627)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff8198ca83)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81080260)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:p4d_page_vaddr
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81082ccb)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
```
```
In mm/gup.c (ffffffff8120546b)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812087a1)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81217c89)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81218f11)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8121a841)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8121af49)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
```
```
In mm/rmap.c (ffffffff8121c779)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8121f6e7)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81228c94)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
```
```
In mm/hugetlb.c (ffffffff81232b99)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8198f62e)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff81249f51)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
```
```
In mm/huge_memory.c (ffffffff8125438f)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/userfaultfd.c (ffffffff8126b107)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812c819d)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (ffffffff818230b2)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In lib/ioremap.c (ffffffff81973445)
Location: arch/x86/include/asm/pgtable_types.h:363
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf5b7)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81021a53)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff826ddb9e)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064e5c)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff810744c1)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810751ce)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:spurious_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed720)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a0cc)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f397)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff819e939c)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff810833aa)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f016a)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810864f1)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff81226906)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812297da)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81239aa6)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection
  - mm/mprotect.c:change_protection
```
```
In mm/mremap.c (ffffffff8123a8e8)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8123c522)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8123ce53)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
```
```
In mm/rmap.c (ffffffff8123e569)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81240e67)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81249faa)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81255c22)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff819ebebe)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8126eecf)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
```
```
In mm/huge_memory.c (ffffffff81278230)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812889e3)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff8128fb05)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff812f155c)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/include/asm/pgtable_types.h:362
Inline: True
```
```
In lib/ioremap.c (ffffffff819cf96a)
Location: arch/x86/include/asm/pgtable_types.h:362
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828855e4)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810211f5)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff82893fe6)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106aacc)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8107a3b1)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107afce)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a42b2)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810808ac)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085f61)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24ce2)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81089f5b)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e72)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d381)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff812399e1)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8123ccea)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff8124d3c4)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8124eaeb)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81250938)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81251306)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81252af9)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81254b77)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8125e5ea)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8126a072)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a2712c)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8128357f)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c870)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8129d6e3)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812a4a25)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81305f1c)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
```
```
In lib/ioremap.c (ffffffff81a08db8)
Location: arch/x86/include/asm/pgtable_types.h:386
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c662)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81022d5f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ab794)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e286)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e0f2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e953)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc75c)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810843ac)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810899eb)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81a950b2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dd0a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf52a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109122f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff8124ac0e)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8124e955)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8125fbc3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81260e40)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81262c18)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812635a8)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81264e79)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81266f27)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8127b819)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff812851a5)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a979d3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/huge_memory.c (ffffffff812a7553)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b8a22)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812bffe4)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813274af)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In lib/ioremap.c (ffffffff81a78b5d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f652)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102369f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828ae7a2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f836)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107f182)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107f9e3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2c03)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810850ec)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108a65b)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc992)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e96a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c59a5)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81091f6f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff812590fe)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff8125cef2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8126e483)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8126f5d9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812713c8)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81272070)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81273709)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81275827)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff8128b2f9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff81294d45)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81acf2a1)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812af001)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b89f3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812ca902)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d1f34)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133a28f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In lib/ioremap.c (ffffffff81aaff0d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b40)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026480)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff810479f8)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d37)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81085afb)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81086bd0)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5fd4)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108c68f)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc51ff)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094cba)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8c85)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097bb8)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec21a)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:p4d_page_vaddr
```
```
In mm/gup.c (ffffffff812892ce)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8128d524)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8129ee6d)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff8129faf6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pmd
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1d5e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2c91)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812a48e1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812a7236)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/swapfile.c (ffffffff812bdcea)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c8380)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7c5e)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812e50a1)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ed5a6)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81300746)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81307d26)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813722de)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
```
```
In lib/ioremap.c (ffffffff815e9deb)
Location: arch/x86/include/asm/pgtable_types.h:409
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
  - lib/ioremap.c:ioremap_pud_range
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:409
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1434)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026b7f)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4c7e)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077367)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086bc1)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810884b0)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd395a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cc3f)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e0d2)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff8109407a)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd670b)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096d7c)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8123ca95)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81292fae)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8129f9d5)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812aa22d)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812aaf86)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad589)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae5b1)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812b0071)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b24b6)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
```
```
In mm/ioremap.c (ffffffff812b8362)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/swapfile.c (ffffffff812c980e)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_p4d_range
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f50)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c40989)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f0464)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f8cc6)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130c8e6)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81313a56)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8138012e)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:410
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb5bf)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81028eb0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc70d5)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077df5)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81087873)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff81089134)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de554)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d831)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c303e7)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094a1b)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e115f)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097610)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff81243daa)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8129a708)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a5250)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812af67a)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812b03bf)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b272f)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3982)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812b5669)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b8b92)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff812d047e)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae39)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81c3295f)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812f6776)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ff218)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff81313056)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff81319bfd)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813874b7)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329baea)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102d607)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085603)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8109681f)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff8109858d)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c182a)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109ca2a)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4eba5)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff832c49e8)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810a75f3)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff8127e71d)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812db0c9)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e67ad)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff812f0eaa)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812f1c01)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f4359)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f5502)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff812f72fb)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812fb144)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813159c9)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e6f)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8132bfca)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_remap_range
```
```
In mm/migrate.c (ffffffff81340dc0)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
```
```
In mm/huge_memory.c (ffffffff81348e1d)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8135fb2a)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813669aa)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff813d478d)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:406
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a2e1)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8103246c)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810959d3)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a9148)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810ab1e9)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473ed8)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0234)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1e9fb)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83477411)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810bc96d)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In kernel/events/core.c (ffffffff812d338e)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In mm/gup.c (ffffffff8133ac80)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff8133d79b)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81354a1e)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813557c6)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81358346)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813593a9)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff8135c916)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff81362649)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81380f56)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f09b)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff8139bb1a)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In mm/migrate_device.c (ffffffff813b7c9f)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bf28f)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff813da763)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff813e3d39)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8145fc39)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:408
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e648f7)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e704b5)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81067ea3)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab618)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c2a6d)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c358c)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bb33)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cb012)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff820c7828)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4b98)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea08de)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810d7e87)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8133b604)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff8137fdcf)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff83ebc883)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813b2a10)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813b67bb)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff813cef7c)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff813cff36)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d2978)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3c79)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff813d6ff6)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff813ddfdf)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff813ff7d4)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140db91)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff814140a3)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff820cb048)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8143995e)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
```
```
In mm/memory-failure.c (ffffffff81460989)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
```
```
In mm/userfaultfd.c (ffffffff8146b759)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff814ef522)
Location: arch/x86/include/asm/pgtable_types.h:387
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e4ac)
Location: arch/x86/include/asm/pgtable_types.h:387
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f77)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691335)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81069753)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af1d8)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810c614d)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810c6ddc)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf5d3)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce642)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b8b8)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d80a8)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4aa0)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810e3418)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff8136cfe2)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813b12e3)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff836e4f03)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff813e74f7)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_p4d_mask
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813eb1d9)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81403642)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff814049f9)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff814076b8)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81408649)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff8140bef9)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8141283f)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff81432800)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81440f44)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447603)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_should_optimize
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse-vmemmap.c (ffffffff8214f2d8)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8146e706)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
```
```
In mm/memory-failure.c (ffffffff8149515c)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814a055c)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81524ce9)
Location: arch/x86/include/asm/pgtable_types.h:388
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e4ac)
Location: arch/x86/include/asm/pgtable_types.h:388
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4117)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0e45)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c93)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5d68)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810ce59d)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/fault.c (ffffffff810cf29c)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f0073)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6d22)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:populate_pud
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e368)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e0928)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f56a0)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810ebc68)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/events/core.c (ffffffff81396222)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/vmscan.c (ffffffff813da863)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pud_range
```
```
In mm/percpu.c (ffffffff83917714)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/gup.c (ffffffff8141217c)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff81415202)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:apply_to_pud_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff8142fbc2)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff81430fc9)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81433d46)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81434d69)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/rmap.c (ffffffff81438799)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8143f2af)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:vmap_range_noflush
```
```
In mm/swapfile.c (ffffffff8146bc20)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8147b074)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff822321a8)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:compound_section_tail_page
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate_device.c (ffffffff8149d17a)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/memory-failure.c (ffffffff814c4ac4)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
```
```
In mm/userfaultfd.c (ffffffff814cfbfc)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8155897a)
Location: arch/x86/include/asm/pgtable_types.h:416
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff821764ac)
Location: arch/x86/include/asm/pgtable_types.h:416
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d652)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810237ff)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff8289c7c1)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e7d6)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e182)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e9e3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adbd9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810840ec)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108961b)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b802)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d92a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b093d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090f2f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff8125174e)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81255542)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81266ad3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81267c29)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81269a18)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8126a6c0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8126bd59)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126de77)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812838d9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128d325)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e111)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a75e1)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b0fd3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c2ee2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812ca514)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133286f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In lib/ioremap.c (ffffffff81a4ed5d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b5ba)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/tboot.c (ffffffff8289498b)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee95)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff8106d389)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106dd85)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e3f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff81070c20)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_address_in_pgd
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d30)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c400)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8ac2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107f993)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/gup.c (ffffffff81244615)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81247c96)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/mprotect.c (ffffffff81258954)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81259f8f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff8125bde0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff8125c5b3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff8125de04)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8125fe99)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81275792)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8127f105)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a5a5)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff8129902a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a23d3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812b3fed)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
```
In mm/userfaultfd.c (ffffffff812bb54a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8132343a)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (ffffffff81865353)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
```
In lib/ioremap.c (ffffffff81a0be5d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0652)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102365f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af784)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ec86)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8107e132)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107e993)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0ad8)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff8108409c)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810895cb)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7c12)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8da)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c383c)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81090edf)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff8124f4ee)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff812532e2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81264873)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff812659c9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff812677b8)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81268460)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81269af9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8126bc17)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff812816e9)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8128b135)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ada521)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812a53f1)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aede3)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812c0cf2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812c8324)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff8133033f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In lib/ioremap.c (ffffffff81abb14d)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0657)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81023b0f)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
```
```
In arch/x86/kernel/tboot.c (ffffffff828af7b2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_late_init
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f06)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81080222)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81080a83)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3c23)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/pageattr.c (ffffffff810861dc)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:lookup_pmd_address
  - arch/x86/mm/pageattr.c:lookup_pmd_address
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108b86b)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:walk_pud_level
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae40d2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fcba)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69e2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810932cf)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/gup.c (ffffffff8125ee5e)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (ffffffff81262cf2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__pud_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pud_range
```
```
In mm/mprotect.c (ffffffff81274233)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff8127536b)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/page_vma_mapped.c (ffffffff81277152)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81277de0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
```
```
In mm/rmap.c (ffffffff81279469)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff8127b627)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/vmalloc.c:vmalloc_to_page
```
```
In mm/swapfile.c (ffffffff81291424)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:try_to_unuse
```
```
In mm/hugetlb.c (ffffffff8129af55)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/sparse-vmemmap.c (ffffffff81ae69d7)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
```
```
In mm/migrate.c (ffffffff812b4b21)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bf133)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff812d17b2)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/userfaultfd.c (ffffffff812d9034)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In fs/userfaultfd.c (ffffffff81342c96)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
  - fs/userfaultfd.c:handle_userfault
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
```
```
In lib/ioremap.c (ffffffff81ac758b)
Location: arch/x86/include/asm/pgtable_types.h:385
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
  - lib/ioremap.c:ioremap_pud_range
```
</details>
</li>
</ul>

## Differences
