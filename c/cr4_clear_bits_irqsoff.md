# Function: <code>cr4_clear_bits_irqsoff</code>

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
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006570)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d35b)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae68c)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047359)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81063102)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810634d2)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107161b)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff810886ec)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
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
In arch/x86/kernel/process.c (ffffffff8104039e)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82cd382f)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b140)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81068da2)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810692ed)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078729)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8108adc7)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff810402ee)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82fbf656)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a811)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106ac24)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff8106af0d)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff8107872e)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8108af4e)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/kernel/process.c (ffffffff81041cbe)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff831c9c4c)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c0db)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b3c9)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:cr4_clear_bits
```
```
In arch/x86/kernel/smp.c (ffffffff8106bcf4)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff810792c6)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8108bac2)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/realmode/init.c (ffffffff81039ab5)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process.c (ffffffff81047f8e)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff832ab05c)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053435)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81075f26)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810767d4)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81087326)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff8109b0b3)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/realmode/init.c (ffffffff810409a4)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81050b84)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81e49903)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d197)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
```
```
In arch/x86/kernel/reboot.c (ffffffff81084c34)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/kernel/smp.c (ffffffff810852d4)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81097264)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810ae5ca)
Location: arch/x86/include/asm/tlbflush.h:30
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/realmode/init.c (ffffffff81049cc4)
Location: arch/x86/include/asm/tlbflush.h:31
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105e084)
Location: arch/x86/include/asm/tlbflush.h:31
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063194)
Location: arch/x86/include/asm/tlbflush.h:31
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106b5a7)
Location: arch/x86/include/asm/tlbflush.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
```
```
In arch/x86/kernel/reboot.c (ffffffff81097c64)
Location: arch/x86/include/asm/tlbflush.h:31
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810c87b7)
Location: arch/x86/include/asm/tlbflush.h:31
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/realmode/init.c (ffffffff81049ef4)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff8105f734)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064ae4)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cf57)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
```
```
In arch/x86/kernel/reboot.c (ffffffff8109ad04)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
```
```
In arch/x86/mm/tlb.c (ffffffff810cc0cf)
Location: arch/x86/include/asm/tlbflush.h:34
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/realmode/init.c (ffffffff81051154)
Location: arch/x86/include/asm/tlbflush.h:35
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff810667e4)
Location: arch/x86/include/asm/tlbflush.h:35
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106bf74)
Location: arch/x86/include/asm/tlbflush.h:35
Inline: True
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074727)
Location: arch/x86/include/asm/tlbflush.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_clear_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810d475f)
Location: arch/x86/include/asm/tlbflush.h:35
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:cr4_update_pce
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
In arch/x86/events/core.c (ffffffff81006570)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d4db)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c6ab)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474d9)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81062bf2)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062fc2)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107061b)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff810876ec)
Location: arch/x86/include/asm/tlbflush.h:303
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
In arch/x86/events/core.c (ffffffff81004490)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8102cb6d)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828948a6)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036648)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f91)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810532d7)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff810605ff)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8107635d)
Location: arch/x86/include/asm/tlbflush.h:303
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
In arch/x86/events/core.c (ffffffff81006530)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d31b)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af66e)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047319)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810630a2)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81063472)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107061b)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8108769c)
Location: arch/x86/include/asm/tlbflush.h:303
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
In arch/x86/events/core.c (ffffffff81006690)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103e40e)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af69c)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048719)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81064662)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81064a32)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81072635)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff810897e8)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
</details>
</li>
</ul>

## Differences
