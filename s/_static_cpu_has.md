# Function: <code>_static_cpu_has</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81003e67)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c8d9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102ed16)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81f8f1b4)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff810386f3)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810399b7)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103aca9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b320)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040c5c)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810496de)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8105023f)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059489)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064591)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
```
In arch/x86/mm/init.c (ffffffff81f9ff67)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107f000)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106b24c)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff8106be99)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
```
In arch/x86/mm/pageattr.c (ffffffff8106f301)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:kernel_map_pages_in_pgd
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__cpa_flush_range
```
```
In arch/x86/mm/tlb.c (ffffffff810722a9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8107718c)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/crypto/crc32c-intel_glue.c (ffffffff81fa1f7c)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/crypto/crc32c-intel_glue.c:crc32c_intel_mod_init
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a839)
Location: arch/x86/include/asm/cpufeature.h:144
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
In kernel/locking/qspinlock.c (ffffffff810cf0d9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In mm/mmap.c (ffffffff811e2173)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
```
In fs/dax.c (ffffffff812876c3)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - fs/dax.c:read_dax_sector
```
```
In lib/random32.c (ffffffff8146345d)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff814c78e9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff81566445)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/nvdimm/claim.c (ffffffff815f6b90)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nsio_rw_bytes
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817191af)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8171c930)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81738a82)
Location: arch/x86/include/asm/cpufeature.h:144
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
Location: arch/x86/include/asm/cpufeature.h:144
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
In arch/x86/entry/vdso/vma.c (ffffffff81003e57)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c7b2)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102ecd6)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81fca543)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff810380a7)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039309)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a549)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81fcd5af)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810406a0)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bade)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3cde)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c219)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067a71)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
```
In arch/x86/mm/fault.c (ffffffff8106ee60)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff8106fab9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
```
In arch/x86/mm/mpx.c (ffffffff8107ad3c)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In kernel/fork.c (ffffffff81083e74)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/qspinlock.c (ffffffff810d5ac9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In mm/mmap.c (ffffffff811f2143)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
```
In lib/random32.c (ffffffff814826f9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff814e9819)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff81592ba5)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_long
  - drivers/char/random.c:get_random_int
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b7ef)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174e8db)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_set_epb
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
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
In arch/x86/entry/vdso/vma.c (ffffffff81003ce7)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102a9cd)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102cfe6)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/espfix_64.c (ffffffff820aace9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff81036465)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:select_idle_routine
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81037249)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__current_fpstate_write_end
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810383d9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff820adc46)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103e62b)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8103ef5f)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b29e)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae3e)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b919)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066cfb)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
```
```
In arch/x86/mm/fault.c (ffffffff8106e5d1)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In arch/x86/mm/extable.c (ffffffff8106f1d9)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
```
In arch/x86/mm/mpx.c (ffffffff8107955e)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In kernel/fork.c (ffffffff81080dbd)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/locking/qspinlock.c (ffffffff810d4a49)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In mm/mmap.c (ffffffff811fd135)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
```
In lib/random32.c (ffffffff81461d94)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff814f5439)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff815a8525)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817695af)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d07a)
Location: arch/x86/include/asm/cpufeature.h:144
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
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
In arch/x86/entry/vdso/vma.c (ffffffff81003f37)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102b722)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102d6d3)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff810322b2)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826b146b)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff810387f9)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:select_idle_routine
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81039524)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103a659)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b41bb)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810419b4)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81042074)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ec8e)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819951ae)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/reboot.c (ffffffff810564d8)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105fa29)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b206)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
```
```
In arch/x86/mm/init.c (ffffffff826c2ba4)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81070b99)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff81073676)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826c3886)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81074489)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff81077530)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/pgtable.c (ffffffff8107981f)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8107a0ec)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:enter_lazy_tlb
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:clear_asid_other
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107cb09)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cd78)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8107f765)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff826c56d7)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5ac1)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In kernel/fork.c (ffffffff81087772)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In mm/mmap.c (ffffffff8121566c)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
```
In lib/random32.c (ffffffff8148dc74)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff81535cb9)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff8160ee40)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df34f)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e2f8b)
Location: arch/x86/include/asm/cpufeature.h:149
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
```
In arch/x86/power/cpu.c (ffffffff81822bee)
Location: arch/x86/include/asm/cpufeature.h:149
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
In arch/x86/entry/vdso/vma.c (ffffffff81004767)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c742)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102e573)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff810337a2)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff826dab24)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff81039cb0)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
  - arch/x86/kernel/process.c:speculative_store_bypass_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103aa64)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103bb55)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826dd988)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81043290)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:syscall_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043848)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81043f5f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff810519c5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff819f170e)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/reboot.c (ffffffff81059288)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81062b39)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106de7c)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
```
```
In arch/x86/mm/init.c (ffffffff81073024)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81073939)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff81075fc6)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff826edb0b)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81076ee5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff81079fa5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/pgtable.c (ffffffff8107c3ef)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8107ce9c)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:enter_lazy_tlb
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:clear_asid_other
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8107f7f9)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd8c)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108286f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff826ef82b)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_init
  - arch/x86/mm/pti.c:pti_clone_kernel_text
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efa73)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff826f0157)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff826f2194)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8108ac98)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/sched/core.c (ffffffff810bb640)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff812364a5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - mm/mmap.c:do_munmap
```
```
In lib/random32.c (ffffffff814c29f0)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff8156b858)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff81648935)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff816767a5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8182930f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182b445)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
```
In arch/x86/power/cpu.c (ffffffff8186ce2e)
Location: arch/x86/include/asm/cpufeature.h:162
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
In arch/x86/kernel/process_64.c (ffffffff8102d9bc)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102f883)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff810347de)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82890f06)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8103b200)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:do_arch_prctl_common
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103bf64)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__restore
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103d065)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893dd0)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810445a6)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff81044fb8)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104595f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f065)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cbae)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/reboot.c (ffffffff8105ef88)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81068839)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073e0c)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_pv_lock_init
```
```
In arch/x86/mm/init.c (ffffffff810790b4)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81079b89)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff8107c273)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a469d)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff8107d575)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff8107eeba)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff81082ea5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_free
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff810838dc)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/dump_pagetables.c (ffffffff8108633f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_user_pgd_level_checkwx
  - arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_debugfs
```
```
In arch/x86/mm/kmmio.c (ffffffff810868cc)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108941f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff8108a28d)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_init
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6730)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a6e5f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828a91a4)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81092c95)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In kernel/sched/core.c (ffffffff810c4bdf)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff81249cb3)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In lib/random32.c (ffffffff814d70a0)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815833d8)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff81666b55)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:init_std_data
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff816959f5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853d3f)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818573d5)
Location: arch/x86/include/asm/cpufeature.h:162
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_enable
  - drivers/cpufreq/intel_pstate.c:intel_pstate_hwp_set
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:show_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:store_energy_performance_preference
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
  - drivers/cpufreq/intel_pstate.c:intel_pstate_get_epp
```
```
In arch/x86/power/cpu.c (ffffffff8188ce3e)
Location: arch/x86/include/asm/cpufeature.h:162
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
In arch/x86/kernel/process_64.c (ffffffff8102f725)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff81031671)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff81036924)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828a8471)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8103d019)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103def6)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8103f8e5)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040695)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046e9b)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac3c1)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052125)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810552cc)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd0e)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106bed2)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff810779ac)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff8107ccb4)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107d8a9)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff8107f845)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828bcb6a)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81080e45)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff8108278a)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff810869ea)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8108757c)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a50e)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108d56e)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff8108dfbe)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bedcc)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828bf516)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090b44)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c198b)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096c8d)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/core.c (ffffffff810ca7d3)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff8125be06)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In lib/random32.c (ffffffff81502f00)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b19)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff8169c8f5)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff816ce2f5)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In arch/x86/power/cpu.c (ffffffff818d7616)
Location: arch/x86/include/asm/cpufeature.h:166
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/kernel/process_64.c (ffffffff81030085)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff81031f31)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff81037154)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ab4d1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8103d7d9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e6b5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040055)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040e65)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047618)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828af533)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052a15)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055bcc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad455e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106ca82)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078a1c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff8107dd54)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107e939)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff810808d5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3005)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81081f05)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff8108384a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff810876da)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8108826c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b17e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108e1ce)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff8108ec7d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5245)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c5991)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091844)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7e04)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109d4c1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/core.c (ffffffff810d3d7a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff8126a4f6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In lib/random32.c (ffffffff81520ea0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815d4d59)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff816bf665)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff816f2135)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In arch/x86/power/cpu.c (ffffffff8190997f)
Location: arch/x86/include/asm/cpufeature.h:173
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
In arch/x86/entry/common.c (ffffffff81005164)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__prepare_exit_to_usermode
```
```
In arch/x86/entry/vdso/vma.c (ffffffff8100590a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_addr
  - arch/x86/entry/vdso/vma.c:vdso_addr
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82cc5a8e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/core.c (ffffffff8100960e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user32
```
```
In arch/x86/xen/setup.c (ffffffff82cc9f38)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82ccc2f8)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82cce959)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff81032b40)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/traps.c (ffffffff81bbd6c9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/time.c (ffffffff82ccf21b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/dumpstack.c (ffffffff810375f5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbde52)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff81038562)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff82ccf986)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103ae1c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82cd06ed)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In arch/x86/kernel/e820.c (ffffffff82cd1a10)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e4d4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/process.c (ffffffff810408f3)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81041870)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81043275)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810440c5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81044c69)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/tboot.c (ffffffff81047974)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047d9b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104ac7c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd4e37)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82cd5727)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057b35)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105ad2c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068a85)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81074252)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff81076a26)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076cae)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81078f68)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107ff30)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff81084447)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/init_64.c (ffffffff81085a17)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81bbf644)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:set_signal_archinfo
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff82ce5f91)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/extable.c (ffffffff81088f85)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/mmap.c (ffffffff810896a4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/pgtable.c (ffffffff810897be)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a5d8)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff8108b9f1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:sync_current_stack_to_mm
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:choose_new_asid
  - arch/x86/mm/tlb.c:clear_asid_other
```
```
In arch/x86/mm/maccess.c (ffffffff8108bbc5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cd0f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff810915e5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/mm/kaslr.c (ffffffff81bc5283)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In arch/x86/mm/pti.c (ffffffff81094fc5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_kernel_text
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82ce8bde)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096fca)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81097a55)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec1c9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog
  - arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_prolog
```
```
In kernel/fork.c (ffffffff810a4321)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/exit.c (ffffffff810ae0da)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/resource.c (ffffffff810b08fd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
```
```
In kernel/sys.c (ffffffff810c2c2e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/kthread.c (ffffffff810d13d6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_use_mm
```
```
In kernel/sched/core.c (ffffffff810df113)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/power/snapshot.c (ffffffff81117d35)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/stacktrace.c (ffffffff8114153f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/stacktrace.c:stack_trace_save_user
```
```
In kernel/module.c (ffffffff8116612b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/module.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff82cf292c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff8116a42b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811a129d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/bpf_trace.c (ffffffff811e9ed3)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec59d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/bpf/syscall.c (ffffffff811fb570)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff81231f57)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_output_sample_ustack
```
```
In kernel/events/callchain.c (ffffffff8124488f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
```
In kernel/events/uprobes.c (ffffffff812459ed)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In kernel/iomem.c (ffffffff8124b640)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In kernel/rseq.c (ffffffff8124bfd2)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
```
```
In mm/maccess.c (ffffffff812583fc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/maccess.c:strnlen_user_nofault
  - mm/maccess.c:strncpy_from_user_nofault
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/shmem.c (ffffffff8126bcae)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/vmstat.c (ffffffff81274718)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/percpu.c (ffffffff82cf9f0d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff812822ce)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8128b3f7)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff81295805)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory.c:clear_huge_page
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__follow_pte_pmd
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:apply_to_p4d_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mlock.c (ffffffff81297c8c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff8129b05e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff8129dfa4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff8129f098)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812a0d8b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:get_old_pmd
  - mm/mremap.c:get_old_pmd
  - mm/mremap.c:get_old_pmd
```
```
In mm/page_vma_mapped.c (ffffffff812a1cd1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a2ddd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/pgtable-generic.c (ffffffff812a33ab)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812a488e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812aa5c4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:is_vmalloc_addr
```
```
In mm/page_alloc.c (ffffffff812b43f6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/shuffle.c (ffffffff81bc5a7a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In mm/swapfile.c (ffffffff812bdfee)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812c8331)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
```
```
In mm/mempolicy.c (ffffffff812d094c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/sparse.c (ffffffff82cfe587)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:mminit_validate_memmodel_limits
  - mm/sparse.c:__section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7e3a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/memory_hotplug.c (ffffffff812e0d67)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:check_hotplug_memory_addressable
  - mm/memory_hotplug.c:check_hotplug_memory_addressable
```
```
In mm/migrate.c (ffffffff812e2540)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:p4d_alloc
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812ed558)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130284c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff81303db1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/userfaultfd.c (ffffffff81307cad)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/page_idle.c (ffffffff813091cd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff813097af)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In fs/exec.c (ffffffff8131bd41)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
  - fs/exec.c:begin_new_exec
  - fs/exec.c:__bprm_mm_init
```
```
In fs/userfaultfd.c (ffffffff8137228c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff813a12e5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813a444f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/meminfo.c (ffffffff813c4f74)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff82d01f4c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:add_modules_range
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:get_kcore_size
```
```
In fs/proc/page.c (ffffffff813cc2a0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In lib/random32.c (ffffffff815840b0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In lib/ioremap.c (ffffffff815e9d35)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/ioremap.c:ioremap_page_range
  - lib/ioremap.c:ioremap_page_range
  - lib/ioremap.c:ioremap_page_range
```
```
In arch/x86/lib/usercopy.c (ffffffff815ff926)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In drivers/idle/intel_idle.c (ffffffff81bcc865)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f0f56)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/balloon.c (ffffffff8171413f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/xen/balloon.c:additional_memory_resource
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817237b0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/random.c (ffffffff817715f4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a82f0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
```
```
In drivers/iommu/intel/svm.c (ffffffff817a91f5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:is_canonical_address
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff817d7453)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189e00d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In drivers/md/dm-stats.c (ffffffff81984f4c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81987ce0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d982f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bba7a4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc39b)
Location: arch/x86/include/asm/cpufeature.h:173
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
In arch/x86/entry/vdso/vma.c (ffffffff8100473a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vdso_addr
  - arch/x86/entry/vdso/vma.c:vdso_addr
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff82fb1382)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:write_ok_or_segv
```
```
In arch/x86/events/core.c (ffffffff810086eb)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101513f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_hw_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_disable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff82fb5da6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff82fb8136)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:xen_pagetable_p2m_free
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_get_user_pgd
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82fba7d3)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff810337a5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
```
```
In arch/x86/kernel/signal.c (ffffffff810349f1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:__do_compat_sys_x32_rt_sigreturn
  - arch/x86/kernel/signal.c:__do_sys_rt_sigreturn
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/kernel/traps.c (ffffffff81c35d1d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:handle_bug
```
```
In arch/x86/kernel/time.c (ffffffff82fbb0e1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/dumpstack.c (ffffffff81038633)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_opcodes
```
```
In arch/x86/kernel/nmi.c (ffffffff81c3674c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff81038f12)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff82fbb7b2)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/sys_ia32.c (ffffffff8103ab82)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/sys_ia32.c:cp_stat64
```
```
In arch/x86/kernel/sys_x86_64.c (ffffffff8103b62c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
  - arch/x86/kernel/sys_x86_64.c:arch_get_unmapped_area_topdown
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82fbc52d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_random
```
```
In arch/x86/kernel/e820.c (ffffffff82fbd860)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff8103cf45)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e584)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
  - arch/x86/kernel/hw_breakpoint.c:arch_check_bp_in_kernelspace
```
```
In arch/x86/kernel/process.c (ffffffff81040843)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810418e0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810432a5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81044105)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:update_pasid
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/ptrace.c (ffffffff81045477)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:x32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:ia32_arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:arch_ptrace
  - arch/x86/kernel/ptrace.c:putreg
  - arch/x86/kernel/ptrace.c:putreg
```
```
In arch/x86/kernel/tboot.c (ffffffff81bd4bf8)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:map_tboot_page
```
```
In arch/x86/kernel/stacktrace.c (ffffffff81047251)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a12c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc0ddd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82fc16df)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810568b5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105988c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff82fc43b6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff82fc46c5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a725)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81074db2)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff81077056)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810772de)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81078f58)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fb58)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/kernel/sev-es.c (ffffffff81082eda)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_read_mem
  - arch/x86/kernel/sev-es.c:vc_write_mem
```
```
In arch/x86/mm/init.c (ffffffff81085997)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:poking_init
```
```
In arch/x86/mm/init_64.c (ffffffff81086adc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8108802c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:fault_in_kernel_space
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:sanitize_error_code
  - arch/x86/mm/fault.c:dump_pagetable
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff82fd3917)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_ioremap_pmd
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
```
```
In arch/x86/mm/extable.c (ffffffff81089135)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/mmap.c (ffffffff81089884)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
  - arch/x86/mm/mmap.c:mmap_address_hint_valid
```
```
In arch/x86/mm/pgtable.c (ffffffff8108999e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff8108a878)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff8108ba41)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_local
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:choose_new_asid
  - arch/x86/mm/tlb.c:clear_asid_other
```
```
In arch/x86/mm/maccess.c (ffffffff8108bbe5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108cac1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/hugetlbpage.c (ffffffff81090f15)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3e156)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
```
```
In arch/x86/mm/pti.c (ffffffff81094385)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_clone_kernel_text
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff82fd6664)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810961f0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_rt_sigreturn
  - arch/x86/ia32/ia32_signal.c:__do_compat_sys_sigreturn
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81096c19)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a34c2)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/exit.c (ffffffff810a912f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/exit.c:__do_compat_sys_waitid
  - kernel/exit.c:__do_sys_waitid
```
```
In kernel/resource.c (ffffffff810ac02d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
```
```
In kernel/ptrace.c (ffffffff810b1fb4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_regset
```
```
In kernel/signal.c (ffffffff810ba176)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
```
```
In kernel/sys.c (ffffffff810be01e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:validate_prctl_map_addr
```
```
In kernel/sched/core.c (ffffffff810da873)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_attr_copy_to_user
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff81108acb)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
  - kernel/sched/membarrier.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff81114175)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:mark_nosave_pages
```
```
In kernel/printk/printk.c (ffffffff8111a357)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff81137618)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_map_resource
```
```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bd4e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/entry/syscall_user_dispatch.c:set_syscall_user_dispatch
```
```
In kernel/futex.c (ffffffff811569b6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/futex.c:futex_atomic_op_inuser
  - kernel/futex.c:cmpxchg_futex_value_locked
  - kernel/futex.c:get_futex_key
```
```
In kernel/module.c (ffffffff8116285b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/module.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff82fdf3dd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff81166b6b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/compat.c (ffffffff8116a080)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/compat.c:compat_alloc_user_space
  - kernel/compat.c:compat_put_bitmap
  - kernel/compat.c:compat_get_bitmap
  - kernel/compat.c:get_compat_sigevent
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119e3ed)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/trace/bpf_trace.c (ffffffff811e769b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ea6ed)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
  - kernel/trace/trace_kprobe.c:process_fetch_insn
```
```
In kernel/bpf/syscall.c (ffffffff811fa6b0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff8123ca37)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:perf_virt_to_phys
```
```
In kernel/events/uprobes.c (ffffffff81250331)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/events/uprobes.c:xol_add_vma
```
```
In kernel/iomem.c (ffffffff81255a30)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
```
```
In kernel/rseq.c (ffffffff81256216)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/rseq.c:__ia32_sys_rseq
  - kernel/rseq.c:__x64_sys_rseq
  - kernel/rseq.c:__rseq_handle_notify_resume
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
  - kernel/rseq.c:rseq_get_rseq_cs
```
```
In mm/maccess.c (ffffffff81262790)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
  - mm/maccess.c:copy_from_user_nofault
```
```
In mm/shmem.c (ffffffff812766fe)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_unmapped_area
```
```
In mm/vmstat.c (ffffffff8127ef6b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
```
```
In mm/percpu.c (ffffffff82fe6c66)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff8128c411)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
  - mm/compaction.c:__reset_isolation_pfn
```
```
In mm/gup.c (ffffffff8129519f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a0bea)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__get_locked_pte
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_p4d_range
  - mm/memory.c:print_bad_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mincore.c (ffffffff812a0e83)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mincore.c:__do_sys_mincore
  - mm/mincore.c:__do_sys_mincore
```
```
In mm/mlock.c (ffffffff812a2d99)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mlock.c:__do_sys_mlockall
```
```
In mm/mmap.c (ffffffff812a621e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:__do_munmap
  - mm/mmap.c:get_unmapped_area
  - mm/mmap.c:get_unmapped_area
```
```
In mm/mmu_gather.c (ffffffff812a9324)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff812aa458)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_p4d_range
```
```
In mm/mremap.c (ffffffff812ac57b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mremap.c:mremap_to
  - mm/mremap.c:mremap_to
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812ad4fc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812ae6fd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_p4d_range
```
```
In mm/pgtable-generic.c (ffffffff812aeccb)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812b001e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:mm_find_pmd
```
```
In mm/vmalloc.c (ffffffff812b5c94)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:map_kernel_range_noflush
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:vmap_p4d_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/vmalloc.c:vunmap_p4d_range
  - mm/vmalloc.c:is_vmalloc_addr
```
```
In mm/ioremap.c (ffffffff812b8282)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/ioremap.c:ioremap_page_range
  - mm/ioremap.c:ioremap_page_range
```
```
In mm/page_alloc.c (ffffffff812b9bb1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_range_valid_contig
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
```
```
In mm/shuffle.c (ffffffff81c3ea60)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In mm/swapfile.c (ffffffff812c9b0e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_p4d_range
```
```
In mm/hugetlb.c (ffffffff812d3f01)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:huge_pmd_unshare
```
```
In mm/mempolicy.c (ffffffff812dc46c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
```
```
In mm/sparse.c (ffffffff82feaf7a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:mminit_validate_memmodel_limits
  - mm/sparse.c:__section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81c40b65)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/memory_hotplug.c (ffffffff812eb95f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_memory_block
  - mm/memory_hotplug.c:scan_movable_pages
  - mm/memory_hotplug.c:find_biggest_section_pfn
  - mm/memory_hotplug.c:find_smallest_section_pfn
  - mm/memory_hotplug.c:check_hotplug_memory_addressable
  - mm/memory_hotplug.c:check_hotplug_memory_addressable
```
```
In mm/migrate.c (ffffffff812ed970)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:__copy_gigantic_page
  - mm/migrate.c:p4d_alloc
  - mm/migrate.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff812f8c78)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:split_huge_pmd_address
```
```
In mm/memory-failure.c (ffffffff8130ead9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
```
In mm/page_isolation.c (ffffffff8130fc81)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:test_pages_isolated
  - mm/page_isolation.c:undo_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
```
In mm/userfaultfd.c (ffffffff813139dd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:mm_alloc_pmd
```
```
In mm/page_idle.c (ffffffff8131503c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffff813155bf)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In fs/read_write.c (ffffffff8131dbf4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:vfs_read
```
```
In fs/exec.c (ffffffff81327011)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/exec.c:setup_new_exec
  - fs/exec.c:__bprm_mm_init
```
```
In fs/readdir.c (ffffffff81337c69)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/readdir.c:compat_filldir
  - fs/readdir.c:compat_fillonedir
  - fs/readdir.c:filldir64
  - fs/readdir.c:filldir
  - fs/readdir.c:fillonedir
```
```
In fs/select.c (ffffffff8133a9f2)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/select.c:do_sys_poll
```
```
In fs/eventpoll.c (ffffffff8137bc18)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_wait
```
```
In fs/userfaultfd.c (ffffffff813800dc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In fs/io_uring.c (ffffffff813950b6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_prep
  - fs/io_uring.c:__io_compat_recvmsg_copy_hdr
  - fs/io_uring.c:io_compat_import
```
```
In fs/binfmt_elf.c (ffffffff813b2457)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813b5181)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/proc/meminfo.c (ffffffff813d6eca)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff82fef23b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:add_modules_range
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:get_kcore_size
```
```
In fs/proc/page.c (ffffffff813ddedd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecgroup_read
  - fs/proc/page.c:kpageflags_read
  - fs/proc/page.c:kpagecount_read
```
```
In lib/random32.c (ffffffff81bf3f41)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In lib/iov_iter.c (ffffffff815a4c90)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/iov_iter.c:import_single_range
  - lib/iov_iter.c:__import_iovec
  - lib/iov_iter.c:copy_compat_iovec_from_user
  - lib/iov_iter.c:copyout_mc
  - lib/iov_iter.c:copyin
  - lib/iov_iter.c:copyout
```
```
In lib/usercopy.c (ffffffff815ac5b0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/usercopy.c:check_zeroed_user
  - lib/usercopy.c:_copy_to_user
  - lib/usercopy.c:_copy_from_user
```
```
In lib/strncpy_from_user.c (ffffffff81607fac)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffff816080e4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
  - lib/strnlen_user.c:strnlen_user
```
```
In arch/x86/lib/copy_mc.c (ffffffff8162177e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
```
```
In arch/x86/lib/csum-wrappers_64.c (ffffffff81621fcd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_to_user
  - arch/x86/lib/csum-wrappers_64.c:csum_and_copy_from_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81624856)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
```
In arch/x86/lib/usercopy_64.c (ffffffff81624935)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:clear_user
```
```
In drivers/pci/proc.c (ffffffff81665467)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/proc.c:proc_bus_pci_read
```
```
In drivers/idle/intel_idle.c (ffffffff8169d5a0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In drivers/acpi/acpi_dbg.c (ffffffff8170a833)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e136)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_handle_memory_failure
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817404f0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In drivers/char/mem.c (ffffffff817897ce)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:read_port
```
```
In drivers/char/random.c (ffffffff8178c604)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b41a0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5115)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:is_canonical_address
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff817ebeca)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae99a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_unmap_dma
```
```
In drivers/usb/core/devio.c (ffffffff818d782f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
```
```
In drivers/md/dm-stats.c (ffffffff81988fec)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff8198bc10)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff819d8b8d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
```
In net/socket.c (ffffffff819dd8bb)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:compat_ifreq_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
  - net/socket.c:ethtool_ioctl
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bceed4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bd137b)
Location: arch/x86/include/asm/cpufeature.h:173
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff831bb50d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/intel/core.c (ffffffff831bdc96)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff810163af)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff831c05af)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff831c2799)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c4ea1)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff81034e5f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
```
```
In arch/x86/kernel/traps.c (ffffffff81c281bd)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/time.c (ffffffff831c5959)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/nmi.c (ffffffff81c28bdc)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff8103aa09)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff831c5df0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/espfix_64.c (ffffffff831c6cdc)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/e820.c (ffffffff831c7f74)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff8103e7e5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/process.c (ffffffff81042233)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810432e0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:copy_init_fpstate_to_fpregs
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:copy_fpregs_to_fpstate
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/core.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81044bb5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_user_to_fpregs_zeroing
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
  - arch/x86/kernel/fpu/signal.c:copy_kernel_to_fpregs
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045d75)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/tboot.c (ffffffff81bc7087)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b9de)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff831cb240)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f79c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff831cbdca)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a1fd)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff831cea87)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831cee08)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810697a5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b1ec)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810753f2)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff81077ab6)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077d9c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81079ef8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080c78)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff81086697)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
```
```
In arch/x86/mm/init_64.c (ffffffff810877c8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:pfn_valid
```
```
In arch/x86/mm/fault.c (ffffffff81088af7)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81bcb66c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/extable.c (ffffffff81089db5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
```
In arch/x86/mm/mmap.c (ffffffff8108a097)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/pgtable.c (ffffffff8108a63e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff8108b467)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In arch/x86/mm/tlb.c (ffffffff8108c5b4)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d6e8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/kaslr.c (ffffffff81c3046e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff81094d64)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff831e10b8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096b14)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2da1)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810a0c50)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/resource.c (ffffffff810ad46f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
```
```
In kernel/sched/core.c (ffffffff810d87d0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff8110a9ab)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
  - kernel/sched/membarrier.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff81112b27)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/power/snapshot.c:pfn_valid
```
```
In kernel/dma/mapping.c (ffffffff81138387)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/module.c (ffffffff8116330b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/module.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff831e9fbb)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff81167905)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8119efd7)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/bpf/syscall.c (ffffffff811fb611)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff81243d7a)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:p4d_offset
```
```
In kernel/iomem.c (ffffffff81259fd7)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/percpu.c (ffffffff831f1395)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff812912cd)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In mm/gup.c (ffffffff8129aa1f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812a51fc)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/memory.c:follow_invalidate_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pfn_valid
```
```
In mm/mprotect.c (ffffffff812af898)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812b0360)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812b26e8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812b3abd)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff812b4202)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812b5649)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812bb384)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_no_huge
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:is_vmalloc_addr
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff812bf297)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:pfn_valid
```
```
In mm/memory_hotplug.c (ffffffff812c72a5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_valid
```
```
In mm/swapfile.c (ffffffff812d0354)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff812dae1e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse.c (ffffffff831f5903)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:mminit_validate_memmodel_limits
  - mm/sparse.c:__section_nr
```
```
In mm/sparse-vmemmap.c (ffffffff81c32ac8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In mm/migrate.c (ffffffff812f2cd0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
  - mm/migrate.c:pfn_valid
```
```
In mm/huge_memory.c (ffffffff8130032d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff81313009)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:p4d_offset
  - mm/memory-failure.c:pfn_valid
```
```
In mm/userfaultfd.c (ffffffff81319bc1)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:p4d_offset
```
```
In fs/userfaultfd.c (ffffffff81386a50)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In fs/proc/meminfo.c (ffffffff813ddddb)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff831f9a94)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:get_kcore_size
  - fs/proc/kcore.c:pfn_valid
```
```
In lib/random32.c (ffffffff81be5d9c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In arch/x86/lib/copy_mc.c (ffffffff8160507e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
```
```
In drivers/idle/intel_idle.c (ffffffff81680320)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff816ef857)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81723cb7)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:pfn_valid
```
```
In drivers/char/random.c (ffffffff8176fd1d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179725f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
```
```
In drivers/iommu/intel/svm.c (ffffffff81798c5b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff817d06ea)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8188f937)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819470e5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/md/dm-stats.c (ffffffff8196d6cc)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81970317)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff819be947)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/ras/cec.c:pfn_valid
```
```
In arch/x86/power/hibernate_64.c (ffffffff81bc288e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81bc3160)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8329ba38)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/intel/core.c (ffffffff8329e05b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff81017e0f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff832a10b2)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff832a31a5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5bbc)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/kernel/process_64.c (ffffffff8103a17f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81d4632d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/time.c (ffffffff832a66d9)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/nmi.c (ffffffff81d46d79)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff81040404)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff832a6d66)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/espfix_64.c (ffffffff832a7ba0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/e820.c (ffffffff832a9157)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff81044555)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
```
```
In arch/x86/kernel/process.c (ffffffff81048583)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:flush_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81049aaa)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:__restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:__restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8104a46b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8104aef5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8104c3d5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:validate_xsaves_xrstors
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
  - arch/x86/kernel/fpu/xstate.c:do_extra_xstate_size_checks
```
```
In arch/x86/kernel/tboot.c (ffffffff81c9a687)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81052a02)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff832ac8b0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8105797c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff832ad619)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8106364d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff832b0d2d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b10f0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073bc5)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d0c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff832b4d6b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810828e2)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810852b6)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810855aa)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81088058)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff832bd675)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108fbe8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff81095907)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
```
```
In arch/x86/mm/init_64.c (ffffffff81096b30)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff81097f29)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff81ca0da4)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:p4d_offset
  - arch/x86/mm/ioremap.c:pfn_valid
```
```
In arch/x86/mm/extable.c (ffffffff81099285)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
```
In arch/x86/mm/mmap.c (ffffffff810995c8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_valid
```
```
In arch/x86/mm/pgtable.c (ffffffff81099bc7)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff8109aa00)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:pfn_valid
```
```
In arch/x86/mm/tlb.c (ffffffff8109bdf4)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109cf71)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/pkeys.c (ffffffff832c391d)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In arch/x86/mm/kaslr.c (ffffffff81d4ec2c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810a4ce4)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81ca2557)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6ab4)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6744)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff810b20c3)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/resource.c (ffffffff810befef)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
```
```
In kernel/sched/core.c (ffffffff810ec060)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/membarrier.c (ffffffff8112913b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:ipi_sync_core
  - kernel/sched/membarrier.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff81132d50)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In kernel/dma/mapping.c (ffffffff8115b1d0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/dma/mapping.c:pfn_valid
```
```
In kernel/module.c (ffffffff8118886b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/module.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff832ce5ad)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff8118d185)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811c8e50)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:pfn_valid
```
```
In kernel/bpf/syscall.c (ffffffff8122cdb1)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff8127e6e6)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:p4d_offset
```
```
In kernel/iomem.c (ffffffff81295d90)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - kernel/iomem.c:pfn_valid
```
```
In mm/percpu.c (ffffffff832d6d0a)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff812d0ed8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/compaction.c:pfn_valid
```
```
In mm/gup.c (ffffffff812db3cf)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff812e37a8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mmap.c (ffffffff812eeea0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In mm/mprotect.c (ffffffff812f032e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:p4d_offset
```
```
In mm/mremap.c (ffffffff812f1b9f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff812f42fd)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff812f565c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff812f5de2)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff812f72d8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff812fd9b4)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_no_huge
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:is_vmalloc_addr
  - mm/vmalloc.c:pfn_valid
```
```
In mm/page_alloc.c (ffffffff81301bd0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8130c025)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swapfile.c (ffffffff8131589f)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81321e4e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:pfn_valid
```
```
In mm/sparse.c (ffffffff832dbfa6)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:mminit_validate_memmodel_limits
```
```
In mm/sparse-vmemmap.c (ffffffff81d51492)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate.c (ffffffff8133d1c0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/migrate.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff81349f88)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff8135fad9)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff8136696e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/bootmem_info.c (ffffffff832de7d0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/userfaultfd.c (ffffffff813d3ce0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In fs/proc/task_mmu.c (ffffffff8141fdc8)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
```
```
In fs/proc/meminfo.c (ffffffff8142f591)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff832e09cc)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:get_kcore_size
  - fs/proc/kcore.c:pfn_valid
```
```
In lib/random32.c (ffffffff81cda730)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In arch/x86/lib/copy_mc.c (ffffffff8167396b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
```
```
In drivers/idle/intel_idle.c (ffffffff816f5090)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff817698b0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:pfn_valid
```
```
In drivers/xen/swiotlb-xen.c (ffffffff817a2c30)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
```
```
In drivers/char/random.c (ffffffff817f56dd)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181f26b)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
```
```
In drivers/iommu/intel/svm.c (ffffffff81821315)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff8185b073)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81923248)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:pfn_valid
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebd75)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/md/dm-stats.c (ffffffff81a15c9c)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81a18c28)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:pfn_valid
```
```
In drivers/ras/cec.c (ffffffff81a6ded0)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - drivers/ras/cec.c:pfn_valid
```
```
In arch/x86/power/hibernate_64.c (ffffffff81c92f4e)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81c94160)
Location: arch/x86/include/asm/cpufeature.h:177
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/coco/tdx/tdx.c (ffffffff83449e34)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_guest_init
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8344a234)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/amd/brs.c (ffffffff8344ace3)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_init
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/intel/core.c (ffffffff8344cb42)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff81019e4e)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff834500d7)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83452414)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454ca8)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/ivm.c (ffffffff8103f205)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/process_64.c (ffffffff81041329)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81042a15)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/time.c (ffffffff83455900)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/nmi.c (ffffffff81f152ba)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff81047d27)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff83456025)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83456f41)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/e820.c (ffffffff834587de)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff8104c905)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
```
```
In arch/x86/kernel/static_call.c (ffffffff81f19601)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/process.c (ffffffff81051e57)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:flush_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff81053896)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_flush_thread
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8105460f)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8345a0c9)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81057415)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/tboot.c (ffffffff81e49af1)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105e48f)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8345d40d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:write_spec_ctrl_current
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81061245)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81063c6c)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81063dfc)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8345e4b1)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810702ca)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff83461eae)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8346231d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082395)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff8108450d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81084755)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff834663d5)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff83466642)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8109250f)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/ftrace.c (ffffffff810947db)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810955e5)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8109597c)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81097c94)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff8346f06d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
```
```
In arch/x86/kernel/kvm.c (ffffffff8109efec)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0a28)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff810a7af7)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
```
```
In arch/x86/mm/init_64.c (ffffffff810a95e1)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:kern_addr_valid
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810aab70)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab4d5)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/extable.c (ffffffff810ac3d9)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
```
```
In arch/x86/mm/mmap.c (ffffffff810aca62)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/pgtable.c (ffffffff810acbd8)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff810add61)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff810af334)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b07ea)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
```
```
In arch/x86/mm/pat/memtype.c (ffffffff83474b8f)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:init_cache_modes
```
```
In arch/x86/mm/pkeys.c (ffffffff834761ec)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In arch/x86/mm/kaslr.c (ffffffff81f1ea81)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810b95d6)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81e51be3)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b9740)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_cache_flush_required
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff81e51d96)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:pti_set_user_pgtbl
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bbdbe)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479531)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c18c2)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
```
```
In kernel/fork.c (ffffffff810c8a18)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/resource.c (ffffffff810d610f)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
```
```
In kernel/sched/core.c (ffffffff81106510)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8113c08b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
  - kernel/sched/build_utility.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff81156db3)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/module/main.c (ffffffff8118e69b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/module/main.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff834822b6)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff811bc699)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff811fca45)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/syscall.c (ffffffff8126f182)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff812d334b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:p4d_offset
```
```
In kernel/iomem.c (ffffffff812ebaed)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
  - kernel/iomem.c:try_ram_remap
```
```
In mm/util.c (ffffffff8131d2cc)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/util.c:kvmalloc_node
```
```
In mm/percpu.c (ffffffff81e6c542)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff8132fd02)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
```
```
In mm/gup.c (ffffffff8133afaf)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff81348bd1)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:copy_huge_page_from_user
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mmap.c (ffffffff81352275)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In mm/mprotect.c (ffffffff813536fe)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/mremap.c (ffffffff81355758)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813582fa)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81359518)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff81359d09)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8135c8e8)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81364939)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:is_vmalloc_addr
  - mm/vmalloc.c:vm_area_register_early
```
```
In mm/page_alloc.c (ffffffff81372d94)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff81f1ba2b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_get_pluggable_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swapfile.c (ffffffff81380e4f)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8138f06e)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/sparse.c (ffffffff8139b59d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
```
```
In mm/sparse-vmemmap.c (ffffffff81f21738)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/migrate_device.c (ffffffff813b6200)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/migrate_device.c:p4d_offset
```
```
In mm/huge_memory.c (ffffffff813c09b5)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pages_all
  - mm/huge_memory.c:split_huge_pmd_address
  - mm/huge_memory.c:p4d_offset
```
```
In mm/memory-failure.c (ffffffff813dd185)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff813e3cfe)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/bootmem_info.c (ffffffff834940bc)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:__nr_to_section
```
```
In fs/userfaultfd.c (ffffffff8145d290)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In fs/proc/task_mmu.c (ffffffff81497d08)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smap
```
```
In fs/proc/meminfo.c (ffffffff814a91d7)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff83496a37)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:get_kcore_size
```
```
In arch/x86/lib/copy_mc.c (ffffffff8178df4b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
```
```
In drivers/idle/intel_idle.c (ffffffff818219c0)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8186276a)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff81863fd3)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff81f29914)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e53d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff818dd0ba)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/random.c (ffffffff834b400c)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/char/random.c:random_init
```
```
In drivers/iommu/intel/svm.c (ffffffff81961472)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff819a1ff0)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff834bab74)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a794a9)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51e55)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/md/dm-stats.c (ffffffff81b7e69b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81b81f57)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/ras/cec.c (ffffffff81bdf11d)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_add_elem
```
```
In arch/x86/power/hibernate_64.c (ffffffff81e4279b)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff81e43170)
Location: arch/x86/include/asm/cpufeature.h:185
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83e64867)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/core.c (ffffffff81006205)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_get_x86_pmu_capability
```
```
In arch/x86/events/amd/core.c (ffffffff8100b4f5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_brs_is_visible
```
```
In arch/x86/events/amd/brs.c (ffffffff83e656b5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_init
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/intel/core.c (ffffffff83e67832)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101de9e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff81033e6b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_enable_syscall
  - arch/x86/xen/setup.c:xen_enable_sysenter
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff83e6f95c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e72885)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/ivm.c (ffffffff81048335)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/process_64.c (ffffffff8104aa79)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8104c425)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/time.c (ffffffff83e73879)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/nmi.c (ffffffff820bc74a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff81052a07)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff83e742ea)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/signal_32.c (ffffffff81055da5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83e75632)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/e820.c (ffffffff83e77bf5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/topology.c (ffffffff81058479)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:arch_register_cpu
```
```
In arch/x86/kernel/alternative.c (ffffffff81058c65)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
```
```
In arch/x86/kernel/static_call.c (ffffffff820c114b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/process.c (ffffffff8105f574)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:flush_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff820bcc40)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_idle_fpregs
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106221f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff83e79d1c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064b85)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:fpstate_realloc
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/tboot.c (ffffffff81067e68)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac4e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106ca55)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7d5e9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fbc5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072dcc)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81072eb3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810746d2)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107500a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f685)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107c0ac)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff83e840d8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090e3d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091475)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_sgx2_ready
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e84615)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094df5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff8109747d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810979e5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smpboot.c (ffffffff83e89da2)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff83e8a115)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a754f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/ftrace.c (ffffffff810aa26c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810ab1a5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab5c1)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810ae094)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff83e9524b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/kvm.c (ffffffff810b652c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8720)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/kernel/callthunks.c (ffffffff83e98b8c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:callthunks_patch_builtin_calls
```
```
In arch/x86/mm/init.c (ffffffff810c0f57)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
```
```
In arch/x86/mm/init_64.c (ffffffff810c29e1)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810c4860)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810c5915)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/extable.c (ffffffff810c64e9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b22)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/pgtable.c (ffffffff810c6ca8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff810c7fa1)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff810c9764)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810caeba)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpu_cache_has_invalidate_memregion
```
```
In arch/x86/mm/pat/memtype.c (ffffffff83e9ce05)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
```
```
In arch/x86/mm/pkeys.c (ffffffff83e9f105)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In arch/x86/mm/kaslr.c (ffffffff820c789f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d5146)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810d5200)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d53e0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_cache_flush_required
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff83ea0998)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea37b9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810de322)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
```
```
In kernel/fork.c (ffffffff810e5d75)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/resource.c (ffffffff810f5a5e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
```
```
In kernel/sched/core.c (ffffffff8112c1d0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff81166cab)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
  - kernel/sched/build_utility.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff81187949)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/module/main.c (ffffffff811cb07b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/module/main.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff83eaf771)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff811fe619)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81244165)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/syscall.c (ffffffff812c4a10)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff8133b5bb)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:p4d_offset
```
```
In kernel/iomem.c (ffffffff81355d2d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
  - kernel/iomem.c:try_ram_remap
```
```
In mm/filemap.c (ffffffff8135f967)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/vmscan.c (ffffffff81378642)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/vmscan.c:show_enabled
  - mm/vmscan.c:walk_pmd_range
```
```
In mm/util.c (ffffffff81390c2c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/util.c:kvmalloc_node
```
```
In mm/percpu.c (ffffffff81399140)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff813a68ab)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In mm/gup.c (ffffffff813b2bf8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813b6767)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
```
```
In mm/mmap.c (ffffffff813cc24f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In mm/mprotect.c (ffffffff813cdb58)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff813cfec8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff813d2fc2)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff813d3df8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff813d46f9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff813d980d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff813e0499)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:is_vmalloc_addr
  - mm/vmalloc.c:vm_area_register_early
```
```
In mm/page_alloc.c (ffffffff813f0514)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:mark_free_pages
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:reserve_bootmem_region
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff820c3a26)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:mhp_get_pluggable_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swapfile.c (ffffffff83ec21e9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8140db5e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/hugetlb_vmemmap.c (ffffffff814138a3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse.c (ffffffff820cab9a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
```
```
In mm/sparse-vmemmap.c (ffffffff820cb903)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/ksm.c (ffffffff81421ae8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In mm/migrate.c (ffffffff8143277f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff814397ec)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:p4d_alloc
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff8144423b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff814501aa)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In mm/memory-failure.c (ffffffff81463f53)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff8146b71e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/hmm.c (ffffffff814705d7)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In mm/bootmem_info.c (ffffffff83ec85f0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/userfaultfd.c (ffffffff814ecb70)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In fs/proc/task_mmu.c (ffffffff8153010c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/meminfo.c (ffffffff8153ec83)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff83ecbb97)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:get_kcore_size
```
```
In drivers/idle/intel_idle.c (ffffffff819526b0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In drivers/acpi/sleep.c (ffffffff81958120)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff8199fc8a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff819a1c27)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff820d5764)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7a3d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a30506)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/random.c (ffffffff83eeef00)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
```
```
In drivers/iommu/intel/svm.c (ffffffff81aca05d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff81b13f60)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff83ef848c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81ce9fe5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/md/dm-stats.c (ffffffff81d1c7ab)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81d20797)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/platform/x86/intel/pmc/pltdrv.c (ffffffff83f0b38a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
```
In drivers/ras/cec.c (ffffffff81d8a6f0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_add_elem
```
```
In net/sched/sch_api.c (ffffffff83f0d9f2)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - net/sched/sch_api.c:pktsched_init
```
```
In arch/x86/power/hibernate_64.c (ffffffff8201d1ce)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8201e1c0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
```
In arch/x86/lib/copy_mc.c (ffffffff8204b77b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff83684ee7)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/core.c (ffffffff810059a5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_get_x86_pmu_capability
```
```
In arch/x86/events/amd/core.c (ffffffff8100acc5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_brs_is_visible
```
```
In arch/x86/events/amd/brs.c (ffffffff83685d35)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_init
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/intel/core.c (ffffffff83687ce5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff8101db9e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff81033dfb)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_enable_syscall
  - arch/x86/xen/setup.c:xen_enable_sysenter
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff8369071c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff836937a5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/ivm.c (ffffffff810486e5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/process_64.c (ffffffff8104b7f6)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8104cc95)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/time.c (ffffffff83695339)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/nmi.c (ffffffff8213dee4)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff81053985)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff83695dba)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/signal_32.c (ffffffff81056d4e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
```
```
In arch/x86/kernel/espfix_64.c (ffffffff83697102)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/e820.c (ffffffff8369a085)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff8105a535)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
```
```
In arch/x86/kernel/tsc.c (ffffffff8369ba41)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/static_call.c (ffffffff82144e23)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/process.c (ffffffff81060c94)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:flush_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8213e600)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_idle_fpregs
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff81063ad2)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8369c43c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81066485)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/tboot.c (ffffffff81069718)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c5be)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8369eb58)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff836a0259)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810717c5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810749ac)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff81074a93)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810750a5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:amd_set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107717a)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a23d5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff8107e389)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff836a28e5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082593)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff836a58f3)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff836a7628)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093d6d)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810943b5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_sgx2_ready
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a7b65)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097ce5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff8109a54d)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff821430c3)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff836acce4)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:build_sched_topology
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff836ad805)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aa7af)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/ftrace.c (ffffffff810ad62c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810aed65)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af181)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810b1094)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff836b8dab)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_is_pc10_damaged
```
```
In arch/x86/kernel/kvm.c (ffffffff810b962c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb8f0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/kernel/callthunks.c (ffffffff836bc5ac)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:callthunks_patch_builtin_calls
```
```
In arch/x86/mm/init.c (ffffffff810c4637)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
```
```
In arch/x86/mm/init_64.c (ffffffff810c60c1)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810c8060)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810c90a0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/extable.c (ffffffff810c9b26)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
```
```
In arch/x86/mm/mmap.c (ffffffff810ca2b6)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/pgtable.c (ffffffff810ca420)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff810cb6dd)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff810cba65)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810ce4ea)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpu_cache_has_invalidate_memregion
```
```
In arch/x86/mm/pat/memtype.c (ffffffff836c0925)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
```
```
In arch/x86/mm/pkeys.c (ffffffff836c3285)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In arch/x86/mm/kaslr.c (ffffffff8214b8e1)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810d8636)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810d86f0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810d88d0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_cache_flush_required
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff836c4a88)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c7a54)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e9922)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
```
```
In kernel/fork.c (ffffffff810f14f1)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/resource.c (ffffffff81101e7e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
```
```
In kernel/sched/core.c (ffffffff811392d0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8117711b)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
  - kernel/sched/build_utility.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff81198ad9)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/module/main.c (ffffffff811de49b)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/module/main.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff836d47c1)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff81213a19)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b245)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/syscall.c (ffffffff812ebb04)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff8136cf96)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:p4d_offset
```
```
In kernel/iomem.c (ffffffff813873bd)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - kernel/iomem.c:try_ram_remap
  - kernel/iomem.c:try_ram_remap
```
```
In mm/filemap.c (ffffffff81390937)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/vmscan.c (ffffffff813a59b5)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/vmscan.c:should_clear_pmd_young
```
```
In mm/util.c (ffffffff813c353c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/util.c:kvmalloc_node
```
```
In mm/mm_init.c (ffffffff836e04cf)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (ffffffff813cc150)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff813dba50)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/gup.c (ffffffff813e7868)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff813eb17a)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/memory.c:follow_pte
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mmap.c (ffffffff81400bbf)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In mm/mprotect.c (ffffffff8140239e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff8140498b)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff81407c1e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff814087c8)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff814090c9)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8140e012)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81415259)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:is_vmalloc_addr
  - mm/vmalloc.c:vm_area_register_early
```
```
In mm/page_alloc.c (ffffffff814240a4)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/page_alloc.c:put_page_back_buddy
  - mm/page_alloc.c:take_page_off_buddy
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:__isolate_free_page
  - mm/page_alloc.c:free_unref_page_prepare
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:__free_pages_ok
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:__free_one_page
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8214779c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:mhp_get_pluggable_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swapfile.c (ffffffff836e77d9)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff81440f11)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
```
```
In mm/hugetlb_vmemmap.c (ffffffff81446df3)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_range
```
```
In mm/sparse.c (ffffffff8144efd3)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
```
```
In mm/sparse-vmemmap.c (ffffffff8214fb93)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/ksm.c (ffffffff8145688c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81467e5a)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146fba3)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:p4d_alloc
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff814797b8)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
```
In mm/memcontrol.c (ffffffff81485c0a)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
```
```
In mm/memory-failure.c (ffffffff81499a0f)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814a0521)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/hmm.c (ffffffff814a4db2)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In mm/bootmem_info.c (ffffffff836ed64f)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/userfaultfd.c (ffffffff81523810)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In fs/proc/task_mmu.c (ffffffff81567f7d)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/meminfo.c (ffffffff81576f53)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff836f0c17)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:get_kcore_size
```
```
In drivers/idle/intel_idle.c (ffffffff821435f8)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/sleep.c (ffffffff8199e600)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff819e695e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff819e8907)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff82143ccf)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a3014d)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81a79d15)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/random.c (ffffffff83714b5c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
```
```
In drivers/iommu/amd/init.c (ffffffff81b04985)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_v2_supported
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel/svm.c (ffffffff81b16bdd)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_bind_mm
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff81b62c90)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff8371e02c)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52b25)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/md/dm-stats.c (ffffffff81d8598b)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81d89977)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81dd4683)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In drivers/platform/x86/intel/pmc/pltdrv.c (ffffffff837315ea)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/pltdrv.c:pmc_core_platform_init
```
```
In drivers/ras/cec.c (ffffffff81df8cf0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_add_elem
```
```
In net/sched/sch_api.c (ffffffff83733fe2)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - net/sched/sch_api.c:pktsched_init
```
```
In arch/x86/power/hibernate_64.c (ffffffff8209d85e)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff8209e1c0)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
```
In arch/x86/lib/copy_mc.c (ffffffff820ca05b)
Location: arch/x86/include/asm/cpufeature.h:169
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
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
In arch/x86/entry/common.c (ffffffff8221ba48)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff838b4087)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/events/core.c (ffffffff8100b0a5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_get_x86_pmu_capability
```
```
In arch/x86/events/amd/core.c (ffffffff81010445)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_brs_is_visible
```
```
In arch/x86/events/amd/brs.c (ffffffff838b4ec5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/amd/brs.c:amd_brs_init
  - arch/x86/events/amd/brs.c:amd_brs_reset
```
```
In arch/x86/events/intel/core.c (ffffffff838b7247)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
```
```
In arch/x86/events/intel/lbr.c (ffffffff81023c6e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_pebs_lbrs
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_setup_lbr_filter
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_del
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_add
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_swap_task_ctx
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_reset
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_enable
```
```
In arch/x86/xen/setup.c (ffffffff8103a0fb)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/xen/setup.c:xen_enable_syscall
  - arch/x86/xen/setup.c:xen_enable_sysenter
  - arch/x86/xen/setup.c:xen_get_pages_limit
  - arch/x86/xen/setup.c:xen_memory_setup
```
```
In arch/x86/xen/mmu_pv.c (ffffffff838c01ec)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys
  - arch/x86/xen/mmu_pv.c:__xen_pgd_walk
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
  - arch/x86/xen/mmu_pv.c:xen_relocate_p2m
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c3385)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104f7d5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
```
```
In arch/x86/kernel/process_64.c (ffffffff810529fb)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:do_arch_prctl_64
  - arch/x86/kernel/process_64.c:prctl_enable_tagged_addr
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:current_save_fsgs
  - arch/x86/kernel/process_64.c:__wrgsbase_inactive
  - arch/x86/kernel/process_64.c:__rdgsbase_inactive
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81053f15)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:handle_xfd_event
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:get_kernel_gp_address
  - arch/x86/kernel/traps.c:get_kernel_gp_address
```
```
In arch/x86/kernel/time.c (ffffffff838c5279)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/time.c:x86_late_time_init
```
```
In arch/x86/kernel/nmi.c (ffffffff8221fee0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/ldt.c (ffffffff8105aba5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:map_ldt_struct_to_user
  - arch/x86/kernel/ldt.c:load_mm_ldt
```
```
In arch/x86/kernel/setup.c (ffffffff838c5a0b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/signal_32.c (ffffffff8105df9e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
```
```
In arch/x86/kernel/espfix_64.c (ffffffff838c6e23)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/e820.c (ffffffff838c9e05)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__end_of_ram_pfn
```
```
In arch/x86/kernel/alternative.c (ffffffff810616a5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:do_sync_core
  - arch/x86/kernel/alternative.c:text_poke_early
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:apply_returns
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:patch_retpoline
  - arch/x86/kernel/alternative.c:optimize_nops_inplace
```
```
In arch/x86/kernel/tsc.c (ffffffff838cb810)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_init
```
```
In arch/x86/kernel/static_call.c (ffffffff82227543)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/static_call.c:__static_call_transform
  - arch/x86/kernel/static_call.c:__static_call_transform
```
```
In arch/x86/kernel/process.c (ffffffff81067d40)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:select_idle_routine
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:flush_thread
  - arch/x86/kernel/process.c:copy_thread
```
```
In arch/x86/kernel/fpu/core.c (ffffffff822205f0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu_idle_fpregs
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu__clear_user_states
  - arch/x86/kernel/fpu/core.c:fpu_reset_fpregs
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_clone
  - arch/x86/kernel/fpu/core.c:fpu_copy_uabi_to_guest_fpstate
  - arch/x86/kernel/fpu/core.c:fpu_copy_guest_fpstate_to_uabi
  - arch/x86/kernel/fpu/core.c:fpu_alloc_guest_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:restore_fpregs_from_fpstate
  - arch/x86/kernel/fpu/core.c:save_fpregs_to_fpstate
```
```
In arch/x86/kernel/fpu/regset.c (ffffffff8106b002)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/regset.c:fpregs_set
  - arch/x86/kernel/fpu/regset.c:fpregs_get
  - arch/x86/kernel/fpu/regset.c:ssp_set
  - arch/x86/kernel/fpu/regset.c:ssp_get
  - arch/x86/kernel/fpu/regset.c:xstateregs_set
  - arch/x86/kernel/fpu/regset.c:xstateregs_get
  - arch/x86/kernel/fpu/regset.c:xfpregs_set
  - arch/x86/kernel/fpu/regset.c:xfpregs_get
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff838cc11c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__get_fpstate_size
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu_restore_sig
  - arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:save_xstate_epilog
  - arch/x86/kernel/fpu/signal.c:os_xrstor_safe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106d905)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:__xstate_request_perm
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:validate_independent_components
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:arch_set_user_pkey_access
  - arch/x86/kernel/fpu/xstate.c:__raw_xsave_addr
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__resume_cpu
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:init_xstate_size
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:paranoid_xstate_size_valid
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
  - arch/x86/kernel/fpu/xstate.c:xfeature_get_offset
```
```
In arch/x86/kernel/tboot.c (ffffffff81070c58)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tboot.c:map_tboot_page
  - arch/x86/kernel/tboot.c:p4d_offset
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8107380e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff838ce648)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cet_disable
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff838d0699)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:bhi_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:update_spec_ctrl_cond
```
```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078f85)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107be7c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:get_this_hybrid_cpu_type
```
```
In arch/x86/kernel/cpu/tsx.c (ffffffff8107bfe3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_dev_mode_disable
  - arch/x86/kernel/cpu/tsx.c:tsx_clear_cpuid
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107c585)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:amd_get_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:amd_set_dr_addr_mask
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e6f3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d24d5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_init_device
  - arch/x86/kernel/cpu/mce/core.c:mce_reenable_cpu
  - arch/x86/kernel/cpu/mce/core.c:vendor_disable_error_reporting
  - arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init
  - arch/x86/kernel/cpu/mce/core.c:noist_exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_clear_banks
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
  - arch/x86/kernel/cpu/mce/core.c:msr_to_offset
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085898)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
  - arch/x86/kernel/cpu/mce/amd.c:_log_error_deferred
```
```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff838d2965)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108a0a3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff838d5973)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory
  - arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff838d7b68)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_drv_init
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109b24d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109b895)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_sgx2_ready
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d80b5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f255)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_init
```
```
In arch/x86/kernel/acpi/cppc.c (ffffffff810a1d7d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cppc.c:init_freq_invariance_cppc
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff822257a8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a62f5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:x86_die_flags
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff838ddde5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:start_sync_check_timer
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b184f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/ftrace.c (ffffffff810b41ac)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/ftrace.c:create_trampoline
```
```
In arch/x86/kernel/crash_core_64.c (ffffffff810b58e5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b5d11)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable
  - arch/x86/kernel/machine_kexec_64.c:p4d_offset
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810b8344)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/hpet.c (ffffffff838e96bd)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:mwait_pc10_supported
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0a4b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_kick_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/kvm.c:__send_ipi_mask
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2d00)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_set_pgd
  - arch/x86/kernel/paravirt.c:native_set_p4d
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/kernel/callthunks.c (ffffffff838ed01c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/callthunks.c:callthunks_patch_builtin_calls
```
```
In arch/x86/kernel/cet.c (ffffffff822235f0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/cet.c:exc_control_protection
```
```
In arch/x86/kernel/shstk.c (ffffffff810cad68)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/kernel/shstk.c:shstk_prctl
  - arch/x86/kernel/shstk.c:__ia32_sys_map_shadow_stack
  - arch/x86/kernel/shstk.c:__x64_sys_map_shadow_stack
  - arch/x86/kernel/shstk.c:wrss_control
  - arch/x86/kernel/shstk.c:shstk_free
  - arch/x86/kernel/shstk.c:restore_signal_shadow_stack
  - arch/x86/kernel/shstk.c:setup_signal_shadow_stack
  - arch/x86/kernel/shstk.c:shstk_setup
```
```
In arch/x86/mm/init.c (ffffffff810cca87)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:probe_page_size_mask
```
```
In arch/x86/mm/init_64.c (ffffffff810ce511)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:register_page_bootmem_memmap
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:preallocate_vmalloc_pages
  - arch/x86/mm/init_64.c:remove_pagetable
  - arch/x86/mm/init_64.c:remove_p4d_table
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:__init_extra_mapping
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:populate_extra_pmd
  - arch/x86/mm/init_64.c:set_pte_vaddr
  - arch/x86/mm/init_64.c:sync_global_pgds
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:sync_global_pgds_l5
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff810d0534)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:access_error
  - arch/x86/mm/fault.c:spurious_kernel_fault
  - arch/x86/mm/fault.c:spurious_kernel_fault_check
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:bad_area_access_error
  - arch/x86/mm/fault.c:dump_pagetable
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0d6d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:__ioremap_check_ram
  - arch/x86/mm/ioremap.c:p4d_offset
```
```
In arch/x86/mm/extable.c (ffffffff810d1f86)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
```
```
In arch/x86/mm/mmap.c (ffffffff810d271a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
```
In arch/x86/mm/pgtable.c (ffffffff810d2910)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_ctor
```
```
In arch/x86/mm/physaddr.c (ffffffff810d3d3d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/physaddr.c:__virt_addr_valid
  - arch/x86/mm/physaddr.c:__virt_addr_valid
```
```
In arch/x86/mm/tlb.c (ffffffff810d40f5)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:__flush_tlb_all
  - arch/x86/mm/tlb.c:native_flush_tlb_global
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
  - arch/x86/mm/tlb.c:flush_tlb_one_kernel
  - arch/x86/mm/tlb.c:__get_current_cr3_fast
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d6bca)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:populate_pgd
  - arch/x86/mm/pat/set_memory.c:lookup_pmd_address
  - arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd
  - arch/x86/mm/pat/set_memory.c:cpa_flush
  - arch/x86/mm/pat/set_memory.c:cpu_cache_has_invalidate_memregion
```
```
In arch/x86/mm/pat/memtype.c (ffffffff838f1445)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
  - arch/x86/mm/pat/memtype.c:pat_bp_init
```
```
In arch/x86/mm/pkeys.c (ffffffff838f3e65)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:create_init_pkru_value
  - arch/x86/mm/pkeys.c:__arch_override_mprotect_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In arch/x86/mm/kaslr.c (ffffffff8222e391)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline_kaslr
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:kernel_randomize_memory
  - arch/x86/mm/kaslr.c:p4d_offset
```
```
In arch/x86/mm/pti.c (ffffffff810e0eb6)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810e0f70)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:print_mem_encrypt_feature_info
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810e1150)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:amd_enc_cache_flush_required
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff838f5688)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8654)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f1bc2)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:emit_return
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
  - arch/x86/net/bpf_jit_comp.c:emit_indirect_jump
```
```
In kernel/fork.c (ffffffff810fa8d3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
  - kernel/fork.c:alloc_thread_stack_node
```
```
In kernel/resource.c (ffffffff8110b603)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
```
```
In kernel/sched/core.c (ffffffff811440d0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/sched/core.c:sync_core_before_usermode
  - kernel/sched/core.c:sync_core_before_usermode
```
```
In kernel/sched/build_utility.c (ffffffff8118508b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:ipi_sync_core
  - kernel/sched/build_utility.c:ipi_sync_core
```
```
In kernel/power/snapshot.c (ffffffff811a79a7)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:swsusp_free
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:clear_or_poison_free_pages
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
```
```
In kernel/module/main.c (ffffffff811f41cb)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/module/main.c:module_alloc
```
```
In kernel/crash_core.c (ffffffff83906b81)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
  - kernel/crash_core.c:crash_save_vmcoreinfo_init
```
```
In kernel/kexec_core.c (ffffffff8122b97f)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
  - kernel/kexec_core.c:kimage_alloc_crash_control_pages
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/debug/kdb/kdb_support.c (ffffffff81275115)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
  - kernel/debug/kdb/kdb_support.c:kdb_getphys
```
```
In kernel/bpf/syscall.c (ffffffff8130a054)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_map_area_alloc
```
```
In kernel/events/core.c (ffffffff813961d6)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
  - kernel/events/core.c:perf_virt_to_phys
  - kernel/events/core.c:p4d_offset
```
```
In kernel/iomem.c (ffffffff813b0e61)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - kernel/iomem.c:memunmap
  - kernel/iomem.c:try_ram_remap
  - kernel/iomem.c:try_ram_remap
```
```
In mm/filemap.c (ffffffff813ba5b7)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/filemap.c:migration_entry_wait_on_locked
```
```
In mm/vmscan.c (ffffffff813cf535)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/vmscan.c:should_clear_pmd_young
```
```
In mm/util.c (ffffffff813ee05c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/util.c:kvmalloc_node
```
```
In mm/mm_init.c (ffffffff83912d1d)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:init_unavailable_range
  - mm/mm_init.c:reserve_bootmem_region
  - mm/mm_init.c:reserve_bootmem_region
```
```
In mm/percpu.c (ffffffff813f6ac0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/percpu.c:p4d_offset
  - mm/percpu.c:pcpu_populate_pte
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_embed_first_chunk
```
```
In mm/compaction.c (ffffffff814059b0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_migratepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:fast_isolate_freepages
```
```
In mm/gup.c (ffffffff814124d8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/gup.c:lockless_pages_from_mm
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:gup_pte_range
  - mm/gup.c:gup_pte_range
  - mm/gup.c:fixup_user_fault
  - mm/gup.c:check_vma_flags
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_mask
  - mm/gup.c:follow_page_pte
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814154c0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/memory.c:generic_access_phys
  - mm/memory.c:follow_phys
  - mm/memory.c:follow_pte
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:__p4d_alloc
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_numa_page
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:walk_to_pmd
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:copy_present_pte
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:free_p4d_range
  - mm/memory.c:pgd_populate
  - mm/memory.c:pgd_populate
  - mm/memory.c:pfn_swap_entry_to_page
```
```
In mm/mmap.c (ffffffff8142d20a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In mm/mprotect.c (ffffffff8142e9ce)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_free
  - mm/mprotect.c:__x64_sys_pkey_free
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:__do_sys_pkey_alloc
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:do_mprotect_pkey
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/mremap.c (ffffffff81430f5b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mremap.c:get_old_pud
  - mm/mremap.c:get_old_pud
```
```
In mm/page_vma_mapped.c (ffffffff814342e2)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:check_pte
  - mm/page_vma_mapped.c:p4d_offset
```
```
In mm/pagewalk.c (ffffffff81434ee8)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:walk_pgd_range
  - mm/pagewalk.c:p4d_offset
```
```
In mm/pgtable-generic.c (ffffffff814358b9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pgd_clear_bad
  - mm/pgtable-generic.c:pgd_clear_bad
```
```
In mm/rmap.c (ffffffff8143b0be)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:mm_find_pmd
  - mm/rmap.c:p4d_offset
```
```
In mm/vmalloc.c (ffffffff81441d29)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:pvm_determine_end_from_reverse
  - mm/vmalloc.c:vmalloc_32_user
  - mm/vmalloc.c:vmalloc_user
  - mm/vmalloc.c:vmalloc_huge
  - mm/vmalloc.c:__vmalloc_node
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:vmap_pfn_apply
  - mm/vmalloc.c:get_vm_area_caller
  - mm/vmalloc.c:get_vm_area
  - mm/vmalloc.c:vm_map_ram
  - mm/vmalloc.c:vm_unmap_ram
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmalloc_to_page
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_small_pages_range_noflush
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:vmap_pages_pud_range
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/vmalloc.c:vmap_range_noflush
  - mm/vmalloc.c:is_vmalloc_addr
  - mm/vmalloc.c:vm_area_register_early
```
```
In mm/page_alloc.c (ffffffff81449b5b)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/page_alloc.c:unreserve_highatomic_pageblock
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:__pageblock_pfn_to_page
  - mm/page_alloc.c:free_pcppages_bulk
  - mm/page_alloc.c:set_pfnblock_flags_mask
```
```
In mm/memory_hotplug.c (ffffffff8222a030)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:mhp_get_pluggable_range
  - mm/memory_hotplug.c:adjust_present_page_count
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:pfn_to_online_page
  - mm/memory_hotplug.c:pfn_to_online_page
```
```
In mm/swapfile.c (ffffffff8391a869)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
  - mm/swapfile.c:unuse_vma
```
```
In mm/hugetlb.c (ffffffff8147b041)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_offset
  - mm/hugetlb.c:huge_pte_alloc
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/sparse.c (ffffffff81488b93)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:offline_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:online_mem_sections
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:check_usemap_section_nr
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
  - mm/sparse.c:memory_present
  - mm/sparse.c:subsection_map_init
```
```
In mm/sparse-vmemmap.c (ffffffff822329c3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
```
In mm/ksm.c (ffffffff8148fef6)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:write_protect_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate.c (ffffffff81497b49)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149e3d9)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:migrate_vma_collect_pmd
  - mm/migrate_device.c:p4d_alloc
  - mm/migrate_device.c:p4d_alloc
```
```
In mm/huge_memory.c (ffffffff814a8ca0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
  - mm/huge_memory.c:follow_devmap_pmd
```
```
In mm/khugepaged.c (ffffffff814afe23)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/memcontrol.c (ffffffff814b45ba)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In mm/memory-failure.c (ffffffff814c91af)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:check_hwpoisoned_entry
  - mm/memory-failure.c:p4d_offset
```
```
In mm/userfaultfd.c (ffffffff814cfbc1)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/userfaultfd.c:mm_alloc_pmd
  - mm/userfaultfd.c:p4d_offset
```
```
In mm/hmm.c (ffffffff814d5a9c)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pmd
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7a1e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:wp_clean_pmd_entry
  - mm/mapping_dirty_helpers.c:wp_pte
```
```
In mm/bootmem_info.c (ffffffff83920653)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
  - mm/bootmem_info.c:register_page_bootmem_info_node
```
```
In fs/userfaultfd.c (ffffffff81557e30)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/userfaultfd.c:p4d_offset
```
```
In fs/proc/task_mmu.c (ffffffff8159ee38)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pagemap_pmd_range
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:pte_to_pagemap_entry
  - fs/proc/task_mmu.c:clear_soft_dirty
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:smaps_pte_entry
```
```
In fs/proc/meminfo.c (ffffffff815af8a3)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/proc/meminfo.c:meminfo_proc_show
```
```
In fs/proc/kcore.c (ffffffff83923cb7)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:get_kcore_size
```
```
In drivers/idle/intel_idle.c (ffffffff819e117e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:state_update_enter_method
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/acpi/sleep.c (ffffffff819e6ca0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In drivers/acpi/acpica/hwesleep.c (ffffffff81a316ae)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep
```
```
In drivers/acpi/acpica/hwsleep.c (ffffffff81a33657)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep
```
```
In drivers/acpi/processor_idle.c (ffffffff822263ef)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_idle_enter_s2idle
  - drivers/acpi/processor_idle.c:acpi_idle_enter
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b2ad)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffffffff81acc189)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
  - drivers/xen/swiotlb-xen.c:is_xen_swiotlb_buffer
```
```
In drivers/char/random.c (ffffffff839485bc)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
```
```
In drivers/iommu/amd/init.c (ffffffff81b5a135)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:amd_iommu_v2_supported
  - drivers/iommu/amd/init.c:early_amd_iommu_init
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6c2bd)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_check
  - drivers/iommu/intel/svm.c:intel_svm_check
```
```
In drivers/base/node.c (ffffffff81bb67a0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/base/node.c:register_mem_block_under_node_early
  - drivers/base/node.c:register_mem_block_under_node_early
```
```
In drivers/base/memory.c (ffffffff839519fc)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/base/memory.c:add_boot_memory_block
```
```
In drivers/gpu/drm/drm_cache.c (ffffffff81c81465)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_cache.c:drm_memcpy_init_early
  - drivers/gpu/drm/drm_cache.c:drm_clflush_virt_range
  - drivers/gpu/drm/drm_cache.c:drm_clflush_sg
  - drivers/gpu/drm/drm_cache.c:drm_clflush_pages
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e09885)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
```
```
In drivers/md/dm-stats.c (ffffffff81e3d0cb)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:__check_shared_memory
```
```
In drivers/edac/edac_mc.c (ffffffff81e410b4)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
  - drivers/edac/edac_mc.c:edac_mc_scrub_block
```
```
In drivers/firmware/efi/unaccepted_memory.c (ffffffff81e8c73a)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
```
```
In drivers/ras/cec.c (ffffffff81eaf380)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
  - drivers/ras/cec.c:cec_add_elem
```
```
In net/sched/sch_api.c (ffffffff83968522)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - net/sched/sch_api.c:pktsched_init
```
```
In arch/x86/power/hibernate_64.c (ffffffff8217505e)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
  - arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping
```
```
In arch/x86/power/hibernate.c (ffffffff821761c0)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:p4d_offset
```
```
In arch/x86/lib/copy_mc.c (ffffffff821a49db)
Location: arch/x86/include/asm/cpufeature.h:171
Inline: True
Inline callers:
  - arch/x86/lib/copy_mc.c:copy_mc_to_user
  - arch/x86/lib/copy_mc.c:copy_mc_to_kernel
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
In arch/x86/kernel/process_64.c (ffffffff810301e5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff81032091)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff810372b4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828994e3)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8103d959)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e835)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810401d5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040fe5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047788)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8289d552)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b15)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105574c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a733ce)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c572)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a1c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff8107cd54)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107d939)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff8107f8d5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828adfdb)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81080f05)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff8108284a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff810866da)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8108726c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a13e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108d18e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff8108dc3d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b01dd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828b0929)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090804)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828b2d9c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096de1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/core.c (ffffffff810ce06a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff81262b46)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In lib/random32.c (ffffffff81519480)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815c8aa9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff816850b5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff816b7925)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In arch/x86/power/cpu.c (ffffffff818a8d3f)
Location: arch/x86/include/asm/cpufeature.h:173
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
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff8288b59f)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits
```
```
In arch/x86/kernel/process_64.c (ffffffff8101fc40)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff8102176e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff81026c39)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff82891789)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8102d04e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8102e035)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff8102f9d5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff810307c5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810369f1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff8289573a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81042505)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045875)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f77e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105cd03)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f0ac)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/paravirt.c (ffffffff810676fc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
```
```
In arch/x86/mm/init.c (ffffffff8106c4c4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff81a27927)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:__set_pte_vaddr
  - arch/x86/mm/init_64.c:fill_pud
  - arch/x86/mm/init_64.c:sync_global_pgds_l4
  - arch/x86/mm/init_64.c:kernel_ident_mapping_init
```
```
In arch/x86/mm/fault.c (ffffffff8106e945)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:vmalloc_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828a61de)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff8106fe55)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff81070bcf)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:populate_pgd
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff810753e8)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff81075e3c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/kmmio.c (ffffffff81078bde)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mpx.c (ffffffff8107bcbe)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/kaslr.c (ffffffff81a27d9e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/kaslr.c:init_trampoline
```
```
In arch/x86/mm/pti.c (ffffffff8107c75d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
  - arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a83ca)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828a8aae)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f314)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828aaf1d)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
```
```
In kernel/fork.c (ffffffff81085861)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/core.c (ffffffff810bc932)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/memory.c (ffffffff8124d0c3)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/memory.c:__pud_alloc
  - mm/memory.c:free_pgd_range
```
```
In mm/mmap.c (ffffffff81254f66)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In mm/pgtable-generic.c (ffffffff8125d1ba)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/pgtable-generic.c:p4d_clear_bad
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a672)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_p4d_populate
```
```
In lib/random32.c (ffffffff81509770)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b19)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff81662d55)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff81695565)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In arch/x86/power/cpu.c (ffffffff81863a77)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
```
```
In arch/x86/power/hibernate_64.c (ffffffff81863e8b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
```
In arch/x86/power/hibernate.c (0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
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
In arch/x86/kernel/process_64.c (ffffffff81030045)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff81031ef1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff81037114)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4c3)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8103d799)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103e675)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff81040015)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81040e25)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810475c8)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b0515)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810529c5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055b7c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf7de)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106ca22)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff810779cc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff8107cd04)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107d8e9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff8107f885)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0eda)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81080eb5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff810827fa)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff8108668a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8108721c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0ee)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108d13e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff8108dbed)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c30dc)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c3828)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810907b4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c5c9b)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff81096d91)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/core.c (ffffffff810cd49a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff812608e6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In lib/random32.c (ffffffff81515510)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815c9039)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff816b34a5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff816e5df5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In arch/x86/power/cpu.c (ffffffff818fa39f)
Location: arch/x86/include/asm/cpufeature.h:173
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
In arch/x86/kernel/process_64.c (ffffffff81030e95)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/traps.c (ffffffff81032dc1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
  - arch/x86/kernel/traps.c:do_bounds
```
```
In arch/x86/kernel/ldt.c (ffffffff81038114)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/espfix_64.c (ffffffff828ac4e1)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_bsp
```
```
In arch/x86/kernel/process.c (ffffffff8103e8b5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
  - arch/x86/kernel/process.c:speculation_ctrl_update
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103f825)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:switch_fpu_return
  - arch/x86/kernel/fpu/core.c:fpu__clear
  - arch/x86/kernel/fpu/core.c:fpu__copy
  - arch/x86/kernel/fpu/core.c:fpstate_init
  - arch/x86/kernel/fpu/core.c:fpu__save
  - arch/x86/kernel/fpu/core.c:kernel_fpu_begin
```
```
In arch/x86/kernel/fpu/signal.c (ffffffff810413e5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/signal.c:fpu__alloc_mathframe
  - arch/x86/kernel/fpu/signal.c:fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:__fpu__restore_sig
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
  - arch/x86/kernel/fpu/signal.c:copy_fpstate_to_sigframe
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81042205)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/fpu/xstate.c:fpstate_sanitize_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810489d8)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b0543)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
  - arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81053e45)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105701c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81aebfae)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e122)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079a6c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
  - arch/x86/kernel/paravirt.c:native_flush_tlb_global
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_flush_tlb
  - arch/x86/kernel/paravirt.c:native_set_p4d
```
```
In arch/x86/mm/init.c (ffffffff8107ee04)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/init.c:init_mem_mapping
```
```
In arch/x86/mm/init_64.c (ffffffff8107f9d9)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__set_pte_vaddr
```
```
In arch/x86/mm/fault.c (ffffffff810819ad)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/ioremap.c (ffffffff828c4025)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/extable.c (ffffffff81082fd5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
  - arch/x86/mm/extable.c:ex_handler_fprestore
```
```
In arch/x86/mm/pageattr.c (ffffffff8108491a)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:cpa_flush
  - arch/x86/mm/pageattr.c:__cpa_flush_tlb
```
```
In arch/x86/mm/pgtable.c (ffffffff810887ca)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pgd_alloc
```
```
In arch/x86/mm/tlb.c (ffffffff8108934c)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:do_kernel_range_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:initialize_tlbstate_and_flush
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
  - arch/x86/mm/tlb.c:load_new_mm_cr3
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c38e)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
```
In arch/x86/mm/mpx.c (ffffffff8108f4de)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mpx.c:mpx_disable_management
  - arch/x86/mm/mpx.c:mpx_enable_management
```
```
In arch/x86/mm/pti.c (ffffffff8108ffcd)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_finalize
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6282)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
  - arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem
```
```
In arch/x86/mm/mem_encrypt_identity.c (ffffffff828c69ce)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_identity.c:sme_prepare_pgd
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092b94)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8e41)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
```
```
In kernel/fork.c (ffffffff8109ec31)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
  - kernel/fork.c:dup_mmap
```
```
In kernel/sched/core.c (ffffffff810d47e4)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:finish_task_switch
```
```
In mm/mmap.c (ffffffff812702b6)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - mm/mmap.c:__do_munmap
```
```
In lib/random32.c (ffffffff8152eca0)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - lib/random32.c:__extract_hwseed
  - lib/random32.c:__extract_hwseed
```
```
In drivers/idle/intel_idle.c (ffffffff815e2e99)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/char/random.c (ffffffff816cda25)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:extract_buf
  - drivers/char/random.c:add_interrupt_randomness
  - drivers/char/random.c:_extract_crng
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:crng_initialize
```
```
In drivers/iommu/intel-svm.c (ffffffff817004f5)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
Inline callers:
  - drivers/iommu/intel-svm.c:intel_svm_init
```
```
In arch/x86/power/cpu.c (ffffffff8191b4ff)
Location: arch/x86/include/asm/cpufeature.h:173
Inline: True
```
</details>
</li>
</ul>

## Differences
