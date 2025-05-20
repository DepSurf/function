# Function: <code>cpu_switch_mm</code>

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
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void cpu_switch_mm(pgd_t *pgd, struct mm_struct *mm);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/setup.c (ffff80001143420c)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099fac)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
```
```
In arch/arm64/kernel/smp.c (0)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a6ac4)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9db8)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/mm/mmu.c (ffff8000100af7cc)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
Direct callers:
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
```
```
In arch/arm64/mm/context.c (ffff8000100afc88)
Location: arch/arm64/include/asm/mmu_context.h:49
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
**Symbols:**

```
ffff8000100af7cc-ffff8000100af844: cpu_switch_mm (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
