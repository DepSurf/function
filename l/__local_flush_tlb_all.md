# Function: <code>__local_flush_tlb_all</code>

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
In arch/arm/kernel/suspend.c (c0311be4)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/arm/kernel/suspend.c:cpu_suspend
```
```
In arch/arm/kernel/smp.c (c0312a90)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:secondary_start_kernel
  - arch/arm/kernel/smp.c:__cpu_disable
```
```
In arch/arm/kernel/smp_tlb.c (c0314028)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:flush_tlb_all
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_all
```
```
In arch/arm/mm/idmap.c (c031eed0)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:setup_mm_for_reboot
```
```
In arch/arm/mm/mmu.c (c1509760)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
```
```
In arch/arm/mm/context.c (c0322418)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
Inline callers:
  - arch/arm/mm/context.c:check_and_switch_context
```
```
In arch/arm/mach-mvebu/pmsu.c (c0331004)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
```
```
In arch/arm/mach-imx/pm-imx5.c (c03320b4)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
```
```
In arch/arm/mach-imx/pm-imx6.c (c0334508)
Location: arch/arm/include/asm/tlbflush.h:323
Inline: True
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
