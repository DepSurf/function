# Function: <code>of_clk_add_provider</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:810
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:822
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:832
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:841
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:902
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:938
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1055
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1057
Inline: True
```
</details>
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
int of_clk_add_provider(struct device_node *np, struct clk * (*clk_src_get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c19e0)
Location: drivers/clk/clk.c:4285
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-qoriq.c:legacy_pll_init
  - drivers/clk/clk-qoriq.c:sysclk_init
  - drivers/clk/clk-qoriq.c:core_mux_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-xgene.c:xgene_devclk_init
  - drivers/clk/clk-xgene.c:xgene_pmdclk_init
  - drivers/clk/clk-xgene.c:xgene_pllclk_init
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_infra_probe
  - drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_top_probe
  - drivers/clk/mediatek/clk-mt6779.c:clk_mt6779_apmixed_probe
  - drivers/clk/mediatek/clk-mt6779-mm.c:clk_mt6779_mm_probe
  - drivers/clk/mediatek/clk-mt6779-img.c:clk_mt6779_img_probe
  - drivers/clk/mediatek/clk-mt6779-ipe.c:clk_mt6779_ipe_probe
  - drivers/clk/mediatek/clk-mt6779-cam.c:clk_mt6779_cam_probe
  - drivers/clk/mediatek/clk-mt6779-vdec.c:clk_mt6779_vdec_probe
  - drivers/clk/mediatek/clk-mt6779-venc.c:clk_mt6779_venc_probe
  - drivers/clk/mediatek/clk-mt6779-mfg.c:clk_mt6779_mfg_probe
  - drivers/clk/mediatek/clk-mt6779-aud.c:clk_mt6779_aud_probe
  - drivers/clk/mediatek/clk-mt6797.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt6797.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt6797.c:mtk_infra_of_clk_init_driver
  - drivers/clk/mediatek/clk-mt6797.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt6797-img.c:clk_mt6797_img_probe
  - drivers/clk/mediatek/clk-mt6797-mm.c:clk_mt6797_mm_probe
  - drivers/clk/mediatek/clk-mt6797-vdec.c:clk_mt6797_vdec_probe
  - drivers/clk/mediatek/clk-mt6797-venc.c:clk_mt6797_venc_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_mcu_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_peri_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_infra_probe
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_top_probe
  - drivers/clk/mediatek/clk-mt2712.c:mt2712_topckgen_of_clk_init_driver
  - drivers/clk/mediatek/clk-mt2712.c:clk_mt2712_apmixed_probe
  - drivers/clk/mediatek/clk-mt2712-bdp.c:clk_mt2712_bdp_probe
  - drivers/clk/mediatek/clk-mt2712-img.c:clk_mt2712_img_probe
  - drivers/clk/mediatek/clk-mt2712-jpgdec.c:clk_mt2712_jpgdec_probe
  - drivers/clk/mediatek/clk-mt2712-mfg.c:clk_mt2712_mfg_probe
  - drivers/clk/mediatek/clk-mt2712-mm.c:clk_mt2712_mm_probe
  - drivers/clk/mediatek/clk-mt2712-vdec.c:clk_mt2712_vdec_probe
  - drivers/clk/mediatek/clk-mt2712-venc.c:clk_mt2712_venc_probe
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_sgmiisys_init
  - drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init
  - drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_vencltsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_vencsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_vdecsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_mmsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_imgsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_mcu_probe
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_peri_probe
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_infra_probe
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_top_probe
  - drivers/clk/mediatek/clk-mt8183.c:mt8183_topckgen_of_clk_init_driver
  - drivers/clk/mediatek/clk-mt8183.c:clk_mt8183_apmixed_probe
  - drivers/clk/mediatek/clk-mt8183-audio.c:clk_mt8183_audio_probe
  - drivers/clk/mediatek/clk-mt8183-cam.c:clk_mt8183_cam_probe
  - drivers/clk/mediatek/clk-mt8183-img.c:clk_mt8183_img_probe
  - drivers/clk/mediatek/clk-mt8183-ipu0.c:clk_mt8183_ipu_core0_probe
  - drivers/clk/mediatek/clk-mt8183-ipu1.c:clk_mt8183_ipu_core1_probe
  - drivers/clk/mediatek/clk-mt8183-ipu_adl.c:clk_mt8183_ipu_adl_probe
  - drivers/clk/mediatek/clk-mt8183-ipu_conn.c:clk_mt8183_ipu_conn_probe
  - drivers/clk/mediatek/clk-mt8183-mfgcfg.c:clk_mt8183_mfg_probe
  - drivers/clk/mediatek/clk-mt8183-mm.c:clk_mt8183_mm_probe
  - drivers/clk/mediatek/clk-mt8183-vdec.c:clk_mt8183_vdec_probe
  - drivers/clk/mediatek/clk-mt8183-venc.c:clk_mt8183_venc_probe
  - drivers/clk/mediatek/clk-mt8516.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_infracfg_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8516-aud.c:mtk_audsys_init
  - drivers/clk/mvebu/ap806-system-controller.c:ap806_syscon_common_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
  - drivers/clk/rockchip/clk.c:rockchip_clk_of_add_provider
  - drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divs_clk_setup
  - drivers/clk/sunxi/clk-sunxi.c:sunxi_divider_clk_setup
  - drivers/clk/sunxi/clk-a10-codec.c:sun4i_codec_clk_setup
  - drivers/clk/sunxi/clk-a10-hosc.c:sun4i_osc_clk_setup
  - drivers/clk/sunxi/clk-a10-mod1.c:sun4i_mod1_clk_setup
  - drivers/clk/sunxi/clk-a10-pll2.c:sun4i_pll2_setup
  - drivers/clk/sunxi/clk-a10-ve.c:sun4i_ve_clk_setup
  - drivers/clk/sunxi/clk-a20-gmac.c:sun7i_a20_gmac_clk_setup
  - drivers/clk/sunxi/clk-mod0.c:sunxi_mmc_setup
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun4i-display.c:sun4i_a10_display_init
  - drivers/clk/sunxi/clk-sun4i-pll3.c:sun4i_a10_pll3_setup
  - drivers/clk/sunxi/clk-sun4i-tcon-ch1.c:tcon_ch1_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/clk/sunxi/clk-sun8i-mbus.c:sun8i_a23_mbus_setup
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
  - drivers/clk/sunxi/clk-sun8i-apb0.c:sun8i_a23_apb0_register
  - drivers/clk/sunxi/clk-sun9i-cpus.c:sun9i_a80_cpus_setup
  - drivers/clk/sunxi/clk-sun6i-apb0.c:sun6i_a31_apb0_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
```
**Symbols:**

```
ffff8000107c19e0-ffff8000107c1b04: of_clk_add_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_clk_add_provider(struct device_node *np, struct clk * (*clk_src_get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec60c)
Location: drivers/clk/clk.c:4285
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-qoriq.c:legacy_pll_init
  - drivers/clk/clk-qoriq.c:sysclk_init
  - drivers/clk/clk-qoriq.c:core_mux_init
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/hisilicon/clk-hi3620.c:hi3620_mmc_clk_init
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_sgmiisys_init
  - drivers/clk/mediatek/clk-mt7622-eth.c:clk_mt7622_ethsys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_pciesys_init
  - drivers/clk/mediatek/clk-mt7622-hif.c:clk_mt7622_ssusbsys_init
  - drivers/clk/mediatek/clk-mt7622-aud.c:clk_mt7622_audiosys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_sgmiisys_init
  - drivers/clk/mediatek/clk-mt7629-eth.c:clk_mt7629_ethsys_init
  - drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_pciesys_init
  - drivers/clk/mediatek/clk-mt7629-hif.c:clk_mt7629_ssusbsys_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_vencltsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_vencsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_vdecsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_mmsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_imgsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8173.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_infracfg_init
  - drivers/clk/mediatek/clk-mt8516.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt8516-aud.c:mtk_audsys_init
  - drivers/clk/mvebu/common.c:mvebu_clk_gating_setup
  - drivers/clk/mvebu/common.c:mvebu_coreclk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_mv98dx3236_cpu_clk_setup
  - drivers/clk/mvebu/clk-cpu.c:of_cpu_clk_setup
  - drivers/clk/mvebu/clk-corediv.c:mvebu_corediv_clk_init
  - drivers/clk/mvebu/dove-divider.c:dove_divider_clk_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_gclk_init
  - drivers/clk/renesas/clk-emev2.c:emev2_smu_clkdiv_init
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init
  - drivers/clk/renesas/clk-r8a7779.c:r8a7779_cpg_clocks_init
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_common_init
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init
  - drivers/clk/renesas/clk-div6.c:cpg_div6_clock_init
  - drivers/clk/rockchip/clk.c:rockchip_clk_of_add_provider
  - drivers/clk/tegra/clk.c:tegra_add_of_provider
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/ti/dpll.c:_register_dpll
  - drivers/clk/ti/composite.c:_register_composite
  - drivers/clk/ti/divider.c:of_ti_divider_clk_setup
  - drivers/clk/ti/gate.c:_of_ti_gate_clk_setup
  - drivers/clk/ti/fixed-factor.c:of_ti_fixed_factor_clk_setup
  - drivers/clk/ti/mux.c:of_mux_clk_setup
  - drivers/clk/ti/apll.c:of_omap2_apll_setup
  - drivers/clk/ti/apll.c:omap_clk_register_apll
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/clk/ti/interface.c:_of_ti_interface_clk_setup
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clock_setup
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/versatile/clk-icst.c:of_syscon_icst_setup
  - drivers/clk/versatile/clk-versatile.c:cm_osc_setup
  - drivers/clk/versatile/clk-sp810.c:clk_sp810_of_setup
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
```
**Symbols:**

```
c08ec60c-c08ec6f8: of_clk_add_provider (STB_GLOBAL)
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
int of_clk_add_provider(struct device_node *np, struct clk * (*clk_src_get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f6a6)
Location: drivers/clk/clk.c:4285
Inline: False
Direct callers:
  - drivers/clk/clk-fixed-rate.c:_of_fixed_clk_setup
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
```
**Symbols:**

```
ffffffe00050f6a6-ffffffe00050f7b4: of_clk_add_provider (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1057
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1057
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1057
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1057
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
