# Function: <code>__flush_tlb</code>

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
In arch/x86/kernel/alternative.c (ffffffff81036876)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c08c)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051c8c)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/init.c (ffffffff81f7782f)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107d538)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106c525)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
```
```
In arch/x86/mm/tlb.c (ffffffff810725c1)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_current_task
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81079010)
Location: arch/x86/include/asm/paravirt.h:320
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
```
In mm/rmap.c (ffffffff811ca3c0)
Location: arch/x86/include/asm/paravirt.h:320
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
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
In arch/x86/kernel/alternative.c (ffffffff81035a69)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c1b9)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81051e14)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/init.c (ffffffff81f9ff90)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107f007)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f325)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff810729d5)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a854)
Location: arch/x86/include/asm/paravirt.h:310
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
In mm/rmap.c (ffffffff811e708b)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738a93)
Location: arch/x86/include/asm/paravirt.h:310
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
In arch/x86/power/hibernate_64.c (ffffffff81760933)
Location: arch/x86/include/asm/paravirt.h:310
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
In arch/x86/kernel/alternative.c (ffffffff81035786)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e609)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054711)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/init.c (ffffffff81fdb4df)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff810836c6)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff81072f75)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff81076586)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/tlb.c:flush_tlb_current_task
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e6b1)
Location: arch/x86/include/asm/paravirt.h:301
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
In mm/rmap.c (ffffffff811f8425)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_flush
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176bbbb)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff8178da5b)
Location: arch/x86/include/asm/paravirt.h:301
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
In arch/x86/kernel/alternative.c (ffffffff8103374c)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e579)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054063)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/init.c (ffffffff820bc361)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8106ceb7)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810724dc)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff810748e5)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107ccbd)
Location: arch/x86/include/asm/paravirt.h:301
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
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789fab)
Location: arch/x86/include/asm/paravirt.h:301
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff817abb85)
Location: arch/x86/include/asm/paravirt.h:301
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
In arch/x86/kernel/alternative.c (ffffffff81035aa3)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051ee9)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff826c2d98)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81071bd6)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__flush_tlb_all
```
```
In arch/x86/mm/pageattr.c (ffffffff81077d60)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107a355)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c6108)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083bba)
Location: arch/x86/include/asm/paravirt.h:293
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
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8180049d)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/hibernate_64.c (ffffffff8182312a)
Location: arch/x86/include/asm/paravirt.h:293
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
In arch/x86/kernel/alternative.c (ffffffff81036a1e)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054b95)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff826ecfaf)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff810748cc)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__flush_tlb_all
```
```
In arch/x86/mm/pageattr.c (ffffffff8107a834)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107d0fe)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efedc)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81087919)
Location: arch/x86/include/asm/paravirt.h:293
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate_64.c (ffffffff8186d423)
Location: arch/x86/include/asm/paravirt.h:293
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
In arch/x86/kernel/alternative.c (ffffffff81037c2c)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:text_poke
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81052255)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828a3b41)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8107db3b)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff81083b3e)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6b99)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108f06f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff8188f3e9)
Location: arch/x86/include/asm/paravirt.h:50
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055355)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828bbfe0)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084a9f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810877ee)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf24c)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092ecf)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff818d93e9)
Location: arch/x86/include/asm/paravirt.h:50
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c55)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828c2487)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8108579f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810884de)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c56c7)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093f3f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810951f7)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:bau_process_message
```
```
In arch/x86/power/hibernate.c (ffffffff8190b3e9)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810557d5)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828ad45d)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8108479f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810874de)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b065f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092eff)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff818ab3e9)
Location: arch/x86/include/asm/paravirt.h:50
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045915)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828a571f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81073397)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8107614e)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a87e4)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108197f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff8186543d)
Location: arch/x86/include/asm/paravirt.h:50
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c05)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828c035c)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8108474f)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff8108748e)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c355e)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81092eaf)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/power/hibernate.c (ffffffff818fc3e9)
Location: arch/x86/include/asm/paravirt.h:50
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
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810570a5)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/mm/init.c (ffffffff828c34a7)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81086895)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__kernel_map_pages
  - arch/x86/mm/pageattr.c:__cpa_flush_all
```
```
In arch/x86/mm/tlb.c (ffffffff810895be)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_flush_tlb_all
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6704)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810953ff)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:__flush_tlb_all
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810966b7)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:bau_process_message
```
```
In arch/x86/power/hibernate.c (ffffffff8191d3e9)
Location: arch/x86/include/asm/paravirt.h:50
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:relocate_restore_code
```
</details>
</li>
</ul>

## Differences
