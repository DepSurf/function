# Function: <code>__flush_tlb_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81f7781a)
Location: arch/x86/include/asm/tlbflush.h:125
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107d51f)
Location: arch/x86/include/asm/tlbflush.h:125
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c515)
Location: arch/x86/include/asm/tlbflush.h:125
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810725b5)
Location: arch/x86/include/asm/tlbflush.h:125
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81079000)
Location: arch/x86/include/asm/tlbflush.h:125
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
**Symbols:**

```
ffffffff8107d51f-ffffffff8107d541: __flush_tlb_all (STB_LOCAL)
ffffffff81079000-ffffffff81079022: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81f9ff67)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107effc)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f301)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff810722a9)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a839)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738a82)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In arch/x86/power/hibernate_64.c (ffffffff817608eb)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107effc-ffffffff8107f019: __flush_tlb_all (STB_LOCAL)
ffffffff8107a4c0-ffffffff8107a4db: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81fdb4c9)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff810836ac)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81072f69)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff81075e06)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e6a5)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176bbaf)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178da4f)
Location: arch/x86/include/asm/tlbflush.h:189
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff810836ac-ffffffff810836cf: __flush_tlb_all (STB_LOCAL)
ffffffff8107e2a0-ffffffff8107e2c2: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff820bc34b)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8106ce9d)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pageattr.c (ffffffff810724d0)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff810748d6)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107ccb1)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789f9f)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abb75)
Location: arch/x86/include/asm/tlbflush.h:204
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106ce9d-ffffffff8106cec0: __flush_tlb_all (STB_LOCAL)
ffffffff8107c650-ffffffff8107c672: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff826c2d82)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81071bbc)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pageattr.c (ffffffff81077d54)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107a346)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c60f2)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083bae)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81800491)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182311e)
Location: arch/x86/include/asm/tlbflush.h:425
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81071bbc-ffffffff81071bdf: __flush_tlb_all (STB_LOCAL)
ffffffff81082d00-ffffffff81082d22: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff826ecf99)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff810748b2)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_pud_init
  - arch/x86/mm/init_64.c:phys_pud_init
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a828)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107d0e5)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efec6)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810878ff)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d404)
Location: arch/x86/include/asm/tlbflush.h:470
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff810748b2-ffffffff810748d5: __flush_tlb_all (STB_LOCAL)
ffffffff810878ff-ffffffff81087922: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828a3b2b)
Location: arch/x86/include/asm/tlbflush.h:458
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8107db05)
Location: arch/x86/include/asm/tlbflush.h:458
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff81083b25)
Location: arch/x86/include/asm/tlbflush.h:458
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6b83)
Location: arch/x86/include/asm/tlbflush.h:458
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108f055)
Location: arch/x86/include/asm/tlbflush.h:458
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3dd)
Location: arch/x86/include/asm/tlbflush.h:458
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8107d840-ffffffff8107d862: __flush_tlb_all (STB_LOCAL)
ffffffff8108f055-ffffffff8108f078: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828bbfca)
Location: arch/x86/include/asm/tlbflush.h:460
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084a72)
Location: arch/x86/include/asm/tlbflush.h:460
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810877d5)
Location: arch/x86/include/asm/tlbflush.h:460
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf236)
Location: arch/x86/include/asm/tlbflush.h:460
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092eb5)
Location: arch/x86/include/asm/tlbflush.h:460
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff818d93dd)
Location: arch/x86/include/asm/tlbflush.h:460
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81081140-ffffffff81081162: __flush_tlb_all (STB_LOCAL)
ffffffff81092eb5-ffffffff81092ed8: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828c2471)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81085772)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810884c5)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c56b1)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093f25)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3dd)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81082200-ffffffff81082222: __flush_tlb_all (STB_LOCAL)
ffffffff81093f25-ffffffff81093f48: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a985)
Location: arch/x86/mm/tlb.c:1167
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/pat/set_memory.c:__kernel_map_pages
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8108a950-ffffffff8108a977: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108abf5)
Location: arch/x86/mm/tlb.c:1103
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8108ac20-ffffffff8108ac47: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b715)
Location: arch/x86/mm/tlb.c:1147
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8108b740-ffffffff8108b767: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109acf5)
Location: arch/x86/mm/tlb.c:1206
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff8109ad20-ffffffff8109ad47: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae085)
Location: arch/x86/mm/tlb.c:1176
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810ae0e0-ffffffff810ae139: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8325)
Location: arch/x86/mm/tlb.c:1200
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/pat/set_memory.c:__cpa_flush_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810c8390-ffffffff810c83e9: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cba60)
Location: arch/x86/mm/tlb.c:1221
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810cba60-ffffffff810cbab2: __flush_tlb_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __flush_tlb_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d40f0)
Location: arch/x86/mm/tlb.c:1230
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/tlb.c:do_flush_tlb_all
  - arch/x86/mm/pat/set_memory.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pat/set_memory.c:kernel_map_pages_in_pgd
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810d40f0-ffffffff810d4142: __flush_tlb_all (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c0314018)
Location: arch/arm/include/asm/tlbflush.h:350
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:flush_tlb_all
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828ad447)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084772)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810874c5)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0649)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092ee5)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3dd)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81081200-ffffffff81081222: __flush_tlb_all (STB_LOCAL)
ffffffff81092ee5-ffffffff81092f08: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828a5709)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81073382)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff81076135)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a87ce)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81081965)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff81865426)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff81070150-ffffffff81070172: __flush_tlb_all (STB_LOCAL)
ffffffff81081965-ffffffff81081988: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828c0346)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084722)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff81087475)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3548)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092e95)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3dd)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810811b0-ffffffff810811d2: __flush_tlb_all (STB_LOCAL)
ffffffff81092e95-ffffffff81092eb8: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void __flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828c3491)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81086869)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
Direct callers:
  - arch/x86/mm/pageattr.c:kernel_unmap_pages_in_pgd
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810895a5)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c66ee)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810953e5)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3dd)
Location: arch/x86/include/asm/tlbflush.h:476
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
**Symbols:**

```
ffffffff810832d0-ffffffff810832f2: __flush_tlb_all (STB_LOCAL)
ffffffff810953e5-ffffffff81095408: __flush_tlb_all (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
