# Function: <code>is_smp</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c030d5fc)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:c_show
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:smp_setup_processor_id
```
```
In arch/arm/kernel/module.c (c0310c70)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/kernel/module.c:module_finalize
```
```
In arch/arm/kernel/smp.c (c0313100)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:arch_irq_work_raise
```
```
In arch/arm/kernel/smp_tlb.c (c0314460)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:flush_bp_all
  - arch/arm/kernel/smp_tlb.c:flush_tlb_kernel_range
  - arch/arm/kernel/smp_tlb.c:flush_tlb_range
  - arch/arm/kernel/smp_tlb.c:flush_tlb_kernel_page
  - arch/arm/kernel/smp_tlb.c:flush_tlb_page
  - arch/arm/kernel/smp_tlb.c:flush_tlb_mm
  - arch/arm/kernel/smp_tlb.c:flush_tlb_all
```
```
In arch/arm/kernel/devtree.c (c1506190)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps
```
```
In arch/arm/mm/mmu.c (c1508130)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:build_mem_type_table
```
```
In arch/arm/mach-mvebu/coherency.c (c150da98)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/coherency.c:coherency_pci_init
  - arch/arm/mach-mvebu/coherency.c:coherency_late_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
  - arch/arm/mach-mvebu/coherency.c:coherency_init
```
```
In kernel/irq_work.c (c048e500)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
```
```
In drivers/cpuidle/cpuidle-big_little.c (c15a45dc)
Location: arch/arm/include/asm/smp_plat.h:18
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_driver_init
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
