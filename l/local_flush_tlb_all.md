# Function: <code>local_flush_tlb_all</code>

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
void local_flush_tlb_all();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/setup.c (ffff80001143418c)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:setup_arch
```
```
In arch/arm64/kernel/cpufeature.c (ffff800010099f6c)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: True
Inline callers:
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:cpu_enable_cnp
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
  - arch/arm64/kernel/cpufeature.c:kpti_install_ng_mappings
```
```
In arch/arm64/kernel/smp.c (ffff80001009c294)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
```
In arch/arm64/kernel/suspend.c (ffff8000100a69c0)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: True
Inline callers:
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
  - arch/arm64/kernel/suspend.c:__cpu_suspend_exit
```
```
In arch/arm64/kernel/machine_kexec.c (ffff8000100a9d70)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: True
Inline callers:
  - arch/arm64/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm64/mm/mmu.c (ffff8000100af740)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: False
Direct callers:
  - arch/arm64/mm/mmu.c:paging_init
  - arch/arm64/mm/mmu.c:paging_init
```
```
In arch/arm64/mm/context.c (ffff8000100afb54)
Location: arch/arm64/include/asm/tlbflush.h:131
Inline: True
Inline callers:
  - arch/arm64/mm/context.c:check_and_switch_context
```
**Symbols:**

```
ffff8000100af740-ffff8000100af75c: local_flush_tlb_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/suspend.c (c0311be0)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend
```
```
In arch/arm/kernel/smp.c (c0312a8c)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:__cpu_disable
```
```
In arch/arm/kernel/smp_tlb.c (c0313b88)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_all
```
```
In arch/arm/mm/idmap.c (c031eecc)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:setup_mm_for_reboot
```
```
In arch/arm/mm/mmu.c (c1509758)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
```
```
In arch/arm/mm/context.c (c0322414)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mach-mvebu/pmsu.c (c0330ff4)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
```
```
In arch/arm/mach-imx/pm-imx5.c (c03320a4)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
```
```
In arch/arm/mach-imx/pm-imx6.c (c03344f8)
Location: arch/arm/include/asm/tlbflush.h:333
Inline: True
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smpboot.c (ffffffe0000035f2)
Location: arch/riscv/include/asm/tlbflush.h:13
Inline: True
Inline callers:
  - arch/riscv/kernel/smpboot.c:smp_callin
```
```
In arch/riscv/mm/init.c (ffffffe000003de0)
Location: arch/riscv/include/asm/tlbflush.h:13
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:paging_init
```
```
In arch/riscv/mm/context.c (ffffffe0000ba1ae)
Location: arch/riscv/include/asm/tlbflush.h:13
Inline: True
Inline callers:
  - arch/riscv/mm/context.c:switch_mm
```
```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba496)
Location: arch/riscv/include/asm/tlbflush.h:13
Inline: True
```
</details>
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
