# Function: <code>x86_this_cpu_constant_test_bit</code>

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
In arch/x86/kernel/process.c (ffffffff81038fd9)
Location: arch/x86/include/asm/percpu.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049618)
Location: arch/x86/include/asm/percpu.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105279f)
Location: arch/x86/include/asm/percpu.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052e08)
Location: arch/x86/include/asm/percpu.h:520
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In drivers/acpi/processor_throttling.c (ffffffff814ad8fc)
Location: arch/x86/include/asm/percpu.h:520
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff8103801b)
Location: arch/x86/include/asm/percpu.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049874)
Location: arch/x86/include/asm/percpu.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff810528ef)
Location: arch/x86/include/asm/percpu.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81052f94)
Location: arch/x86/include/asm/percpu.h:521
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In drivers/acpi/processor_throttling.c (ffffffff814fd2df)
Location: arch/x86/include/asm/percpu.h:521
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff818d3b84)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046bef)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bc74)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff810551ff)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055c84)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In drivers/acpi/processor_throttling.c (ffffffff81520070)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff8190acdd)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810466e2)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b3f6)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054aff)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055794)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In drivers/acpi/processor_throttling.c (ffffffff81531547)
Location: arch/x86/include/asm/percpu.h:510
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff8199504d)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a102)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104edf8)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff810588cb)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81059448)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106b20b)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff81592a17)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff819f15b4)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c7b2)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_setup
```
```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81051b82)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mcheck/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff8105b546)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8105c258)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff8106de81)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff815c9aff)
Location: arch/x86/include/asm/percpu.h:511
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81a2c9e6)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049ea2)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104f227)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff810611d0)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81061ed8)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff81073e11)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff815e30df)
Location: arch/x86/include/asm/percpu.h:512
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81a9cb44)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cff2)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff810522eb)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064890)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065584)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff810779b1)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff81614c81)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81ad4394)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d992)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052bdb)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064f10)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065bf4)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff81078a21)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff81636171)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81bcc480)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbe2ec)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81057be6)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106b63e)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106c524)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff8108b8bc)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e3041)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81c4516f)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36c2c)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81056966)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106d2de)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106dcd4)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff8108b90c)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ea04)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In drivers/acpi/processor_throttling.c (ffffffff81700ca1)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81c383ef)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c290dc)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106dd4e)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8106e734)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff8108c521)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f5c4)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e25d1)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81947219)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/process.c (ffffffff81d56c7f)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47892)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/smpboot.c (ffffffff8107955e)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8107a084)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff8109bd61)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f074)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175ae4d)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff819ebecb)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/process.c (ffffffff81f28eef)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff810883e2)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81088fec)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff810af281)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188ea3b)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81b51eaa)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/process.c (ffffffff820d4bdf)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bea2)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109ccdc)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff810c9691)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d616b)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81cea03a)
Location: arch/x86/include/asm/percpu.h:358
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/events/intel/core.c (ffffffff810131e4)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/kernel/process.c (ffffffff82142fca)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109bd6d)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff8109fbfc)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/mm/tlb.c (ffffffff810ccd11)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1daab)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81d52b7a)
Location: arch/x86/include/asm/percpu.h:378
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/events/intel/core.c (ffffffff8101a46e)
Location: arch/x86/include/asm/percpu.h:476
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
```
In arch/x86/kernel/process.c (ffffffff822256ba)
Location: arch/x86/include/asm/percpu.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a336d)
Location: arch/x86/include/asm/percpu.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:mwait_play_dead
  - arch/x86/kernel/smpboot.c:mwait_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810a714c)
Location: arch/x86/include/asm/percpu.h:476
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a68dbb)
Location: arch/x86/include/asm/percpu.h:476
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
```
In drivers/thermal/intel/therm_throt.c (ffffffff81e098da)
Location: arch/x86/include/asm/percpu.h:476
Inline: True
Inline callers:
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
  - drivers/thermal/intel/therm_throt.c:intel_thermal_interrupt
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
In arch/x86/kernel/process.c (ffffffff81a73204)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104daf2)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052cdb)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064a00)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff810656e4)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff81077a21)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff81605731)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81a2f5c4)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cf8b)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8104269b)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81054cda)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81055a64)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067701)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff815f0911)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81adf614)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d942)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff81052b8b)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81064eb0)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81065b94)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff810779d1)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff8162a451)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
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
In arch/x86/kernel/process.c (ffffffff81aebda4)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ed82)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_setup
```
```
In arch/x86/kernel/cpu/mce/therm_throt.c (ffffffff8105400b)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
  - arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt
```
```
In arch/x86/kernel/smpboot.c (ffffffff81066490)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
```
```
In arch/x86/kernel/apic/apic.c (ffffffff81067174)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__lapic_update_tsc_freq
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
  - arch/x86/kernel/apic/apic.c:setup_APIC_timer
```
```
In arch/x86/kernel/paravirt.c (ffffffff81079a71)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_flush_tlb_one_user
```
```
In drivers/acpi/processor_throttling.c (ffffffff816442f1)
Location: arch/x86/include/asm/percpu.h:524
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
```
</details>
</li>
</ul>

## Differences
