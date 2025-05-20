# Function: <code>cpu_suspend</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpu_suspend(long unsigned int arg, int (*fn)(long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/suspend.c (ffff8000100a6d60)
Location: arch/arm64/kernel/suspend.c:86
Inline: False
Direct callers:
  - drivers/firmware/psci/psci.c:psci_system_suspend_enter
  - drivers/firmware/psci/psci.c:psci_cpu_suspend_enter
```
**Symbols:**

```
ffff8000100a6d60-ffff8000100a6f00: cpu_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_suspend(long unsigned int arg, int (*fn)(long unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/suspend.c (c0311b30)
Location: arch/arm/kernel/suspend.c:20
Inline: False
Direct callers:
  - arch/arm/kernel/hibernate.c:swsusp_arch_suspend
  - arch/arm/common/mcpm_entry.c:mcpm_loopback
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/mach-exynos/firmware.c:exynos_suspend
  - arch/arm/mach-exynos/pm.c:exynos_cpu1_powerdown
  - arch/arm/mach-exynos/pm.c:exynos_enter_aftr
  - arch/arm/mach-exynos/suspend.c:exynos_suspend_enter
  - arch/arm/mach-highbank/pm.c:highbank_pm_enter
  - arch/arm/mach-mvebu/pmsu.c:armada_370_xp_cpu_suspend
  - arch/arm/mach-imx/cpuidle-imx6sx.c:imx6sx_enter_wait
  - arch/arm/mach-imx/pm-imx6.c:imx6q_pm_enter
  - arch/arm/mach-omap2/omap-mpuss-lowpower.c:omap4_enter_lowpower
  - arch/arm/mach-omap2/pm34xx.c:omap_sram_idle
  - arch/arm/mach-omap2/pm33xx-core.c:am33xx_suspend
  - arch/arm/mach-rockchip/pm.c:rk3288_suspend_enter
  - arch/arm/mach-shmobile/platsmp-apmu.c:shmobile_smp_apmu_enter_suspend
  - arch/arm/mach-tegra/pm.c:tegra_suspend_enter
  - arch/arm/mach-tegra/pm.c:tegra_suspend_enter
  - arch/arm/mach-tegra/pm.c:tegra_suspend_enter
  - arch/arm/mach-tegra/pm.c:tegra_idle_lp2_last
  - arch/arm/mach-tegra/cpuidle-tegra30.c:tegra30_idle_lp2
  - arch/arm/mach-tegra/cpuidle-tegra114.c:tegra114_idle_power_down
  - drivers/soc/qcom/spm.c:qcom_cpu_spc
  - drivers/cpuidle/cpuidle-big_little.c:bl_enter_powerdown
  - drivers/firmware/psci/psci.c:psci_system_suspend_enter
  - drivers/firmware/psci/psci.c:psci_cpu_suspend_enter
```
**Symbols:**

```
c0311b30-c0311c18: cpu_suspend (STB_GLOBAL)
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
