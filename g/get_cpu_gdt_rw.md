# Function: <code>get_cpu_gdt_rw</code>

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
In arch/x86/entry/vdso/vma.c (ffffffff81003d06)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101ec13)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102954a)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ebb4)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81052052)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81053f78)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066b10)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/power/cpu.c (ffffffff817ab57a)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff81003f56)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f6c4)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102976f)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104183b)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81055cbe)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057d27)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106ac80)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff826c3b4f)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff81822a12)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/entry/vdso/vma.c (ffffffff810047cc)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:vgetcpu_cpu_init
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff81020d00)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a19f)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810430ec)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058b5e)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105aa5f)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106d940)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff826eddef)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff8186cc32)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff8101fbe0)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102a7ef)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044604)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e78a)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff810606df)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073ae0)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828a4b1a)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff8188cc42)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff81021930)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102c646)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046bab)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061bae)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81063e91)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077650)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828bd030)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff818d7539)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022270)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102cf16)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104732b)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106245e)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064536)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810786c0)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c34ba)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff81909a18)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff81024f00)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ee90)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103df64)
Location: arch/x86/include/asm/desc.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b11b)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106842c)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106af8f)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107fb40)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff82ce6786)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
```
In arch/x86/power/cpu.c (ffffffff81bba033)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff81025c1c)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102fca0)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103dffd)
Location: arch/x86/include/asm/desc.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a7ec)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a10c)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106cbff)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8107f760)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff82fd40d7)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
```
In arch/x86/power/cpu.c (ffffffff81bce8a3)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102763c)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff810307b0)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103f966)
Location: arch/x86/include/asm/desc.h:50
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c0b6)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106abdc)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d6a3)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81080860)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff831deb14)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
```
In arch/x86/power/cpu.c (ffffffff81bc2253)
Location: arch/x86/include/asm/desc.h:50
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff8102bb4f)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103568a)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81045768)
Location: arch/x86/include/asm/desc.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810531e9)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8107552f)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81078de9)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff8108f780)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff832c201e)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
```
In arch/x86/power/cpu.c (ffffffff81c9283c)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103053d)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8103b4c5)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104e308)
Location: arch/x86/include/asm/desc.h:51
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105ec69)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81083f94)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81087bdf)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810a0490)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff834746f0)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_area
```
```
In arch/x86/power/cpu.c (ffffffff81e41fb6)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff81037b3d)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043c95)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b1ca)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d3b8)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096e24)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109b56f)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810b8070)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff83e9c75b)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff8201c7b6)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff81037a77)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff81043da9)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105c70a)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106ed48)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/paravirt.c (ffffffff810bb220)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff836c027b)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff8209ce46)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff8103ddc7)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a2d8)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/kernel/hw_breakpoint.c (ffffffff810637ca)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810760a8)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
  - arch/x86/kernel/cpu/common.c:switch_gdt_and_percpu_base
```
```
In arch/x86/kernel/paravirt.c (ffffffff810c2630)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff838f0d9b)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff821749b6)
Location: arch/x86/include/asm/desc.h:51
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:fix_processor_context
  - arch/x86/power/cpu.c:fix_processor_context
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
In arch/x86/xen/enlighten_pv.c (ffffffff810223d0)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102d076)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474ab)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061fde)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064026)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff810776c0)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828ae490)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff818a8dd8)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8101f9fe)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/ldt.c (ffffffff81026caf)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:flush_ldt
  - arch/x86/kernel/ldt.c:flush_ldt
```
```
In arch/x86/kernel/tls.c (ffffffff8103275c)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/tls.c:set_tls_desc
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036632)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81052392)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054326)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/tlb.c (ffffffff810760f2)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828a6682)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff818637f3)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:restore_processor_state
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff81022230)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102ced6)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810472eb)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810623fe)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff810644d6)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077670)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c138f)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff818fa438)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten_pv.c (ffffffff810224c0)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:load_TLS_descriptor
```
```
In arch/x86/xen/smp_pv.c (ffffffff8102dcc6)
Location: arch/x86/include/asm/desc.h:55
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810486eb)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:load_direct_gdt
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810639be)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/smpboot.c (ffffffff81065a96)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079710)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_load_tls
```
```
In arch/x86/mm/cpu_entry_area.c (ffffffff828c44da)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
```
```
In arch/x86/power/cpu.c (ffffffff8191b598)
Location: arch/x86/include/asm/desc.h:55
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
</ul>

## Differences
