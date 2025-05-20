# Function: <code>of_machine_is_compatible</code>

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
int of_machine_is_compatible(const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6af70)
Location: drivers/of/base.c:593
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_device_type
  - drivers/edac/altera_edac.c:altr_init_a10_ecc_block
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
**Symbols:**

```
ffff800010b6af70-ffff800010b6afdc: of_machine_is_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_machine_is_compatible(const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e414)
Location: drivers/of/base.c:593
Inline: False
Direct callers:
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_dt_machine_init
  - arch/arm/mach-exynos/exynos.c:exynos_set_delayed_reset_assertion
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_set_cpu_boot_addr
  - arch/arm/mach-mvebu/system-controller.c:mvebu_system_controller_get_soc_id
  - arch/arm/mach-mvebu/board-v7.c:mvebu_dt_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pmsu.c:mvebu_v7_cpu_pm_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_init
  - arch/arm/mach-mvebu/pm.c:mvebu_pm_init
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
  - arch/arm/mach-mvebu/platsmp-a9.c:mvebu_cortex_a9_boot_secondary
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-milbeaut/platsmp.c:m10v_pm_init
  - arch/arm/mach-omap2/omap_hwmod_7xx_data.c:dra7xx_hwmod_init
  - arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init
  - arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init
  - arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init
  - arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_check
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init_late
  - arch/arm/mach-tegra/tegra.c:tegra_dt_init_late
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:of_assigned_ldb_sels
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_clk_ratio
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_cpu_freq
  - drivers/clk/mvebu/mv98dx3236.c:mv98dx3236_get_cpu_freq
  - drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup
  - drivers/clk/ti/dpll.c:of_ti_omap3_dpll_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/soc/tegra/fuse/tegra-apbmisc.c:tegra_init_apbmisc
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init
  - drivers/cpufreq/tegra124-cpufreq.c:tegra_cpufreq_init
  - drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_probe
  - drivers/cpuidle/cpuidle-exynos.c:exynos_cpuidle_probe
  - drivers/clocksource/timer-tegra.c:tegra20_init_timer
  - drivers/clocksource/timer-tegra.c:tegra20_init_timer
  - drivers/clocksource/timer-ti-32k.c:ti_32k_timer_init
  - drivers/clocksource/timer-imx-gpt.c:imx31_timer_init_dt
```
**Symbols:**

```
c0c4e414-c0c4e464: of_machine_is_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_machine_is_compatible(const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c44a70)
Location: drivers/of/base.c:593
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_64.c:__se_sys_pciconfig_iobase
  - arch/powerpc/platforms/powernv/setup.c:pnv_probe
  - arch/powerpc/platforms/pseries/setup.c:pSeries_probe
  - arch/powerpc/platforms/pseries/setup.c:pSeries_probe
  - drivers/of/address.c:__of_translate_address
  - drivers/of/address.c:__of_translate_address
```
**Symbols:**

```
c000000000c44a70-c000000000c44b10: of_machine_is_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_machine_is_compatible(const char *compat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720586)
Location: drivers/of/base.c:593
Inline: False
```
**Symbols:**

```
ffffffe000720586-ffffffe0007205ea: of_machine_is_compatible (STB_GLOBAL)
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
