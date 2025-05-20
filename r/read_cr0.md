# Function: <code>read_cr0</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101cd6c)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102d2bf)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
  - arch/x86/kernel/process_64.c:__switch_to
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810398c1)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_ctx_switch
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/fpu/bugs.c (ffffffff81f699ae)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/kernel/fpu/core.c (ffffffff810399b8)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:fpu__drop
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c048)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fb34)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff816fafeb)
Location: arch/x86/include/asm/paravirt.h:59
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten.c (ffffffff8101bf8c)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c9ee)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__switch_to
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81f9169c)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_ctx_switch
```
```
In arch/x86/kernel/fpu/bugs.c (ffffffff81f91899)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/bugs.c:fpu__init_check_bugs
```
```
In arch/x86/kernel/fpu/core.c (ffffffff8103996b)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/core.c:fpu__drop
  - arch/x86/kernel/fpu/core.c:__kernel_fpu_end
  - arch/x86/kernel/fpu/core.c:irq_fpu_usable
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104c1d6)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8104fcae)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff817601ff)
Location: arch/x86/include/asm/paravirt.h:49
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/xen/enlighten.c (ffffffff8101c79c)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
```
```
In arch/x86/kernel/process_64.c (ffffffff8102c28f)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102e116)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81fcca35)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e626)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810524ce)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff8178d1ff)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
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
In arch/x86/kernel/process_64.c (ffffffff8102a47f)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102c244)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff820ad22f)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8104e596)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81051fee)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff817ab36f)
Location: arch/x86/include/asm/paravirt.h:44
Inline: True
Inline callers:
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
In arch/x86/kernel/process_64.c (ffffffff8102b1e7)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102d156)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff826b3ac0)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81051f06)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81055c5e)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff81822862)
Location: arch/x86/include/asm/paravirt.h:45
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
In arch/x86/kernel/process_64.c (ffffffff8102cf54)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102e135)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff826dd2a5)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81054bb6)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81058ade)
Location: arch/x86/include/asm/paravirt.h:45
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff8186caa2)
Location: arch/x86/include/asm/paravirt.h:45
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
In arch/x86/kernel/process_64.c (ffffffff8102e1a2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8102f2a5)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828936ed)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81052276)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105e71e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff8188cab2)
Location: arch/x86/include/asm/paravirt.h:107
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
In arch/x86/kernel/process_64.c (ffffffff8102ff2b)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031095)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828aad15)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055376)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061b1e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff818d7422)
Location: arch/x86/include/asm/paravirt.h:107
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
In arch/x86/kernel/process_64.c (ffffffff8103088b)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031955)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828add85)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c76)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810623ce)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff81909ab2)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/power/cpu.c:save_processor_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr0();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81032eb6)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81bbd925)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810411e1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105add4)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810683ac)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff81bba1e2)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
**Symbols:**

```
ffffffff81041190-ffffffff8104119d: read_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr0();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81bd30d3)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c36087)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff810410b1)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81059934)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a08c)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff81bcea57)
Location: arch/x86/include/asm/paravirt.h:113
Inline: True
```
**Symbols:**

```
ffffffff81041060-ffffffff8104106d: read_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr0();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81bc54c3)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81c28527)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81042a9c)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8105a2b4)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106ab5c)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In drivers/iommu/intel/pasid.c (ffffffff81796d67)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In arch/x86/power/cpu.c (ffffffff81bc2407)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
```
**Symbols:**

```
ffffffff81042a50-ffffffff81042a5d: read_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr0();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81c980e3)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81d46697)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff81048e0c)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81063704)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810754bc)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181ed1a)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In arch/x86/power/cpu.c (ffffffff81c92a73)
Location: arch/x86/include/asm/paravirt.h:126
Inline: True
```
**Symbols:**

```
ffffffff81048dc0-ffffffff81048dcd: read_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int read_cr0();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process_64.c (ffffffff81e47584)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81f14994)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff83459f51)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810703a4)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81083f1c)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195f049)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In arch/x86/power/cpu.c (ffffffff81e423be)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
```
**Symbols:**

```
ffffffff81052140-ffffffff81052164: read_cr0 (STB_LOCAL)
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
In arch/x86/kernel/process_64.c (ffffffff8104a1d3)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff820bbd54)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff83e79be9)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac58)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096dac)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6c7b)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
```
In arch/x86/power/cpu.c (ffffffff8201cd8e)
Location: arch/x86/include/asm/paravirt.h:132
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
In arch/x86/kernel/process_64.c (ffffffff8104aa13)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8213d484)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8369c309)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c5c8)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099ecc)
Location: arch/x86/include/asm/paravirt.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff8209d41e)
Location: arch/x86/include/asm/paravirt.h:132
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
In arch/x86/kernel/process_64.c (ffffffff81051c83)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff8221f4a4)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff838cbfe9)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_system
```
```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073818)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_enable
  - arch/x86/kernel/cpu/cacheinfo.c:cache_disable
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a16fc)
Location: arch/x86/include/asm/paravirt.h:136
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff82174c1e)
Location: arch/x86/include/asm/paravirt.h:136
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
In arch/x86/kernel/process_64.c (ffffffff810309eb)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031ab5)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff8289bda4)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810557f6)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff81061f4e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff818a8e72)
Location: arch/x86/include/asm/paravirt.h:107
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
In arch/x86/kernel/process_64.c (ffffffff8102047e)
Location: arch/x86/include/asm/special_insns.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff810215a5)
Location: arch/x86/include/asm/special_insns.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff82894048)
Location: arch/x86/include/asm/special_insns.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81045936)
Location: arch/x86/include/asm/special_insns.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8105230d)
Location: arch/x86/include/asm/special_insns.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff81863614)
Location: arch/x86/include/asm/special_insns.h:143
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
In arch/x86/kernel/process_64.c (ffffffff8103084b)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff81031915)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828aed67)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81055c26)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106236e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff818fa4d2)
Location: arch/x86/include/asm/paravirt.h:107
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
In arch/x86/kernel/process_64.c (ffffffff810316db)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/process_64.c:__show_regs
```
```
In arch/x86/kernel/traps.c (ffffffff810327d5)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_device_not_available
```
```
In arch/x86/kernel/fpu/init.c (ffffffff828aed95)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810570c6)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
```
```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106392e)
Location: arch/x86/include/asm/paravirt.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel
```
```
In arch/x86/power/cpu.c (ffffffff8191b632)
Location: arch/x86/include/asm/paravirt.h:107
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
