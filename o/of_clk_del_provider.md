# Function: <code>of_clk_del_provider</code>

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
void of_clk_del_provider(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bc868)
Location: drivers/clk/clk.c:4421
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_of_clk_release_provider
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_remove
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_remove
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_remove
  - drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init
  - drivers/clk/mediatek/clk-mt8183-audio.c:clk_mt8183_audio_probe
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_remove
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_remove
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_remove
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/sunxi/clk-factors.c:sunxi_factors_unregister
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi-ng/ccu_common.c:sunxi_ccu_probe
```
**Symbols:**

```
ffff8000107bc868-ffff8000107bc91c: of_clk_del_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void of_clk_del_provider(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e8c90)
Location: drivers/clk/clk.c:4421
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_of_clk_release_provider
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_remove
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_remove
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_remove
  - drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister
  - drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_remove
  - drivers/net/ethernet/ti/cpts.c:cpts_create
```
**Symbols:**

```
c08e8c90-c08e8d20: of_clk_del_provider (STB_GLOBAL)
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
void of_clk_del_provider(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050bd8e)
Location: drivers/clk/clk.c:4421
Inline: False
Direct callers:
  - drivers/clk/clk.c:devm_of_clk_release_provider
  - drivers/clk/clk.c:of_clk_add_hw_provider
  - drivers/clk/clk.c:of_clk_add_provider
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_remove
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_remove
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_remove
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_remove
```
**Symbols:**

```
ffffffe00050bd8e-ffffffe00050be1e: of_clk_del_provider (STB_GLOBAL)
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
