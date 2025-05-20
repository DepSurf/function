# Function: <code>native_read_cr4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_read_cr4();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b934)
Location: arch/x86/include/asm/special_insns.h:59
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064554)
Location: arch/x86/include/asm/special_insns.h:59
Inline: True
```
**Symbols:**

```
ffffffff8101c9a0-ffffffff8101c9a9: native_read_cr4 (STB_LOCAL)
ffffffff81064b30-ffffffff81064b39: native_read_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int native_read_cr4();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ad24)
Location: arch/x86/include/asm/special_insns.h:59
Inline: True
```
```
In arch/x86/kernel/paravirt.c (ffffffff810641a4)
Location: arch/x86/include/asm/special_insns.h:59
Inline: True
```
**Symbols:**

```
ffffffff8101bc10-ffffffff8101bc19: native_read_cr4 (STB_LOCAL)
ffffffff81064900-ffffffff81064909: native_read_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
long unsigned int native_read_cr4();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b450)
Location: arch/x86/include/asm/special_insns.h:54
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067690)
Location: arch/x86/include/asm/special_insns.h:54
Inline: False
```
**Symbols:**

```
ffffffff8101b450-ffffffff8101b459: native_read_cr4 (STB_LOCAL)
ffffffff81067690-ffffffff81067699: native_read_cr4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
long unsigned int native_read_cr4();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101e540)
Location: arch/x86/include/asm/special_insns.h:54
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066950)
Location: arch/x86/include/asm/special_insns.h:54
Inline: False
```
**Symbols:**

```
ffffffff8101e540-ffffffff8101e549: native_read_cr4 (STB_LOCAL)
ffffffff81066950-ffffffff81066959: native_read_cr4 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff826a34dc)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac75d)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8102b208)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff826b08e6)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104166e)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051e7f)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81055c73)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81056985)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81056e8c)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057736)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/crash.c (ffffffff8106388c)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff81073029)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8182288c)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
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
In arch/x86/kernel/head64.c (ffffffff826cc4b5)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d589e)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8102cf75)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff826d9f87)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042f3e)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054b2f)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058af3)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810597bd)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059cf4)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a616)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/crash.c (ffffffff8106653d)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff81075a00)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8186cacc)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
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
In arch/x86/kernel/head64.c (ffffffff828824c0)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b944)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8102e1c3)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff8289036c)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104451e)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810521ef)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e733)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f43d)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105f974)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060296)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/crash.c (ffffffff8106c54d)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8107b7c7)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8188cadc)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
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
In arch/x86/kernel/head64.c (ffffffff8289944c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2d7d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8102ff4c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff828a7b4d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81045b10)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810552dd)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061b33)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81062872)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062dd4)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107054d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8107f2ea)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818d744c)
Location: arch/x86/include/asm/special_insns.h:54
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
In arch/x86/kernel/head64.c (ffffffff8289c44c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5e30)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff810308ac)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff828aaba5)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046270)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055bdd)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810623e3)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff810630e2)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81063494)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107154d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8108037a)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff81909adc)
Location: arch/x86/include/asm/special_insns.h:54
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
In arch/x86/kernel/head64.c (ffffffff81000200)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccc11e)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81032ed3)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff82ccff98)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a220)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105ad96)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810683c1)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81068f95)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810692d1)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078709)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff81087208)
Location: arch/x86/include/asm/special_insns.h:55
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bba20c)
Location: arch/x86/include/asm/special_insns.h:55
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
In arch/x86/kernel/head64.c (ffffffff810002f0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7f5c)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81bd30f0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff82fbbdd8)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810496c0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810598f6)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a0a1)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106abfc)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106aef1)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff8107870e)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/sev-es.c (ffffffff81082554)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev-es.c:vc_handle_cpuid
```
```
In arch/x86/mm/fault.c (ffffffff81087888)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bcea81)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/kernel/head64.c (ffffffff810002f0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c269f)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81bc54e0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff831c6491)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104ae40)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a276)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106ab71)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b851)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8106bcd8)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff810795c5)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/sev.c (ffffffff810848ab)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
```
In arch/x86/mm/fault.c (ffffffff81088464)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81bc2431)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/kernel/head64.c (ffffffff810002f0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a308d)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81c98100)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff832a72f7)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81051ee0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810636c6)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810754d1)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8107634e)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810767b8)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81087625)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/sev.c (ffffffff81093a6b)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
```
```
In arch/x86/mm/fault.c (ffffffff81097804)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81c92a9d)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/kernel/head64.c (ffffffff81000340)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff834522b7)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81e4759e)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff834565fb)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d7d0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81070343)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81083f30)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81085098)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8108538f)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff8109778e)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/kernel/sev.c (ffffffff810a5c97)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:vc_handle_exitcode
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
```
In arch/x86/mm/fault.c (ffffffff810aa332)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff81e423e5)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/kernel/head64.c (ffffffff81000370)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6f0ee)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8104a1f1)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff83e74975)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106abb4)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106bd10)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096dc0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81097eaf)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/sev.c (ffffffff810bd5e0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
```
In arch/x86/mm/fault.c (ffffffff810c3d87)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff8201cdb5)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/xen/enlighten_pv.c (ffffffff83690038)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/head64.c (ffffffff81000480)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8104aa31)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff83696447)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c524)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d6c0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099ee0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff8109af58)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
```
In arch/x86/kernel/sev.c (ffffffff810c0c50)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
```
```
In arch/x86/mm/fault.c (ffffffff810c75c7)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff8209d445)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bfb88)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/head64.c (ffffffff81000490)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81051ca1)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff838c609d)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073774)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074910)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a1710)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/sev.c (ffffffff810c80b0)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:vc_handle_cpuid
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:snp_cpuid_postprocess
  - arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb
```
```
In arch/x86/mm/fault.c (ffffffff810cfa97)
Location: arch/x86/include/asm/special_insns.h:57
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:show_fault_oops
```
```
In arch/x86/power/cpu.c (ffffffff82174c45)
Location: arch/x86/include/asm/special_insns.h:57
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
In arch/x86/kernel/head64.c (ffffffff8288a44c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893e39)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff81030a0c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff82898bb5)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810463f0)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105575d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061f63)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81062bd2)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062f84)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107054d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8107f37a)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818a8e9c)
Location: arch/x86/include/asm/special_insns.h:54
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
In arch/x86/kernel/head64.c (ffffffff828883f0)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8102048e)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff82890ec5)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810356e0)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810458ef)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105231e)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f7f)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810532a7)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106053a)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8106e355)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff81863632)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
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
In arch/x86/kernel/head64.c (ffffffff8289d44c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6e30)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff8103086c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff828abba5)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046230)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055b8d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81062383)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81063082)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81063434)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107054d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8107f32a)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff818fa4fc)
Location: arch/x86/include/asm/special_insns.h:54
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
In arch/x86/kernel/head64.c (ffffffff8289d44c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:x86_64_start_kernel
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6e04)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
```
In arch/x86/kernel/process_64.c (ffffffff810316fc)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/setup.c (ffffffff828abbb5)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047630)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105702d)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81063943)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/kernel/reboot.c (ffffffff81064642)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810649f4)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81072567)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/fault.c (ffffffff8108141a)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:no_context
```
```
In arch/x86/power/cpu.c (ffffffff8191b65c)
Location: arch/x86/include/asm/special_insns.h:54
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
</ul>
