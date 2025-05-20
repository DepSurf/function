# Function: <code>__write_cr4</code>

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
In arch/x86/events/core.c (ffffffff810058b1)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/xen/enlighten.c (ffffffff8101cdd2)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81039279)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:disable_TSC
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81039908)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8103b774)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040e3f)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cpu_init
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104548e)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c080)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
```
```
In arch/x86/kernel/reboot.c (ffffffff81050323)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d6c9)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:kdump_nmi_callback
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In arch/x86/mm/init.c (ffffffff8107d4b7)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In kernel/sched/core.c (ffffffff8181fcb1)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:idle_task_exit
```
```
In mm/mmu_context.c (ffffffff811afcdc)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffffffff8121380c)
Location: arch/x86/include/asm/paravirt.h:98
Inline: True
```
```
In arch/x86/power/cpu.c (ffffffff816fb0bc)
Location: arch/x86/include/asm/paravirt.h:98
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
In arch/x86/events/core.c (ffffffff81005b41)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/xen/enlighten.c (ffffffff8101bff2)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81038416)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810388f8)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81f91d76)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81041063)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045549)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c1f9)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff8105053f)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff8105d7db)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107ef94)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810724c0)
Location: arch/x86/include/asm/paravirt.h:88
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8176031c)
Location: arch/x86/include/asm/paravirt.h:88
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
In arch/x86/events/core.c (ffffffff81005a81)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/xen/enlighten.c (ffffffff8101c802)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
```
```
In arch/x86/kernel/process.c (ffffffff81037ea8)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81038318)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81fcd026)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81040ab0)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047159)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e649)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff81052daf)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/crash.c (ffffffff81060858)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff81083644)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81076054)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8178d31c)
Location: arch/x86/include/asm/paravirt.h:79
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
In arch/x86/events/core.c (ffffffff810057cf)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff81036074)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810364f8)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff820add49)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8103ea33)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810469e9)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e5b9)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff810528b6)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105319b)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8105f92e)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8106b953)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8107477a)
Location: arch/x86/include/asm/paravirt.h:79
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff817ab499)
Location: arch/x86/include/asm/paravirt.h:79
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
In arch/x86/events/core.c (ffffffff81005c01)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810383ff)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810388ba)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826b42cc)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104170e)
Location: arch/x86/include/asm/paravirt.h:75
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a44b)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051f29)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff810565f2)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81056ee9)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81057740)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/crash.c (ffffffff81063979)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff810701f4)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8107a57f)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff81822999)
Location: arch/x86/include/asm/paravirt.h:75
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
In arch/x86/events/core.c (ffffffff810063c6)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff810397d7)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81039dea)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff826ddaa0)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81042fde)
Location: arch/x86/include/asm/paravirt.h:75
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104cafa)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054bd9)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff810593f2)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81059d51)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105a619)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/crash.c (ffffffff8106661c)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff810730f5)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8107d2ea)
Location: arch/x86/include/asm/paravirt.h:75
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8186cbb9)
Location: arch/x86/include/asm/paravirt.h:75
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
In arch/x86/events/core.c (ffffffff81006316)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103ab2e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103b30a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff82893ee8)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81044646)
Location: arch/x86/include/asm/paravirt.h:137
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104a1da)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81052299)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff8105f0a2)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff8105f9d1)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81060299)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:start_secondary
```
```
In arch/x86/kernel/crash.c (ffffffff8106c63b)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107918f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81083dee)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8188cbc9)
Location: arch/x86/include/asm/paravirt.h:137
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
In arch/x86/events/core.c (ffffffff81006526)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d180)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103d93a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab673)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81046bf4)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d35a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055399)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff810628cc)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062e31)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107063a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107cd8f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81087a47)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818d76ab)
Location: arch/x86/include/asm/paravirt.h:137
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
In arch/x86/events/core.c (ffffffff8100658f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d940)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e0fa)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae6ac)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047374)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dcfa)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c99)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff8106313c)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810634f1)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107163a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107de2f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8108870b)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8190970b)
Location: arch/x86/include/asm/paravirt.h:137
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
In arch/x86/kernel/process.c (ffffffff81040aad)
Location: arch/x86/include/asm/paravirt.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104a256)
Location: arch/x86/include/asm/paravirt.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105ae07)
Location: arch/x86/include/asm/paravirt.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81bba2bd)
Location: arch/x86/include/asm/paravirt.h:143
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
In arch/x86/kernel/process.c (ffffffff81040a06)
Location: arch/x86/include/asm/paravirt.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810496f6)
Location: arch/x86/include/asm/paravirt.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81059967)
Location: arch/x86/include/asm/paravirt.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81bceb2d)
Location: arch/x86/include/asm/paravirt.h:143
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
In arch/x86/kernel/process.c (ffffffff810423fe)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8104ae76)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a2e7)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81bc24dd)
Location: arch/x86/include/asm/paravirt.h:160
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
In arch/x86/kernel/process.c (ffffffff8104874b)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81051f13)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81063737)
Location: arch/x86/include/asm/paravirt.h:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81c92b6b)
Location: arch/x86/include/asm/paravirt.h:160
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
In arch/x86/kernel/process.c (ffffffff81051a3f)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8105d803)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810703ed)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/power/cpu.c (ffffffff81e424da)
Location: arch/x86/include/asm/paravirt.h:166
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
In arch/x86/kernel/process.c (ffffffff8105f0bb)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac72)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106bd43)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/power/cpu.c (ffffffff8201ceba)
Location: arch/x86/include/asm/paravirt.h:166
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
In arch/x86/kernel/process.c (ffffffff810607bb)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c5e2)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff8106d6e8)
Location: arch/x86/include/asm/paravirt.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_update_irqsoff
```
```
In arch/x86/power/cpu.c (ffffffff8209d54a)
Location: arch/x86/include/asm/paravirt.h:166
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
In arch/x86/kernel/process.c (ffffffff81067866)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073832)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81074938)
Location: arch/x86/include/asm/paravirt.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cr4_init
  - arch/x86/kernel/cpu/common.c:cr4_set_bits
```
```
In arch/x86/power/cpu.c (ffffffff82174d4a)
Location: arch/x86/include/asm/paravirt.h:168
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
In arch/x86/events/core.c (ffffffff8100658f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103dac0)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e27a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c6cb)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff810474f4)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104de5a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055819)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff81062c2c)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81062fe1)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107063a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107ce2f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8108770b)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818a8acb)
Location: arch/x86/include/asm/paravirt.h:137
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
In arch/x86/events/core.c (ffffffff810044af)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8102d15e)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8102da8c)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828948c6)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81036668)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d2fc)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045961)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff81052fc3)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff810532f6)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8106061e)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8106c591)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff8107637c)
Location: arch/x86/include/asm/special_insns.h:177
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8186378c)
Location: arch/x86/include/asm/special_insns.h:177
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
In arch/x86/events/core.c (ffffffff8100654f)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103d900)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103e0ba)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af68e)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81047334)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dcaa)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c49)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff810630dc)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81063491)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff8107063a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107cddf)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff810876bb)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff818fa12b)
Location: arch/x86/include/asm/paravirt.h:137
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
In arch/x86/events/core.c (ffffffff810066af)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/events/core.c:refresh_pce
```
```
In arch/x86/kernel/process.c (ffffffff8103ea19)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:__switch_to_xtra
  - arch/x86/kernel/process.c:set_tsc_mode
  - arch/x86/kernel/process.c:disable_TSC
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8103f23a)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff828af6bc)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
```
In arch/x86/kernel/cpu/common.c (ffffffff81048734)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:cr4_init
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f0ea)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810570e9)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/reboot.c (ffffffff8106469c)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
  - arch/x86/kernel/reboot.c:vmxoff_nmi
```
```
In arch/x86/kernel/smp.c (ffffffff81064a51)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
```
In arch/x86/kernel/crash.c (ffffffff81072654)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
  - arch/x86/kernel/crash.c:kdump_nmi_callback
```
```
In arch/x86/mm/init.c (ffffffff8107eedf)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/init.c:cr4_set_bits
```
```
In arch/x86/mm/tlb.c (ffffffff81089807)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In arch/x86/power/cpu.c (ffffffff8191b28b)
Location: arch/x86/include/asm/paravirt.h:137
Inline: True
```
</details>
</li>
</ul>

## Differences
