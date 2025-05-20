# Function: <code>clk_get_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e5b10)
Location: drivers/clk/clk.c:1056
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff816e5b10-ffffffff816e5b2b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174a9c0)
Location: drivers/clk/clk.c:1105
Inline: False
Direct callers:
  - lib/vsprintf.c:clock
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff8174a9c0-ffffffff8174a9db: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81533240)
Location: drivers/clk/clk.c:1105
Inline: False
Direct callers:
  - lib/vsprintf.c:clock
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff81533240-ffffffff8153325b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81546900)
Location: drivers/clk/clk.c:1107
Inline: True
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - lib/vsprintf.c:clock
```
**Symbols:**

```
ffffffff81546900-ffffffff8154691b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aa040)
Location: drivers/clk/clk.c:1184
Inline: True
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - lib/vsprintf.c:clock
```
**Symbols:**

```
ffffffff815aa040-ffffffff815aa05b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e1430)
Location: drivers/clk/clk.c:1393
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff815e1430-ffffffff815e144b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fb560)
Location: drivers/clk/clk.c:1499
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff815fb560-ffffffff815fb57b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162d9d0)
Location: drivers/clk/clk.c:1617
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff8162d9d0-ffffffff8162d9eb: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164f650)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff8164f650-ffffffff8164f66b: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fe6d0)
Location: drivers/clk/clk.c:1622
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff816fe6d0-ffffffff816fe729: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171b8d0)
Location: drivers/clk/clk.c:1631
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:clocks_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff8171b8d0-ffffffff8171b929: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fc9b0)
Location: drivers/clk/clk.c:1652
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff816fc9b0-ffffffff816fca09: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81778400)
Location: drivers/clk/clk.c:1652
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff81778400-ffffffff81778459: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818ae7c0)
Location: drivers/clk/clk.c:1666
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff818ae7c0-ffffffff818ae834: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f9c20)
Location: drivers/clk/clk.c:1846
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff819f9c20-ffffffff819f9c9a: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a422d0)
Location: drivers/clk/clk.c:1891
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff81a422d0-ffffffff81a4234a: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8dce0)
Location: drivers/clk/clk.c:1891
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/opp/core.c:_set_opp
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff81a8dce0-ffffffff81a8dd5a: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107be580)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_get_debounce_div
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/video/fbdev/mx3fb.c:sdc_init_panel
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/imx/clk-cpu.c:clk_cpu_recalc_rate
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_clk_src_twocell_get
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
  - drivers/clk/sunxi/clk-mod0.c:mmc_set_phase
  - drivers/clk/sunxi/clk-mod0.c:mmc_get_phase
  - drivers/clk/sunxi/clk-mod0.c:mmc_get_phase
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_set_timeout
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
```
**Symbols:**

```
ffff8000107be580-ffff8000107be5b4: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08eb018)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk
  - arch/arm/mach-omap2/io.c:omap_sdrc_init
  - arch/arm/mach-omap2/timer.c:realtime_counter_init
  - arch/arm/mach-omap2/timer.c:omap_dm_timer_init_one
  - arch/arm/mach-omap2/voltage.c:omap_voltage_late_init
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_host_init
  - drivers/video/fbdev/mx3fb.c:__set_par
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/imx/clk-cpu.c:clk_cpu_recalc_rate
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/renesas/r7s9210-cpg-mssr.c:rza2_cpg_clk_register
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_mod_clk
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_core_clk
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_clk_src_twocell_get
  - drivers/clk/rockchip/clk-cpu.c:rockchip_cpuclk_notifier_cb
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/clk/samsung/clk.c:_get_rate
  - drivers/clk/samsung/clk-exynos5410.c:exynos5410_clk_init
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllss
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllc
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllm
  - drivers/clk/tegra/clk-pll.c:tegra_clk_register_pllxc
  - drivers/clk/tegra/clk-emc.c:emc_set_rate
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init
  - drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init
  - drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init
  - drivers/clk/ti/clk-3xxx.c:omap3xxx_dt_clk_init
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/tegra/pmc.c:tegra_pmc_enter_suspend_mode
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/tty/serial/amba-pl011.c:pl011_console_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_init
  - drivers/power/avs/smartreflex.c:sr_set_clk_length
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/mvebu-cpufreq.c:armada_xp_pmsu_cpufreq_init
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_get_intermediate
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_request
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_clock
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_clk_get_max_clock
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_xp_timer_init
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/exynos_mct.c:mct_init_dt
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
  - drivers/clocksource/timer-sp804.c:sp804_get_clock_rate
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-gpt.c:imx6dl_gpt_setup_tctl
  - drivers/clocksource/timer-imx-gpt.c:imx31_gpt_setup_tctl
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_timings
  - drivers/memory/omap-gpmc.c:gpmc_round_ps_to_sync_clk
  - drivers/memory/omap-gpmc.c:gpmc_round_ps_to_sync_clk
  - drivers/memory/omap-gpmc.c:gpmc_cs_set_timings
  - drivers/memory/omap-gpmc.c:gpmc_calc_divider
  - drivers/memory/omap-gpmc.c:set_gpmc_timing_reg
  - drivers/memory/omap-gpmc.c:gpmc_round_ps_to_ticks
  - drivers/memory/omap-gpmc.c:gpmc_round_ps_to_ticks
  - drivers/memory/omap-gpmc.c:gpmc_ticks_to_ns
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/tegra124-emc.c:emc_debug_rate_get
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
```
**Symbols:**

```
c08eb018-c08eb040: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/pci/controller/pci-ftpci100.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/mfd/twl-core.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/clk.h:837
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/linux/clk.h:837
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050d9be)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_config
  - drivers/pwm/pwm-sifive.c:pwm_sifive_apply
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe00050d9be-ffffffe00050d9ec: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816156b0)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff816156b0-ffffffff816156cb: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81609be0)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff81609be0-ffffffff81609bfb: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81643490)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff81643490-ffffffff816434ab: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clk_get_rate(struct clk *clk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165d8d0)
Location: drivers/clk/clk.c:1625
Inline: True
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_get_clk_rate_khz
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/cpufreq/cpufreq.c:cpufreq_generic_get
```
**Symbols:**

```
ffffffff8165d8d0-ffffffff8165d8eb: clk_get_rate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
