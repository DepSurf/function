# Function: <code>read_cpuid_part</code>

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
In arch/arm/kernel/setup.c (c15041dc)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_processor
```
```
In arch/arm/kernel/hw_breakpoint.c (c1506668)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init
```
```
In arch/arm/mm/proc-v7-bugs.c (c0322d04)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mm/proc-v7-bugs.c:cpu_v7_spectre_init
```
```
In arch/arm/mm/cache-l2x0.c (c1509ef0)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0.c:l2c310_enable
```
```
In arch/arm/mach-actions/platsmp.c (c150c030)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-actions/platsmp.c:s500_smp_prepare_cpus
```
```
In arch/arm/mach-exynos/firmware.c (c150c750)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-exynos/firmware.c:exynos_firmware_init
  - arch/arm/mach-exynos/firmware.c:exynos_suspend
```
```
In arch/arm/mach-exynos/pm.c (c032d418)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
```
```
In arch/arm/mach-exynos/suspend.c (c032de08)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos_pm_suspend
```
```
In arch/arm/mach-exynos/platsmp.c (c150ca14)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_smp_prepare_cpus
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c032ea88)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_cluster_cache_disable
```
```
In arch/arm/mach-hisi/platsmp.c (c150cfcc)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-hisi/platsmp.c:hisi_enable_scu_a9
```
```
In arch/arm/mach-rockchip/platsmp.c (c151945c)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-rockchip/platsmp.c:rockchip_smp_prepare_cpus
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
```
```
In arch/arm/mach-tegra/platsmp.c (c151abf4)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-tegra/platsmp.c:tegra_smp_prepare_cpus
```
```
In arch/arm/mach-vexpress/tc2_pm.c (c034d64c)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/tc2_pm.c:tc2_pm_cluster_cache_disable
```
```
In drivers/cpuidle/cpuidle-big_little.c (c15a45dc)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle-big_little.c:bl_idle_driver_init
```
```
In drivers/clocksource/arm_global_timer.c (c15ad838)
Location: arch/arm/include/asm/cputype.h:236
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
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
