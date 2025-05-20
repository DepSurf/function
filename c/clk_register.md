# Function: <code>clk_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e8460)
Location: drivers/clk/clk.c:2524
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk-divider.c:_register_divider
  - drivers/clk/clk-fixed-factor.c:clk_register_fixed_factor
  - drivers/clk/clk-fixed-rate.c:clk_register_fixed_rate_with_accuracy
  - drivers/clk/clk-gate.c:clk_register_gate
  - drivers/clk/clk-mux.c:clk_register_mux_table
  - drivers/clk/clk-composite.c:clk_register_composite
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
**Symbols:**

```
ffffffff816e8460-ffffffff816e8c00: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174c990)
Location: drivers/clk/clk.c:2532
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff8174c990-ffffffff8174d09e: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815351f0)
Location: drivers/clk/clk.c:2535
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff815351f0-ffffffff8153590b: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815485f0)
Location: drivers/clk/clk.c:2569
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff815485f0-ffffffff81548cce: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815aba70)
Location: drivers/clk/clk.c:2700
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff815aba70-ffffffff815ac22b: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:2958
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff815e449d-ffffffff815e459e: clk_register.cold.59 (STB_LOCAL)
ffffffff815e3a50-ffffffff815e4177: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:3259
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_hw_register
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff815fe88d-ffffffff815fe98e: clk_register.cold.63 (STB_LOCAL)
ffffffff815fde30-ffffffff815fe56c: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162fd60)
Location: drivers/clk/clk.c:3677
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff8162fca0-ffffffff8162fcb5: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81652310)
Location: drivers/clk/clk.c:3756
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff81652250-ffffffff81652265: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81701290)
Location: drivers/clk/clk.c:3846
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff817011d0-ffffffff817011e5: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171e7b0)
Location: drivers/clk/clk.c:3915
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff8171e6f0-ffffffff8171e705: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ff7f0)
Location: drivers/clk/clk.c:3924
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff816ff740-ffffffff816ff755: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81779f87)
Location: drivers/clk/clk.c:3951
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
Direct callers:
  - drivers/clk/versatile/clk-icst.c:icst_clk_setup
```
**Symbols:**

```
ffffffff81779f20-ffffffff81779f35: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b03c6)
Location: drivers/clk/clk.c:4024
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff818b0360-ffffffff818b037f: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fc896)
Location: drivers/clk/clk.c:4213
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff819fc820-ffffffff819fc83f: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a45306)
Location: drivers/clk/clk.c:4265
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff81a45290-ffffffff81a452af: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a90df6)
Location: drivers/clk/clk.c:4311
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff81a90d80-ffffffff81a90d9f: clk_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c2d58)
Location: drivers/clk/clk.c:3756
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/clk-xgene.c:xgene_pllclk_init
  - drivers/clk/hisilicon/clkgate-separated.c:hisi_register_clkgate_sep
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_register_clkdiv
  - drivers/clk/imx/clk-pllv1.c:imx_clk_pllv1
  - drivers/clk/imx/clk-pllv2.c:imx_clk_pllv2
  - drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx
  - drivers/clk/mediatek/clk-pll.c:mtk_clk_register_plls
  - drivers/clk/mediatek/clk-gate.c:mtk_clk_register_gate
  - drivers/clk/mediatek/clk-apmixed.c:mtk_clk_register_ref2usb_tx
  - drivers/clk/mediatek/clk-cpumux.c:mtk_clk_register_cpumuxes
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_register_mux
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
  - drivers/clk/rockchip/clk-inverter.c:rockchip_clk_register_inverter
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_clk_register_mmc
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_clk_register_muxgrf
  - drivers/clk/rockchip/clk-ddr.c:rockchip_clk_register_ddrclk
  - drivers/clk/socfpga/clk-pll-s10.c:s10_register_pll
  - drivers/clk/socfpga/clk-periph-s10.c:s10_register_cnt_periph
  - drivers/clk/socfpga/clk-periph-s10.c:s10_register_periph
  - drivers/clk/socfpga/clk-gate-s10.c:s10_register_gate
  - drivers/clk/sunxi/clk-mod0.c:sunxi_mmc_setup
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_clk_init
```
**Symbols:**

```
ffff8000107c2d58-ffff8000107c2dc4: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ed9f4)
Location: drivers/clk/clk.c:3756
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_register
  - drivers/clk/hisilicon/clkgate-separated.c:hisi_register_clkgate_sep
  - drivers/clk/hisilicon/clkdivider-hi6220.c:hi6220_register_clkdiv
  - drivers/clk/hisilicon/clk-hi3620.c:hi3620_mmc_clk_init
  - drivers/clk/hisilicon/clk-hix5hd2.c:hix5hd2_clk_init
  - drivers/clk/imx/clk-pllv1.c:imx_clk_pllv1
  - drivers/clk/imx/clk-pllv2.c:imx_clk_pllv2
  - drivers/clk/imx/clk-pll14xx.c:imx_clk_pll14xx
  - drivers/clk/mediatek/clk-pll.c:mtk_clk_register_plls
  - drivers/clk/mediatek/clk-gate.c:mtk_clk_register_gate
  - drivers/clk/mediatek/clk-apmixed.c:mtk_clk_register_ref2usb_tx
  - drivers/clk/mediatek/clk-cpumux.c:mtk_clk_register_cpumuxes
  - drivers/clk/mediatek/clk-mux.c:mtk_clk_register_mux
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init
  - drivers/clk/mvebu/dove-divider.c:dove_divider_clk_init
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_register_clock
  - drivers/clk/renesas/rcar-gen2-cpg.c:rcar_gen2_cpg_clk_register
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_register_mod_clk
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
  - drivers/clk/rockchip/clk.c:rockchip_clk_register_branches
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-pll.c:rockchip_clk_register_pll
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
  - drivers/clk/rockchip/clk-inverter.c:rockchip_clk_register_inverter
  - drivers/clk/rockchip/clk-mmc-phase.c:rockchip_clk_register_mmc
  - drivers/clk/rockchip/clk-muxgrf.c:rockchip_clk_register_muxgrf
  - drivers/clk/rockchip/clk-ddr.c:rockchip_clk_register_ddrclk
  - drivers/clk/tegra/clk-audio-sync.c:tegra_clk_register_sync_source
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-divider.c:tegra_clk_register_divider
  - drivers/clk/tegra/clk-periph.c:_tegra_clk_register_periph
  - drivers/clk/tegra/clk-periph.c:_tegra_clk_register_periph
  - drivers/clk/tegra/clk-periph-fixed.c:tegra_clk_register_periph_fixed
  - drivers/clk/tegra/clk-periph-gate.c:tegra_clk_register_periph_gate
  - drivers/clk/tegra/clk-pll.c:_tegra_clk_register_pll
  - drivers/clk/tegra/clk-pll-out.c:tegra_clk_register_pll_out
  - drivers/clk/tegra/clk-sdmmc-mux.c:tegra_clk_register_sdmmc_mux_div
  - drivers/clk/tegra/clk-super.c:tegra_clk_register_super_clk
  - drivers/clk/tegra/clk-super.c:tegra_clk_register_super_mux
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
  - drivers/clk/ti/clk.c:ti_clk_register
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/clk/versatile/clk-icst.c:icst_clk_setup
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
```
**Symbols:**

```
c08ed9f4-c08eda48: clk_register (STB_GLOBAL)
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
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe000510770)
Location: drivers/clk/clk.c:3756
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffe000510770-ffffffe0005107b8: clk_register (STB_GLOBAL)
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
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81618370)
Location: drivers/clk/clk.c:3756
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff816182b0-ffffffff816182c5: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160c8a0)
Location: drivers/clk/clk.c:3756
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff8160c7e0-ffffffff8160c7f5: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81646150)
Location: drivers/clk/clk.c:3756
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff81646090-ffffffff816460a5: clk_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register(struct device *dev, struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816606e0)
Location: drivers/clk/clk.c:3756
Inline: True
Inline callers:
  - drivers/clk/clk.c:devm_clk_register
```
**Symbols:**

```
ffffffff81660620-ffffffff81660635: clk_register (STB_GLOBAL)
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
