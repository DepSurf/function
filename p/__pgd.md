# Function: <code>__pgd</code>

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
In arch/x86/xen/mmu.c (ffffffff8101e2f0)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f672ff)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba17)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81f779d5)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c985)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
```
```
In mm/memory.c (ffffffff811bd01b)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:__pud_alloc
```
```
In mm/pgtable-generic.c (ffffffff811d0385)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8181f4f9)
Location: arch/x86/include/asm/paravirt.h:432
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
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
In arch/x86/xen/mmu.c (ffffffff81f8add6)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f8f19c)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb0a)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81fa0117)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c9ea)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81896ef1)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa3810)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811da87e)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed535)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81899bf2)
Location: arch/x86/include/asm/paravirt.h:405
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff817606cd)
Location: arch/x86/include/asm/paravirt.h:405
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
In arch/x86/xen/mmu.c (ffffffff81fc61c4)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81fca52b)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ea84)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81fdb681)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107062a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb5da)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf15a)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In mm/memory.c (ffffffff811ea3ee)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7925)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff818ce2a4)
Location: arch/x86/include/asm/paravirt.h:396
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d82d)
Location: arch/x86/include/asm/paravirt.h:396
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
In arch/x86/xen/mmu_pv.c (ffffffff820a7093)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff820aacd1)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e129)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff820bc6a2)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106fdee)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81076418)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81902bc4)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In mm/memory.c (ffffffff811f546f)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81202ab5)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8190572d)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff817ab9c5)
Location: arch/x86/include/asm/paravirt.h:404
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826a63f2)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826ad7f9)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826b1453)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061dfb)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff826c30dc)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810752a3)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107c669)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff8198cb0f)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff826c54b9)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8120e342)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8121b825)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8198f7a1)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81822f51)
Location: arch/x86/include/asm/paravirt.h:390
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff826cf58d)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff826d6af7)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826daafe)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064e99)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff826ed337)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81077f56)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f383)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff819e940c)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108337d)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8122ed31)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff8123d605)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff819ebfff)
Location: arch/x86/include/asm/paravirt.h:390
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d242)
Location: arch/x86/include/asm/paravirt.h:390
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828855ba)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8288ca40)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82890ee0)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ab09)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81a2489f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107e706)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81085f4d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a24d52)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff81089f2f)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812417c1)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff81251b55)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a2726d)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8188d0f2)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:399
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289c638)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a3ed6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828a844b)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e2c2)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a94bfb)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81081ff1)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089da6)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a950fb)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108dcdd)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81254141)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81263e26)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a97b1b)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818d7b22)
Location: arch/x86/include/asm/paravirt.h:399
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:399
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8289f628)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a6f76)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ab4ab)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f872)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81acc4db)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810830b1)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108aa16)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81acc9db)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108e93d)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812626a1)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81272696)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81acf3e9)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81909e62)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t __pgd(pgdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064a9)
Location: arch/x86/include/asm/paravirt.h:401
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026648)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ccf)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810852a1)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:401
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd30)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81094a04)
Location: arch/x86/include/asm/paravirt.h:401
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094b46)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff8128cd7c)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812a33b0)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff812d1753)
Location: arch/x86/include/asm/paravirt.h:401
Inline: False
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba772)
Location: arch/x86/include/asm/paravirt.h:401
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff810064a9-ffffffff810064b6: __pgd (STB_LOCAL)
ffffffff81025890-ffffffff8102589d: __pgd (STB_LOCAL)
ffffffff81085e36-ffffffff81085e43: __pgd (STB_LOCAL)
ffffffff81094a04-ffffffff81094a11: __pgd (STB_LOCAL)
ffffffff812d1753-ffffffff812d1760: __pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t __pgd(pgdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1ab2)
Location: arch/x86/include/asm/paravirt.h:382
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026da8)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810772ff)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086381)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cae2)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bda1ba)
Location: arch/x86/include/asm/paravirt.h:382
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81093f06)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff81296f3a)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81be8b4f)
Location: arch/x86/include/asm/paravirt.h:382
Inline: False
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bceea2)
Location: arch/x86/include/asm/paravirt.h:382
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81bd1ab2-ffffffff81bd1abf: __pgd (STB_LOCAL)
ffffffff81025fb0-ffffffff81025fbd: __pgd (STB_LOCAL)
ffffffff81bd87e8-ffffffff81bd87f5: __pgd (STB_LOCAL)
ffffffff81bda1ba-ffffffff81bda1c7: __pgd (STB_LOCAL)
ffffffff81be8b4f-ffffffff81be8b5c: __pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t __pgd(pgdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b53)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81029498)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077dbd)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8108712d)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d709)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bcc29a)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810948d0)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff8129cd19)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81bdab7b)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc285c)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81bc3b53-ffffffff81bc3b60: __pgd (STB_LOCAL)
ffffffff81bc4d56-ffffffff81bc4d63: __pgd (STB_LOCAL)
ffffffff81bca68f-ffffffff81bca69c: __pgd (STB_LOCAL)
ffffffff81bcc29a-ffffffff81bcc2a7: __pgd (STB_LOCAL)
ffffffff81bdab7b-ffffffff81bdab88: __pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t __pgd(pgdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94ba4)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102dc24)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810855cb)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8109644c)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cf92)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81ca22db)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a4829)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff812ddaf9)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81cc05f5)
Location: arch/x86/include/asm/paravirt.h:402
Inline: False
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92f1c)
Location: arch/x86/include/asm/paravirt.h:402
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81c94ba4-ffffffff81c94bb1: __pgd (STB_LOCAL)
ffffffff81c97532-ffffffff81c9753f: __pgd (STB_LOCAL)
ffffffff81c9fb35-ffffffff81c9fb42: __pgd (STB_LOCAL)
ffffffff81ca22db-ffffffff81ca22e8: __pgd (STB_LOCAL)
ffffffff81cc05f5-ffffffff81cc0602: __pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
pgd_t __pgd(pgdval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43e2d)
Location: arch/x86/include/asm/paravirt.h:408
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81032bb4)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8109599d)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8ce2)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b080b)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81e51976)
Location: arch/x86/include/asm/paravirt.h:408
Inline: False
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b90c0)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff81e6c50a)
Location: arch/x86/include/asm/paravirt.h:408
Inline: False
```
```
In mm/memory.c (ffffffff8133d636)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81e729e5)
Location: arch/x86/include/asm/paravirt.h:408
Inline: False
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e428b1)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81e43e2d-ffffffff81e43e3f: __pgd (STB_LOCAL)
ffffffff81031240-ffffffff81031252: __pgd (STB_LOCAL)
ffffffff810a7c50-ffffffff810a7c62: __pgd (STB_LOCAL)
ffffffff81e51976-ffffffff81e51988: __pgd (STB_LOCAL)
ffffffff81e6c50a-ffffffff81e6c51c: __pgd (STB_LOCAL)
ffffffff81e729e5-ffffffff81e729f7: __pgd (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64875)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e70bfb)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab5e2)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b4a0)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810caedb)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff820c78c0)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4a12)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff8139d3d6)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
```
```
In mm/memory.c (ffffffff813b52df)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff8141bcc6)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d2e4)
Location: arch/x86/include/asm/paravirt.h:408
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684ef5)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691a7b)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af1a2)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff836bef40)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce50b)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b94c)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d7f22)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff813d0506)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
```
```
In mm/memory.c (ffffffff813ea07f)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff8144f2c6)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d974)
Location: arch/x86/include/asm/paravirt.h:403
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4095)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c158b)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5d32)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff838ef9e0)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6beb)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e3fc)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e07a2)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff813faec6)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In mm/memory.c (ffffffff81415d8f)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488f46)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175174)
Location: arch/x86/include/asm/paravirt.h:404
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288d628)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82894f7f)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828994bd)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e812)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81a6b34b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810820b1)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff810899d6)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81a6b84b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8fd)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8125acf1)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff8126ace6)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a6e259)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818a9222)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:387
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a0628)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7f76)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac49d)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ecc2)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ad775b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81082061)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff81089986)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81ad7c5b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108d8ad)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81258a91)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81268a86)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81ada669)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff818fa882)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:387
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff828a062d)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff828a7f7c)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_setup_kernel_pagetable
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_pagetable_init
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4bb)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070f42)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81ae3c1b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81084181)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108bc26)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core
```
```
In arch/x86/mm/kaslr.c (ffffffff81ae411b)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8108fc8d)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff81268491)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff81278416)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6b1f)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8191b9e2)
Location: arch/x86/include/asm/paravirt.h:387
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:387
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
