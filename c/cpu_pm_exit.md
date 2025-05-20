# Function: <code>cpu_pm_exit</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int cpu_pm_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (ffff80001025b630)
Location: kernel/cpu_pm.c:110
Inline: True
Inline callers:
  - kernel/cpu_pm.c:cpu_pm_resume
Direct callers:
  - arch/arm64/kernel/cpuidle.c:acpi_processor_ffh_lpi_enter
  - drivers/cpuidle/cpuidle-psci.c:psci_enter_idle_state
```
**Symbols:**

```
ffff80001025b518-ffff80001025b540: cpu_pm_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpu_pm_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu_pm.c (c048e790)
Location: kernel/cpu_pm.c:110
Inline: True
Inline callers:
  - kernel/cpu_pm.c:cpu_pm_resume
Direct callers:
  - arch/arm/common/mcpm_entry.c:mcpm_loopback
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/mach-exynos/pm.c:exynos_cpu1_powerdown
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
  - arch/arm/mach-highbank/pm.c:highbank_pm_enter
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait
  - arch/arm/mach-omap2/cpuidle34xx.c:omap3_enter_idle_bm
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-omap2/cpuidle44xx.c:omap_enter_idle_coupled
  - arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2
  - arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2
  - arch/arm/mach-tegra/cpuidle-tegra114.c:tegra114_idle_power_down
  - drivers/cpuidle/cpuidle-mvebu-v7.c:mvebu_v7_enter_idle
  - drivers/cpuidle/cpuidle-big_little.c:bl_enter_powerdown
  - drivers/cpuidle/cpuidle-psci.c:psci_enter_idle_state
```
**Symbols:**

```
c048e670-c048e698: cpu_pm_exit (STB_GLOBAL)
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
