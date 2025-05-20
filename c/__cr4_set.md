# Function: <code>__cr4_set</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005bf9)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810383f7)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810388b2)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b42c4)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041706)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a443)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810565ea)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81056ee1)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81063971)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff810701ec)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8107a577)
Location: arch/x86/include/asm/tlbflush.h:250
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff810063be)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810397cf)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81039de2)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826dda98)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042fd6)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104caf2)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810593ea)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059d49)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81066614)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff810730ed)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8107d2e2)
Location: arch/x86/include/asm/tlbflush.h:295
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff8100630e)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103ab26)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103b302)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893ee0)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104463e)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a1d2)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f09a)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105f9c9)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106c633)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff81079187)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81083de6)
Location: arch/x86/include/asm/tlbflush.h:283
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff8100651e)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d178)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103d932)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab66b)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046bec)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d352)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810628c4)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062e29)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070632)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107cd87)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81087a3f)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff81006587)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d938)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e0f2)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae6a4)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104736c)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dcf2)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81063134)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810634e9)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81071632)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107de27)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81088703)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff81006587)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103dab8)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e272)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c6c3)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474ec)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de52)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c24)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062fd9)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070632)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107ce27)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81087703)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff810044a7)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8102d156)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8102da84)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828948be)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036660)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d2f4)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81052fbb)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810532ee)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81060616)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8106c589)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81076374)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff81006547)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d8f8)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e0b2)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af686)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104732c)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dca2)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff810630d4)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81063489)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81070632)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107cdd7)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810876b3)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/events/core.c (ffffffff810066a7)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103ea11)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103f232)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af6b4)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104872c)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f0e2)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
```
```
In arch/x86/kernel/reboot.c (ffffffff81064694)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81064a49)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107264c)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107eed7)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810897ff)
Location: arch/x86/include/asm/tlbflush.h:285
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
</ul>

## Differences
