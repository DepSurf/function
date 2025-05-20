# Function: <code>of_clk_add_hw_provider</code>

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
int of_clk_add_hw_provider(struct device_node *np, struct clk_hw * (*get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1b08)
Location: drivers/clk/clk.c:4322
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/bcm/clk-iproc-armpll.c:iproc_armpll_setup
  - drivers/clk/bcm/clk-iproc-pll.c:iproc_pll_clk_setup
  - drivers/clk/bcm/clk-iproc-asiu.c:iproc_asiu_setup
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe
  - drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe
  - drivers/clk/zynqmp/clkc.c:zynqmp_clock_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
```
**Symbols:**

```
ffff8000107c1b08-ffff8000107c1c2c: of_clk_add_hw_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_clk_add_hw_provider(struct device_node *np, struct clk_hw * (*get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec6f8)
Location: drivers/clk/clk.c:4322
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-aspeed.c:aspeed_cc_g5_of_clk_init_driver
  - drivers/clk/clk-ast2600.c:aspeed_cc_g6_of_clk_init_driver
  - drivers/clk/clk-highbank.c:hb_clk_init
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/clk-milbeaut.c:m10v_cc_of_clk_init_driver
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/clk/berlin/bg2.c:berlin2_clock_setup
  - drivers/clk/berlin/bg2q.c:berlin2q_clock_setup
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sll.c:imx6sll_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx7d.c:imx7d_clocks_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_smc1_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc3_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_pcc2_init
  - drivers/clk/imx/clk-imx7ulp.c:imx7ulp_clk_scg1_init
  - drivers/clk/meson/meson8b.c:meson8b_clkc_init_common
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/samsung/clk.c:samsung_clk_of_add_provider
  - drivers/clk/samsung/clk-exynos-clkout.c:exynos_clkout_init
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/ti/clkctrl.c:_ti_omap4_clkctrl_setup
  - drivers/clk/ti/clkctrl.c:_clkctrl_add_provider
  - drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_probe
  - drivers/net/ethernet/ti/cpts.c:cpts_create
```
**Symbols:**

```
c08ec6f8-c08ec7e4: of_clk_add_hw_provider (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_clk_add_hw_provider(struct device_node *np, struct clk_hw * (*get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f7b4)
Location: drivers/clk/clk.c:4322
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_of_clk_add_hw_provider
  - drivers/clk/clk-fixed-factor.c:_of_fixed_factor_clk_setup
  - drivers/clk/clk-fixed-mmio.c:fixed_mmio_clk_setup
  - drivers/clk/clk-hsdk-pll.c:of_hsdk_pll_clk_setup
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
```
**Symbols:**

```
ffffffe00050f7b4-ffffffe00050f8c2: of_clk_add_hw_provider (STB_GLOBAL)
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
