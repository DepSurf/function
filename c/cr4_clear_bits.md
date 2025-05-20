# Function: <code>cr4_clear_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff810058a9)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810392fb)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f69cce)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104112e)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81050300)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/crash.c (ffffffff8105d6aa)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/sched/core.c (ffffffff8181fca9)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afcd4)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff81213804)
Location: arch/x86/include/asm/tlbflush.h:53
Inline: True
```
**Symbols:**

```
ffffffff81050300-ffffffff8105032c: cr4_clear_bits.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005b39)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810383fa)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f91d4c)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041047)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81050520)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/crash.c (ffffffff8105d7bc)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff810724b8)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81050480-ffffffff810504ad: cr4_clear_bits.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005a79)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff81037e8c)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81fccffc)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040a94)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81052d90)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/crash.c (ffffffff81060839)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8107604c)
Location: arch/x86/include/asm/tlbflush.h:101
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81052cf0-ffffffff81052d1d: cr4_clear_bits.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff810057c7)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff81035ebc)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff820add1f)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ea17)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/reboot.c (ffffffff81052897)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
```
In arch/x86/kernel/smp.c (ffffffff8105317c)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8105f90b)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff81074772)
Location: arch/x86/include/asm/tlbflush.h:106
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81052800-ffffffff8105282e: cr4_clear_bits.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005bf9)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810381fe)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b429c)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810416e1)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810565c2)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81056eb9)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81063949)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8107a577)
Location: arch/x86/include/asm/tlbflush.h:270
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81056440-ffffffff81056485: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006396)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103937a)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826dda70)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042fb1)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810593c2)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81059d21)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff810665ec)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff8107d44a)
Location: arch/x86/include/asm/tlbflush.h:315
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff810591f0-ffffffff81059235: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810062e6)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103a5da)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893eb8)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044619)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f072)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff8105f9a1)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106c60b)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff81083dbe)
Location: arch/x86/include/asm/tlbflush.h:303
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff8105eef0-ffffffff8105ef35: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810064f6)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103cb8a)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab642)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046bc8)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81062881)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81062e01)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107060a)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/tlb.c (ffffffff81087a17)
Location: arch/x86/include/asm/tlbflush.h:305
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
**Symbols:**

```
ffffffff81062300-ffffffff81062345: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d34a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae67b)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047348)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff810630f1)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff810634c1)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107160a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81062b70-ffffffff81062bb5: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8104038d)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82cd3822)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104b12f)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81068d91)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff810692dc)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81078718)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81068c30-ffffffff81068c60: cr4_clear_bits (STB_LOCAL)
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
In arch/x86/kernel/process.c (ffffffff810402dd)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82fbf649)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a800)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106ac15)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:emergency_vmx_disable_all
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff8106aefc)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff8107871d)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81041cad)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff831c9c3f)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104c0ca)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8106b3b0)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff8106bce3)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
Direct callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff810792b0)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff8106b3b0-ffffffff8106b3e8: cr4_clear_bits (STB_LOCAL)
ffffffff8106ba20-ffffffff8106ba5a: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff810792b0-ffffffff810792ea: cr4_clear_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81039aa4)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process.c (ffffffff81047f7d)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff832ab04f)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81053424)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81075f10)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810767c3)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
Direct callers:
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
```
In arch/x86/kernel/crash.c (ffffffff81087310)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81075f10-ffffffff81075f4a: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff810764f0-ffffffff8107652a: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81087310-ffffffff8108734a: cr4_clear_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81040990)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process.c (ffffffff81050b70)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81e498ef)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d180)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81084c20)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810852c0)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
```
```
In arch/x86/kernel/crash.c (ffffffff81097250)
Location: arch/x86/include/asm/tlbflush.h:46
Inline: True
Direct callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81040990-ffffffff810409cb: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81050b70-ffffffff81050bab: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81e498ef-ffffffff81e49928: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff8105d180-ffffffff8105d1b9: cr4_clear_bits (STB_LOCAL)
ffffffff81084c20-ffffffff81084c5b: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff810852c0-ffffffff810852fb: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81097250-ffffffff8109728b: cr4_clear_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81049cb0)
Location: arch/x86/include/asm/tlbflush.h:47
Inline: True
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process.c (ffffffff8105e070)
Location: arch/x86/include/asm/tlbflush.h:47
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81063180)
Location: arch/x86/include/asm/tlbflush.h:47
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106b590)
Location: arch/x86/include/asm/tlbflush.h:47
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81097c50)
Location: arch/x86/include/asm/tlbflush.h:47
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
**Symbols:**

```
ffffffff81049cb0-ffffffff81049cef: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff8105e070-ffffffff8105e0af: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81063180-ffffffff810631bf: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff8106b590-ffffffff8106b5d3: cr4_clear_bits (STB_LOCAL)
ffffffff81097c50-ffffffff81097c8f: cr4_clear_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81049ee0)
Location: arch/x86/include/asm/tlbflush.h:50
Inline: True
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process.c (ffffffff8105f720)
Location: arch/x86/include/asm/tlbflush.h:50
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81064ad0)
Location: arch/x86/include/asm/tlbflush.h:50
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106cf40)
Location: arch/x86/include/asm/tlbflush.h:50
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff8109acf0)
Location: arch/x86/include/asm/tlbflush.h:50
Inline: True
Direct callers:
  - arch/x86/kernel/reboot.c:crash_nmi_callback
```
**Symbols:**

```
ffffffff81049ee0-ffffffff81049f1f: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff8105f720-ffffffff8105f75f: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81064ad0-ffffffff81064b0f: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff8106cf40-ffffffff8106cf83: cr4_clear_bits (STB_LOCAL)
ffffffff8109acf0-ffffffff8109ad2f: cr4_clear_bits.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/realmode/init.c (ffffffff81051140)
Location: arch/x86/include/asm/tlbflush.h:51
Inline: True
Direct callers:
  - arch/x86/realmode/init.c:load_trampoline_pgtable
```
```
In arch/x86/kernel/process.c (ffffffff810667d0)
Location: arch/x86/include/asm/tlbflush.h:51
Inline: True
Direct callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8106bf60)
Location: arch/x86/include/asm/tlbflush.h:51
Inline: True
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074710)
Location: arch/x86/include/asm/tlbflush.h:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81051140-ffffffff8105117f: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff810667d0-ffffffff8106680f: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff8106bf60-ffffffff8106bf9f: cr4_clear_bits.constprop.0 (STB_LOCAL)
ffffffff81074710-ffffffff81074753: cr4_clear_bits (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d4ca)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c69a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474c8)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81062be1)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81062fb1)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107060a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81062660-ffffffff810626a5: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102cb6a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828948a3)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036645)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81052f8e)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff810532d4)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff810605fc)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810529d0-ffffffff810529fd: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d30a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af65d)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047308)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81063091)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81063461)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107060a)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff81062b10-ffffffff81062b55: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cr4_clear_bits(long unsigned int mask);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e3fd)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:set_tsc_mode
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af68b)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048708)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/reboot.c (ffffffff81064651)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
Direct callers:
  - arch/x86/kernel/reboot.c:machine_real_restart
```
```
In arch/x86/kernel/smp.c (ffffffff81064a21)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81072624)
Location: arch/x86/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
**Symbols:**

```
ffffffff810640d0-ffffffff81064115: cr4_clear_bits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
