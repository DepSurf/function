# Function: <code>write_cr3</code>

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
In arch/x86/kernel/head64.c (ffffffff81f59252)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/mmu.c (ffffffff8101e481)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102b414)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e169)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff81050410)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff81f77810)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8107253a)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81079137)
Location: arch/x86/include/asm/paravirt.h:84
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
In kernel/sched/core.c (ffffffff8181fc65)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afc91)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff812137bd)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff816fb0ca)
Location: arch/x86/include/asm/paravirt.h:84
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff81f811f2)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/mmu.c (ffffffff8102089a)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102a070)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8103df87)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff81050593)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff81f9ff60)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81072478)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a824)
Location: arch/x86/include/asm/paravirt.h:74
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
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738a6d)
Location: arch/x86/include/asm/paravirt.h:74
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
In arch/x86/power/cpu.c (ffffffff8176032a)
Location: arch/x86/include/asm/paravirt.h:74
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff81fbd1f2)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/mmu.c (ffffffff81020ffe)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/xen/mmu.c:xen_exit_mmap
```
```
In arch/x86/xen/smp.c (ffffffff8102a7c0)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:stop_self
  - arch/x86/xen/smp.c:xen_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8103d83b)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff81052e03)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff81fdb4c2)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81076009)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e690)
Location: arch/x86/include/asm/paravirt.h:69
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
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8176bb9a)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/cpu.c (ffffffff8178d32a)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff8209d1f2)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff810292e0)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8103b89d)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052913)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff820bc344)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81074708)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107cc9c)
Location: arch/x86/include/asm/paravirt.h:69
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
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81789f8a)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/cpu.c (ffffffff817ab4a7)
Location: arch/x86/include/asm/paravirt.h:69
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff826a3208)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102954f)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8103e2bd)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:tboot_shutdown
```
```
In arch/x86/kernel/reboot.c (ffffffff810564d1)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff826c2d7b)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8107ab63)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083b99)
Location: arch/x86/include/asm/paravirt.h:70
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
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8180047c)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In arch/x86/power/cpu.c (ffffffff818229a7)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff826cc1fe)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff81029fb5)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8103f84a)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81059277)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff826ecf88)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8107d913)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff8186cbc7)
Location: arch/x86/include/asm/paravirt.h:70
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff828821fe)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a595)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff81040e4a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8105ef77)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828a3b1a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81084443)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff8188cbd7)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff828991fe)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c36d)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8104353a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062387)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828bbfb9)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810880e9)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff818d76b9)
Location: arch/x86/include/asm/paravirt.h:132
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
In arch/x86/kernel/head64.c (ffffffff8289c1fe)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cd0d)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff81043c8a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062bf7)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828c2460)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81088d83)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81909719)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff82cc21fe)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ecf5)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8104760f)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81068c97)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff82ce579b)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8108b3f2)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81bba2cb)
Location: arch/x86/include/asm/paravirt.h:138
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
In arch/x86/kernel/head64.c (ffffffff82fae23e)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fb05)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff81046e3f)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8106a8c9)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff82fd2ff1)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8108b4b2)
Location: arch/x86/include/asm/paravirt.h:138
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81bceb3b)
Location: arch/x86/include/asm/paravirt.h:138
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
In arch/x86/kernel/head64.c (ffffffff831b823e)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff810305ed)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff810487e5)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b427)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff831ddc35)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8108c043)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81bc24eb)
Location: arch/x86/include/asm/paravirt.h:154
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
In arch/x86/kernel/head64.c (ffffffff8329823e)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103546f)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/realmode/init.c (ffffffff81039a88)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/tboot.c (ffffffff8104f12e)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff832c0e9d)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff8109b803)
Location: arch/x86/include/asm/paravirt.h:154
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81c92b79)
Location: arch/x86/include/asm/paravirt.h:154
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
In arch/x86/kernel/head64.c (ffffffff8344621d)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b3df)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/realmode/init.c (ffffffff810409e7)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/tboot.c (ffffffff8105a39e)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff8347348c)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810aecf2)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81e424e7)
Location: arch/x86/include/asm/paravirt.h:160
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
In arch/x86/kernel/head64.c (ffffffff83e5f22a)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043b9f)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/realmode/init.c (ffffffff81049d17)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/tboot.c (ffffffff8106814e)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff83e9ac29)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810c9062)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff8201cec7)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
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
In arch/x86/xen/smp_pv.c (ffffffff81043cbf)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/realmode/init.c (ffffffff81049f47)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/head64.c (ffffffff8369446a)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a788)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/tboot.c (ffffffff810699cd)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff836be621)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810cc6d3)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8209d557)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
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
In arch/x86/xen/smp_pv.c (ffffffff8104a1bf)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/realmode/init.c (ffffffff810511a7)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/head64.c (ffffffff838c435a)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/kernel/process_64.c (ffffffff810518db)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
```
```
In arch/x86/kernel/tboot.c (ffffffff81070b6f)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff838ef0e1)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810d4d63)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff82174d57)
Location: arch/x86/include/asm/paravirt.h:163
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff8288a1fe)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ce6d)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff81043e0a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810626e7)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828ad436)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81087d83)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff818a8ad9)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
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
In arch/x86/kernel/head64.c (ffffffff828881ab)
Location: arch/x86/include/asm/special_insns.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/kernel/tboot.c (ffffffff8103343a)
Location: arch/x86/include/asm/special_insns.h:172
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052b4a)
Location: arch/x86/include/asm/special_insns.h:172
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828a56fc)
Location: arch/x86/include/asm/special_insns.h:172
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff810769ee)
Location: arch/x86/include/asm/special_insns.h:172
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff81863798)
Location: arch/x86/include/asm/special_insns.h:172
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
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
In arch/x86/kernel/head64.c (ffffffff8289d1fe)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cccd)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff81043c4a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062b97)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828c0335)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81087d33)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff818fa139)
Location: arch/x86/include/asm/paravirt.h:132
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
In arch/x86/kernel/head64.c (ffffffff8289d1fe)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:reset_early_page_tables
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dabd)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:stop_self
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_disable
```
```
In arch/x86/kernel/tboot.c (ffffffff8104504a)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81064155)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/mm/init.c (ffffffff828c3480)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/tlb.c (ffffffff81089f23)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/power/cpu.c (ffffffff8191b299)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
</details>
</li>
</ul>

## Differences
