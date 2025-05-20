# Function: <code>set_p4d</code>

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
In arch/x86/xen/mmu_pv.c (ffffffff820a6f19)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff820aacd8)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e133)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff820bc6af)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106d57c)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fdf8)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
```
```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81902bce)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff820bfed0)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff811f5479)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202ac1)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81905737)
Location: arch/x86/include/asm/paravirt.h:581
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab9e3)
Location: arch/x86/include/asm/paravirt.h:581
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a6403)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad680)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81031f08)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826b145a)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061e05)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff826c30e6)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81072587)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810752ad)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8107a747)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff8198cb16)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff826c54c3)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826c8070)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8120e34c)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b831)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8198f7ab)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822f6f)
Location: arch/x86/include/asm/paravirt.h:545
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf59b)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6984)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff810331b5)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826dab1d)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064eb1)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff826ed355)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81075146)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81077f74)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8107d4c5)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff819e942c)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81083395)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2664)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8122ed4f)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d611)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff819ec017)
Location: arch/x86/include/asm/paravirt.h:545
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d259)
Location: arch/x86/include/asm/paravirt.h:545
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828855c8)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288c8cd)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81034575)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82890eff)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab21)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a2490b)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107af46)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e724)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81083fa3)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24d72)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81089f47)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a8f70)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812417df)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251b61)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a27285)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d109)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:529
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c646)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3d67)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff810362f9)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828a846a)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e2da)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94c93)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fe41)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108200d)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087c27)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81a9511b)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dcf5)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c159a)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81254159)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81263e32)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a97b33)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7b39)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:530
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f636)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6e01)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036c14)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ab4ca)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f88a)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc573)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81080ed1)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810830cd)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810888e7)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc9fb)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e955)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7a19)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812626b9)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812726a2)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81acf401)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909e79)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064d0)
Location: arch/x86/include/asm/paravirt.h:532
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a489)
Location: arch/x86/include/asm/paravirt.h:532
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103857d)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd07d4)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107702b)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81084d10)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/fault.c (ffffffff8108803f)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:532
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108ab1e)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ce57)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81094a11)
Location: arch/x86/include/asm/paravirt.h:532
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094ca5)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec1d0)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/memory.c (ffffffff812925b9)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812a3432)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff812d1760)
Location: arch/x86/include/asm/paravirt.h:532
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba7f8)
Location: arch/x86/include/asm/paravirt.h:532
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:532
Inline: False
```
**Symbols:**

```
ffffffff810064d0-ffffffff810064dd: set_p4d (STB_LOCAL)
ffffffff8102a489-ffffffff8102a496: set_p4d (STB_LOCAL)
ffffffff81085eca-ffffffff81085ed7: set_p4d (STB_LOCAL)
ffffffff81094a11-ffffffff81094a1e: set_p4d (STB_LOCAL)
ffffffff812d1760-ffffffff812d176d: set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1ad9)
Location: arch/x86/include/asm/paravirt.h:454
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2be5)
Location: arch/x86/include/asm/paravirt.h:454
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81038f2d)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc614)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107765b)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086220)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:454
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cc15)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bda1c7)
Location: arch/x86/include/asm/paravirt.h:454
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094065)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff8129ce69)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812aed36)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81be8b5c)
Location: arch/x86/include/asm/paravirt.h:454
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcef28)
Location: arch/x86/include/asm/paravirt.h:454
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:454
Inline: False
```
**Symbols:**

```
ffffffff81bd1ad9-ffffffff81bd1ae6: set_p4d (STB_LOCAL)
ffffffff81bd2be5-ffffffff81bd2bf2: set_p4d (STB_LOCAL)
ffffffff81bd885d-ffffffff81bd886a: set_p4d (STB_LOCAL)
ffffffff81bda1c7-ffffffff81bda1d4: set_p4d (STB_LOCAL)
ffffffff81be8b5c-ffffffff81be8b69: set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b7a)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4db1)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103aa24)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bc60ac)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810780e6)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086d32)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d807)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bcc2a7)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094a06)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff812a254a)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812b4266)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81bdab88)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc28e6)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
```
**Symbols:**

```
ffffffff81bc3b7a-ffffffff81bc3b87: set_p4d (STB_LOCAL)
ffffffff81bc4db1-ffffffff81bc4dbe: set_p4d (STB_LOCAL)
ffffffff81bca704-ffffffff81bca711: set_p4d (STB_LOCAL)
ffffffff81bcc2a7-ffffffff81bcc2b4: set_p4d (STB_LOCAL)
ffffffff81bdab88-ffffffff81bdab95: set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94bcb)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c9758d)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81040426)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81c9907d)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810858fb)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096042)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109d090)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81ca22e8)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a4976)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff812e38ba)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812f5e46)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81cc0602)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92f32)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
```
**Symbols:**

```
ffffffff81c94bcb-ffffffff81c94bd8: set_p4d (STB_LOCAL)
ffffffff81c9758d-ffffffff81c9759a: set_p4d (STB_LOCAL)
ffffffff81c9fbaa-ffffffff81c9fbb7: set_p4d (STB_LOCAL)
ffffffff81ca22e8-ffffffff81ca22f5: set_p4d (STB_LOCAL)
ffffffff81cc0602-ffffffff81cc060f: set_p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43e63)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e469e3)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81047d62)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81e48648)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095cdc)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a88c7)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b091e)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81e51988)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b9214)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff81e6c51c)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81344c5a)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff81359da4)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81e729f7)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e428c6)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
```
**Symbols:**

```
ffffffff81e43e63-ffffffff81e43e89: set_p4d (STB_LOCAL)
ffffffff81e469e3-ffffffff81e46a09: set_p4d (STB_LOCAL)
ffffffff810a7da0-ffffffff810a7dc6: set_p4d (STB_LOCAL)
ffffffff81e51988-ffffffff81e519ae: set_p4d (STB_LOCAL)
ffffffff81e6c51c-ffffffff81e6c542: set_p4d (STB_LOCAL)
ffffffff81e729f7-ffffffff81e72a1d: set_p4d (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e649d6)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e706a6)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81052a21)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810566ec)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab92b)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c5f14)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cafeb)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff820c7962)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4b83)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff83ebc86d)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813bce77)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff813d47a4)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff820cb885)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d390)
Location: arch/x86/include/asm/paravirt.h:488
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:488
Inline: False
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83685056)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691520)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8105399f)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810576bc)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af4ef)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff82149f74)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:483
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce61b)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b924)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d8093)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff836e4eed)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813f1bad)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff81409174)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8214fb15)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209da20)
Location: arch/x86/include/asm/paravirt.h:483
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:483
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void set_p4d(p4d_t *p4dp, p4d_t p4d);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b41f6)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c1030)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8105abbf)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/espfix_64.c (ffffffff838c6ea2)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b607f)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222ca24)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6cfb)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e3d4)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e0913)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff813f912b)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
```
```
In mm/memory.c (ffffffff81417684)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - mm/memory.c:free_pud_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:p4d_populate
Direct callers:
  - mm/memory.c:free_p4d_range
```
```
In mm/pgtable-generic.c (ffffffff81435964)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81488e9b)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175220)
Location: arch/x86/include/asm/paravirt.h:482
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:482
Inline: False
```
**Symbols:**

```
ffffffff81414100-ffffffff81414126: set_p4d (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d636)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894e0a)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036d74)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828994dc)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e82a)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b3e3)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fed1)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff810820cd)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810878e7)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b86b)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d915)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b29b1)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff8125ad09)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff8126acf2)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e271)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a9239)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0636)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7e01)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81036bd4)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4bc)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ecda)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad77f3)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8107fe81)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108207d)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81087897)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7c7b)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8c5)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c58b0)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff81258aa9)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81268a92)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81ada681)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa899)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:518
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a063b)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7e07)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81037ad2)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4da)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f5a)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3cb3)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81081f71)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8108419d)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff81089a03)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae413b)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fca5)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8a56)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff812684a9)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81278422)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6b37)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b9f9)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:518
Inline: True
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
