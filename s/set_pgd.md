# Function: <code>set_pgd</code>

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
In arch/x86/xen/mmu.c (ffffffff81f62931)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_pagetable_init
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f6730d)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba2c)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81f779ea)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:remove_pagetable
```
```
In arch/x86/mm/fault.c (ffffffff8106a72b)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c991)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pgd_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7acaf)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In mm/memory.c (ffffffff811bd02a)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:__pud_alloc
```
```
In mm/pgtable-generic.c (ffffffff811d0391)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff8181f50a)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff816fb32b)
Location: arch/x86/include/asm/paravirt.h:593
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/xen/mmu.c (ffffffff81f8aac4)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f8f1a3)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105bb17)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81fa0124)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106a499)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c9f4)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
```
```
In arch/x86/mm/kaslr.c (ffffffff81896efb)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa381a)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff811da888)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811ed541)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81899bfc)
Location: arch/x86/include/asm/paravirt.h:566
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff817606eb)
Location: arch/x86/include/asm/paravirt.h:566
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
In arch/x86/xen/mmu.c (ffffffff81fc5eb2)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_pagetable_init
  - arch/x86/xen/mmu.c:xen_relocate_p2m
  - arch/x86/xen/mmu.c:xen_relocate_p2m
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81fca532)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ea91)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/mm/init_64.c (ffffffff81fdb68e)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106e039)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/pageattr.c (ffffffff81070634)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8107619b)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/kaslr.c (ffffffff818cb5e4)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81fdf164)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In mm/memory.c (ffffffff811ea3f8)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffffffff811f7931)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff818ce2ae)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178d84b)
Location: arch/x86/include/asm/paravirt.h:557
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/mmu.c (ffff80001143827c)
Location: arch/arm64/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:alloc_init_pud
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca1a8)
Location: arch/arm64/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_get_pud
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In mm/memory.c (ffff8000102f98c8)
Location: arch/arm64/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
```
In mm/pgtable-generic.c (ffff800010307ee8)
Location: arch/arm64/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:p4d_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/sparse-vmemmap.c (ffff800010da0fd4)
Location: arch/arm64/include/asm/pgtable.h:593
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
</details>
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
