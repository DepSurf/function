# Function: <code>__read_cr3</code>

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
In arch/x86/kernel/head64.c (ffffffff8209d45a)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff820a6560)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/process_64.c (ffffffff8102a495)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff8106df83)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff820bca26)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107cc95)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789f83)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/cpu.c (ffffffff817ab38b)
Location: arch/x86/include/asm/paravirt.h:64
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abadf)
Location: arch/x86/include/asm/paravirt.h:64
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
In arch/x86/kernel/head64.c (ffffffff826a32fa)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102562a)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff8102b1fd)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff81072f93)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3473)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8107aaeb)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083b92)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800475)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/cpu.c (ffffffff8182287e)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182306b)
Location: arch/x86/include/asm/paravirt.h:65
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
In arch/x86/kernel/head64.c (ffffffff826cc2f2)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81026367)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cf6a)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff81075948)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826ed6e5)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8107d89b)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff8186cabe)
Location: arch/x86/include/asm/paravirt.h:65
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d366)
Location: arch/x86/include/asm/paravirt.h:65
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
In arch/x86/kernel/head64.c (ffffffff828822fd)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81025f17)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff8102e1b8)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff8107b73a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a4277)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff810843cb)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff8188cace)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff8188f33f)
Location: arch/x86/include/asm/paravirt.h:127
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
In arch/x86/kernel/head64.c (ffffffff8289929a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81027c17)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ff41)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff8107f262)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc713)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8108804b)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff818d743e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff818d933f)
Location: arch/x86/include/asm/paravirt.h:127
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
In arch/x86/kernel/head64.c (ffffffff8289c29a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102854c)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff810308a1)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff810802f2)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2bba)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff81088d0b)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81909ace)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff8190b33f)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/kernel/head64.c (ffffffff82cc22af)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102a4a3)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81032ec8)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff81086dc2)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5f4e)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8108b36b)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81bba1fe)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc368)
Location: arch/x86/include/asm/paravirt.h:133
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
In arch/x86/kernel/head64.c (ffffffff82fae2ef)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bd2bff)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81bd30e5)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev-es.c (ffffffff810836a5)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81087442)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd38d4)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8108b42b)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81bcea73)
Location: arch/x86/include/asm/paravirt.h:133
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bd1348)
Location: arch/x86/include/asm/paravirt.h:133
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
In arch/x86/kernel/head64.c (ffffffff831b82ef)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81bc4dcb)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81bc54d5)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev.c (ffffffff81083c15)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810883d9)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff831de504)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8108bfbb)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81bc2423)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3388)
Location: arch/x86/include/asm/paravirt.h:148
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
In arch/x86/kernel/head64.c (ffffffff832982e7)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81c975a7)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81c980f5)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev.c (ffffffff81092db7)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff81097769)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff832c17a5)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff8109b77b)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81c92a8f)
Location: arch/x86/include/asm/paravirt.h:148
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81c94388)
Location: arch/x86/include/asm/paravirt.h:148
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
In arch/x86/kernel/head64.c (ffffffff834462e9)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff81e46a2f)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81e47594)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev.c (ffffffff810a52ee)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810aa298)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83473e55)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff810aec6b)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81e423d8)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff81e433b6)
Location: arch/x86/include/asm/paravirt.h:154
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
In arch/x86/kernel/head64.c (ffffffff83e5f3c0)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f8f5)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a1e7)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev.c (ffffffff810bda7c)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c3cf0)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff83e9bad0)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff810c8fdb)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff8201cda8)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8201e452)
Location: arch/x86/include/asm/paravirt.h:154
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
In arch/x86/xen/mmu_pv.c (ffffffff836906b5)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/head64.c (ffffffff836945f0)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a782)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev.c (ffffffff810c10ec)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810c7530)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff836bf570)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff810cc61b)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff8209d438)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff8209e452)
Location: arch/x86/include/asm/paravirt.h:154
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
In arch/x86/xen/mmu_pv.c (ffffffff838c0185)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/kernel/head64.c (ffffffff838c44e0)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/process_64.c (ffffffff810518d5)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/sev.c (ffffffff810c854c)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810cfa00)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff838f0010)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff810d4cab)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff82174c38)
Location: arch/x86/include/asm/paravirt.h:157
Inline: True
```
```
In arch/x86/power/hibernate.c (ffffffff82176452)
Location: arch/x86/include/asm/paravirt.h:157
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
In arch/x86/kernel/head64.c (ffffffff8288a29a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff810286ac)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81030a01)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff8107f2f2)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adb90)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff81087d0b)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff818a8e8e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff818ab33f)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/kernel/head64.c (ffffffff82888240)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/kernel/process_64.c (ffffffff8102048a)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff8106e2d4)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5e2e)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff81076978)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff81863628)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff81865341)
Location: arch/x86/include/asm/special_insns.h:167
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
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
In arch/x86/kernel/head64.c (ffffffff8289d29a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102850c)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff81030861)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff8107f2a2)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0a8f)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff81087cbb)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff818fa4ee)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff818fc33f)
Location: arch/x86/include/asm/paravirt.h:127
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
In arch/x86/kernel/head64.c (ffffffff8289d29a)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__early_make_pgtable
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8102919c)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:read_cr3_pa
```
```
In arch/x86/kernel/process_64.c (ffffffff810316f1)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/mm/fault.c (ffffffff81081392)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3bda)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
```
```
In arch/x86/mm/tlb.c (ffffffff81089eab)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
```
```
In arch/x86/power/cpu.c (ffffffff8191b64e)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
```
In arch/x86/power/hibernate.c (ffffffff8191d33f)
Location: arch/x86/include/asm/paravirt.h:127
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
</ul>

## Differences
