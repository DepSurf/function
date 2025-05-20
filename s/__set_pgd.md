# Function: <code>__set_pgd</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5acc)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a496)
Location: arch/x86/include/asm/paravirt.h:553
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81038567)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076ce7)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81084e91)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/fault.c (ffffffff81087d8f)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:553
Inline: False
```
```
In arch/x86/mm/tlb.c (ffffffff8108ab39)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd48)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81094a1e)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094b5e)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec1dc)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
```
```
In mm/memory.c (ffffffff8128cd88)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812a33bc)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff812d1819)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba7a9)
Location: arch/x86/include/asm/paravirt.h:553
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff8102a496-ffffffff8102a4a3: __set_pgd (STB_LOCAL)
ffffffff81085ef1-ffffffff81085efe: __set_pgd (STB_LOCAL)
ffffffff81094a1e-ffffffff81094a35: __set_pgd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb13c6)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2bf2)
Location: arch/x86/include/asm/paravirt.h:475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81038f17)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077317)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086424)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:475
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cafa)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bda1d4)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81093f1e)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff812985dd)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812aecd0)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81be8c0a)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bceed9)
Location: arch/x86/include/asm/paravirt.h:475
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81bd2bf2-ffffffff81bd2bff: __set_pgd (STB_LOCAL)
ffffffff81bd8884-ffffffff81bd8891: __set_pgd (STB_LOCAL)
ffffffff81bda1d4-ffffffff81bda1eb: __set_pgd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb551)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4dbe)
Location: arch/x86/include/asm/paravirt.h:506
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8103aa0e)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077dd6)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810871ba)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:506
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d722)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bcc2fb)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810948e9)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff8129d43e)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812b4207)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81bdac36)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc2893)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81bc4dbe-ffffffff81bc4dcb: __set_pgd (STB_LOCAL)
ffffffff81bca72b-ffffffff81bca738: __set_pgd (STB_LOCAL)
ffffffff81bcc2fb-ffffffff81bcc312: __set_pgd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329ba7c)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c9759a)
Location: arch/x86/include/asm/paravirt.h:506
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81040409)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810855e4)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810964d8)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:506
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cfab)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81ca233c)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a4842)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/memory.c (ffffffff812de890)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff812f5de7)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81cc06d1)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92f69)
Location: arch/x86/include/asm/paravirt.h:506
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81c9759a-ffffffff81c975a7: __set_pgd (STB_LOCAL)
ffffffff81c9fbd1-ffffffff81c9fbde: __set_pgd (STB_LOCAL)
ffffffff81ca233c-ffffffff81ca2353: __set_pgd.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __set_pgd(pgd_t *pgdp, pgd_t pgd);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a276)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e46a09)
Location: arch/x86/include/asm/paravirt.h:512
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81047d2c)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810959b5)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a8d39)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
Direct callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:512
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0823)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81e51a0c)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Direct callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b90d8)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff81e6c734)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
```
```
In mm/memory.c (ffffffff8133e97b)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff81359d0e)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81e72ade)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e428fc)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
**Symbols:**

```
ffffffff81e46a09-ffffffff81e46a2f: __set_pgd (STB_LOCAL)
ffffffff810a7e10-ffffffff810a7e36: __set_pgd (STB_LOCAL)
ffffffff81e51a0c-ffffffff81e51a3c: __set_pgd.constprop.0 (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64882)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e7014f)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff81052a0c)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab5f7)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b4b5)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:512
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810caef0)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff820c78d5)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4a27)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff8139d3ea)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
```
```
In mm/memory.c (ffffffff813b59eb)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff813d46fe)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8141bcda)
Location: arch/x86/include/asm/paravirt.h:512
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d333)
Location: arch/x86/include/asm/paravirt.h:512
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f02)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83690fcf)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8105398a)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af1b7)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff836bef55)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:507
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce520)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810d7f37)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff813d051a)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
```
```
In mm/memory.c (ffffffff813eb09b)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff814090ce)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8144f2da)
Location: arch/x86/include/asm/paravirt.h:507
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d9c3)
Location: arch/x86/include/asm/paravirt.h:507
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b40a2)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c0adf)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/ldt.c (ffffffff8105abaa)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5d47)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff838ef9f5)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/pgtable.c (0)
Location: arch/x86/include/asm/paravirt.h:505
Inline: False
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6c00)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/pti.c (ffffffff810e07b7)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In mm/percpu.c (ffffffff813faeda)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
```
```
In mm/memory.c (ffffffff8141789b)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
```
```
In mm/pgtable-generic.c (ffffffff814358be)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81488f5a)
Location: arch/x86/include/asm/paravirt.h:505
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff821751c3)
Location: arch/x86/include/asm/paravirt.h:505
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
