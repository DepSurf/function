# Function: <code>__p4d</code>

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
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4d_t __p4d(p4dval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5b1e)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccd094)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd07bc)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076d73)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81084cf8)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:free_pud_table
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cdd0)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc5263)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff81094c8d)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812925a1)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pud_range
```
```
In mm/pgtable-generic.c (ffffffff812a3426)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7de8)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba746)
Location: arch/x86/include/asm/paravirt.h:541
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:541
Inline: False
```
**Symbols:**

```
ffffffff81085ed7-ffffffff81085ee4: __p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4d_t __p4d(p4dval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1412)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8ed0)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc5fc)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810773a3)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086208)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cb82)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e136)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff8109404d)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff8129ce51)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c40b13)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bcee76)
Location: arch/x86/include/asm/paravirt.h:463
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:463
Inline: False
```
**Symbols:**

```
ffffffff81bd886a-ffffffff81bd8877: __p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4d_t __p4d(p4dval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb59d)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c350c)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81bc6093)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077e31)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81086d18)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d772)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3044d)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810949ed)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812a2531)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81c32a75)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc282f)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:491
Inline: False
```
**Symbols:**

```
ffffffff81bca711-ffffffff81bca71e: __p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4d_t __p4d(p4dval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329bac8)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a3f46)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81c99064)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8108563f)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff81096028)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cffb)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4ec0b)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810a495d)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/memory.c (ffffffff812e38a1)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81d51445)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92eef)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:491
Inline: False
```
**Symbols:**

```
ffffffff81c9fbb7-ffffffff81c9fbc4: __p4d (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
p4d_t __p4d(p4dval_t val);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a2c1)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff834531e3)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81e48630)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095a0f)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff810a88ae)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
Direct callers:
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b0872)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1ea61)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810b91fd)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff8348b951)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff81344c42)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81f216d8)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e42886)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:497
Inline: False
```
**Symbols:**

```
ffffffff810a7dd0-ffffffff810a7de2: __p4d (STB_LOCAL)
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e648d5)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e7069e)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810566d7)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab654)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff820c715d)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810caf42)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff820c787f)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d4b6f)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff83ebc857)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813bce62)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff820cb870)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d2b9)
Location: arch/x86/include/asm/paravirt.h:497
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:497
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684f55)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83691518)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810576a7)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af214)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8214b1cd)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce572)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b90f)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810d807f)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff836e4ed7)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_pte
```
```
In mm/memory.c (ffffffff813f1b98)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8214fb00)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d949)
Location: arch/x86/include/asm/paravirt.h:492
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:492
Inline: False
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b40f5)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c1028)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d
```
```
In arch/x86/kernel/espfix_64.c (ffffffff838c6e8d)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5da4)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/mm/init_64.c (ffffffff8222dc7d)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:ident_p4d_init
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6c52)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e3bf)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
```
```
In arch/x86/mm/pti.c (ffffffff810e08ff)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In mm/percpu.c (ffffffff813f9116)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
```
```
In mm/memory.c (ffffffff814150ff)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - mm/memory.c:p4d_populate
```
```
In mm/sparse-vmemmap.c (ffffffff81488e86)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
```
```
In arch/x86/power/hibernate_64.c (ffffffff82175149)
Location: arch/x86/include/asm/paravirt.h:491
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/paravirt.h:491
Inline: False
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
