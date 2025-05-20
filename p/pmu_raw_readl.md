# Function: <code>pmu_raw_readl</code>

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
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
u32 pmu_raw_readl(u32 offset);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-exynos/exynos.c (c032cc00)
Location: arch/arm/mach-exynos/common.h:160
Inline: True
Inline callers:
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
```
```
In arch/arm/mach-exynos/pm.c (c032d3f8)
Location: arch/arm/mach-exynos/common.h:160
Inline: True
Inline callers:
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
```
```
In arch/arm/mach-exynos/suspend.c (c032da88)
Location: arch/arm/mach-exynos/common.h:160
Inline: True
Inline callers:
  - arch/arm/mach-exynos/suspend.c:exynos_suspend_enter
  - arch/arm/mach-exynos/suspend.c:exynos_suspend_enter
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_resume
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos5420_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos3250_pm_prepare
  - arch/arm/mach-exynos/suspend.c:exynos_pm_init
```
```
In arch/arm/mach-exynos/platsmp.c (c032e6fc)
Location: arch/arm/mach-exynos/common.h:160
Inline: True
Inline callers:
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_boot_secondary
  - arch/arm/mach-exynos/platsmp.c:exynos_cluster_power_state
  - arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down
  - arch/arm/mach-exynos/platsmp.c:exynos_cpu_power_down
```
```
In arch/arm/mach-exynos/mcpm-exynos.c (c150cb44)
Location: arch/arm/mach-exynos/common.h:160
Inline: True
Inline callers:
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_mcpm_init
  - arch/arm/mach-exynos/mcpm-exynos.c:exynos_cpu_powerup
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939e0c)
Location: drivers/soc/samsung/exynos-pmu.c:33
Inline: False
Direct callers:
  - drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init
  - drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init
  - drivers/soc/samsung/exynos3250-pmu.c:exynos3250_pmu_init
  - drivers/soc/samsung/exynos5250-pmu.c:exynos5_powerdown_conf
  - drivers/soc/samsung/exynos5250-pmu.c:exynos5_powerdown_conf
  - drivers/soc/samsung/exynos5250-pmu.c:exynos5_powerdown_conf
  - drivers/soc/samsung/exynos5250-pmu.c:exynos5250_pmu_init
  - drivers/soc/samsung/exynos5250-pmu.c:exynos5250_pmu_init
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init
  - drivers/soc/samsung/exynos5420-pmu.c:exynos5420_pmu_init
```
**Symbols:**

```
c0939e0c-c0939e38: pmu_raw_readl (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
