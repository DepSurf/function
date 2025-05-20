# Function: <code>clk_set_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e7e50)
Location: drivers/clk/clk.c:1554
Inline: False
Direct callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
**Symbols:**

```
ffffffff816e7e50-ffffffff816e7e88: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174c3f0)
Location: drivers/clk/clk.c:1620
Inline: False
```
**Symbols:**

```
ffffffff8174c3f0-ffffffff8174c427: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81534c50)
Location: drivers/clk/clk.c:1620
Inline: False
```
**Symbols:**

```
ffffffff81534c50-ffffffff81534c87: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81547e90)
Location: drivers/clk/clk.c:1622
Inline: True
```
**Symbols:**

```
ffffffff81547e90-ffffffff81547ed2: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aa200)
Location: drivers/clk/clk.c:1733
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff815aa200-ffffffff815aa242: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e28c0)
Location: drivers/clk/clk.c:1943
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff815e28c0-ffffffff815e293e: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fcf50)
Location: drivers/clk/clk.c:2056
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff815fcf50-ffffffff815fcfce: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816303c0)
Location: drivers/clk/clk.c:2192
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff816303c0-ffffffff81630442: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81651770)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff81651770-ffffffff816517f2: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81701e60)
Location: drivers/clk/clk.c:2221
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
```
**Symbols:**

```
ffffffff81701e60-ffffffff81701faf: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171f1a0)
Location: drivers/clk/clk.c:2230
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
  - drivers/opp/core.c:_generic_set_opp_regulator
```
**Symbols:**

```
ffffffff8171f1a0-ffffffff8171f2ef: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817001e0)
Location: drivers/clk/clk.c:2243
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff817001e0-ffffffff8170032f: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177ab90)
Location: drivers/clk/clk.c:2243
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff8177ab90-ffffffff8177acdf: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b12c0)
Location: drivers/clk/clk.c:2257
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
  - drivers/opp/core.c:_set_opp
```
**Symbols:**

```
ffffffff818b12c0-ffffffff818b1419: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fdb90)
Location: drivers/clk/clk.c:2441
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_config_clks_simple
  - drivers/opp/core.c:dev_pm_opp_config_clks_simple
  - drivers/opp/core.c:_opp_config_clk_single
```
**Symbols:**

```
ffffffff819fdb90-ffffffff819fdce9: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a46300)
Location: drivers/clk/clk.c:2486
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_config_clks_simple
  - drivers/opp/core.c:dev_pm_opp_config_clks_simple
  - drivers/opp/core.c:_opp_config_clk_single
```
**Symbols:**

```
ffffffff81a46300-ffffffff81a464d4: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a91df0)
Location: drivers/clk/clk.c:2486
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_config_clks_simple
  - drivers/opp/core.c:dev_pm_opp_config_clks_simple
  - drivers/opp/core.c:_opp_config_clk_single
```
**Symbols:**

```
ffffffff81a91df0-ffffffff81a91fc4: clk_set_rate (STB_GLOBAL)
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
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c22e8)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
```
**Symbols:**

```
ffff8000107c22e8-ffff8000107c23a0: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ecf20)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk
  - arch/arm/mach-omap2/io.c:omap_sdrc_init
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_set_par
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/rockchip/clk-rk3188.c:rk3188a_clk_init
  - drivers/clk/tegra/clk.c:tegra_init_from_table
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
  - drivers/clk/ti/clk-44xx.c:omap4xxx_dt_clk_init
  - drivers/clk/ti/clk-44xx.c:omap4xxx_dt_clk_init
  - drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init
  - drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init
  - drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_set_opp
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_set_opp
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/cpufreq/omap-cpufreq.c:omap_target
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:emc_debug_rate_set
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_set_bclk
```
**Symbols:**

```
c08ecf20-c08ecfb8: clk_set_rate (STB_GLOBAL)
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
In drivers/pci/controller/pci-ftpci100.c (0)
Location: include/linux/clk.h:842
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/linux/clk.h:842
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050fe6c)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffe00050fe6c-ffffffe00050ff0a: clk_set_rate (STB_GLOBAL)
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
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816177d0)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff816177d0-ffffffff81617852: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160bd00)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8160bd00-ffffffff8160bd82: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816455b0)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff816455b0-ffffffff81645632: clk_set_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int clk_set_rate(struct clk *clk, long unsigned int rate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165fb40)
Location: drivers/clk/clk.c:2200
Inline: True
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
  - drivers/opp/core.c:dev_pm_opp_set_rate
```
**Symbols:**

```
ffffffff8165fb40-ffffffff8165fbc2: clk_set_rate (STB_GLOBAL)
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
