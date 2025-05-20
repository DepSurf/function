# Function: <code>cpu_set_reserved_ttbr0</code>

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
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/setup.c (ffff800011434184)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099f64)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
```
```
In arch/arm64/kernel/smp.c (ffff80001009c28c)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a69b8)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9d68)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/mm/mmu.c (ffff8000114384dc)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
```
```
In arch/arm64/mm/context.c (ffff8000100afbe0)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
  - arch/arm64/mm/context.c:check_and_switch_context
```
```
In kernel/sched/core.c (ffff80001013d0c0)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:__schedule
```
```
In mm/mmu_context.c (ffff8000102e00dc)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In fs/exec.c (ffff80001038eec0)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
```
```
In drivers/firmware/efi/arm-runtime.c (ffff800010b61164)
Location: arch/arm64/include/asm/mmu_context.h:41
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/context.c (c03222a4)
Location: arch/arm/mm/context.c:85
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
