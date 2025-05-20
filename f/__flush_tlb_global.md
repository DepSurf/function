# Function: <code>__flush_tlb_global</code>

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
In arch/x86/mm/init.c (ffffffff81f77826)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107d52f)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c52e)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810725d5)
Location: arch/x86/include/asm/paravirt.h:324
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81079019)
Location: arch/x86/include/asm/paravirt.h:324
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
In arch/x86/mm/init.c (ffffffff81f9ff6c)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107f010)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f306)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff810722ae)
Location: arch/x86/include/asm/paravirt.h:314
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a83e)
Location: arch/x86/include/asm/paravirt.h:314
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
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738a87)
Location: arch/x86/include/asm/paravirt.h:314
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
In arch/x86/power/hibernate_64.c (ffffffff817608f0)
Location: arch/x86/include/asm/paravirt.h:314
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
In arch/x86/mm/init.c (ffffffff81fdb4d6)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff810836bd)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81072f9e)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff81075e2a)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e6ef)
Location: arch/x86/include/asm/paravirt.h:305
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
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176bbf3)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178daa8)
Location: arch/x86/include/asm/paravirt.h:305
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
In arch/x86/mm/init.c (ffffffff820bc358)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8106ceae)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81072505)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff81074908)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107ccf3)
Location: arch/x86/include/asm/paravirt.h:305
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
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789fe3)
Location: arch/x86/include/asm/paravirt.h:305
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abc49)
Location: arch/x86/include/asm/paravirt.h:305
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
In arch/x86/mm/init.c (ffffffff826c2d8f)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81071bcd)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__flush_tlb_all
```
```
In arch/x86/mm/pageattr.c (ffffffff81077d85)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107a35e)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c60ff)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083bf0)
Location: arch/x86/include/asm/paravirt.h:297
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
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818004db)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182313d)
Location: arch/x86/include/asm/paravirt.h:297
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
In arch/x86/mm/init.c (ffffffff826ecfa6)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff810748c3)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__flush_tlb_all
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a853)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107d0f5)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efed3)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81087910)
Location: arch/x86/include/asm/paravirt.h:297
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d410)
Location: arch/x86/include/asm/paravirt.h:297
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
In arch/x86/mm/init.c (ffffffff828a3b38)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8107db19)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff81083b35)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6b90)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108f066)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3f5)
Location: arch/x86/include/asm/paravirt.h:55
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
In arch/x86/mm/init.c (ffffffff828bbfd7)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084a7e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810877e5)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf243)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092ec6)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff818d93f5)
Location: arch/x86/include/asm/paravirt.h:55
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
In arch/x86/mm/init.c (ffffffff828c247e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8108577e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810884d5)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c56be)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093f36)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3f5)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a995)
Location: arch/x86/include/asm/paravirt.h:61
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108ac05)
Location: arch/x86/include/asm/paravirt.h:61
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b725)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109ad05)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810ae095)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c8335)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cba6e)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d40fe)
Location: arch/x86/include/asm/paravirt.h:78
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
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
In arch/x86/mm/init.c (ffffffff828ad454)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8108477e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810874d5)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0656)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092ef6)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3f5)
Location: arch/x86/include/asm/paravirt.h:55
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
In arch/x86/mm/init.c (ffffffff828a5716)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8107338e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff81076145)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a87db)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81081976)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff81865432)
Location: arch/x86/include/asm/paravirt.h:55
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
In arch/x86/mm/init.c (ffffffff828c0353)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8108472e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff81087485)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3555)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092ea6)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3f5)
Location: arch/x86/include/asm/paravirt.h:55
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
In arch/x86/mm/init.c (ffffffff828c349e)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81086875)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810895b5)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c66fb)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810953f6)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3f5)
Location: arch/x86/include/asm/paravirt.h:55
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
</ul>

## Differences
