# Function: <code>devm_platform_ioremap_resource</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816dd8f0)
Location: drivers/base/platform.c:91
Inline: False
Direct callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
ffffffff816dd8f0-ffffffff816dd955: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817019a0)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
ffffffff817019a0-ffffffff81701a0a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc5d0)
Location: drivers/base/platform.c:95
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_soc_data
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817bc5d0-ffffffff817bc63a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1300)
Location: drivers/base/platform.c:120
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_soc_data
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817d1300-ffffffff817d136a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b4d30)
Location: drivers/base/platform.c:120
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817b4d30-ffffffff817b4d9a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e1f0)
Location: drivers/base/platform.c:120
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8183e1f0-ffffffff8183e25a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81981000)
Location: drivers/base/platform.c:122
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81981000-ffffffff81981074: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aeebc0)
Location: drivers/base/platform.c:122
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81aeebc0-ffffffff81aeec34: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3cfb0)
Location: drivers/base/platform.c:122
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b3cfb0-ffffffff81b3d024: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94af0)
Location: drivers/base/platform.c:122
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b94af0-ffffffff81b94b64: devm_platform_ioremap_resource (STB_GLOBAL)
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
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108ecf90)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/clk/imx/clk-imx8mm.c:imx8mm_clocks_probe
  - drivers/clk/imx/clk-imx8mn.c:imx8mn_clocks_probe
  - drivers/clk/imx/clk-imx8mq.c:imx8mq_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
**Symbols:**

```
ffff8000108ecf90-ffff8000108ed018: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09daf40)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/imx/gpcv2.c:imx_gpcv2_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_init
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
```
**Symbols:**

```
c09daf40-c09dafbc: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000984ec0)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
c000000000984ec0-c000000000984f58: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580264)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
**Symbols:**

```
ffffffe000580264-ffffffe0005802da: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c70f0)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
ffffffff816c70f0-ffffffff816c715a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a23f0)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
ffffffff816a23f0-ffffffff816a245a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f5660)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff816f5660-ffffffff816f56ca: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devm_platform_ioremap_resource(struct platform_device *pdev, unsigned int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8170fef0)
Location: drivers/base/platform.c:73
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
**Symbols:**

```
ffffffff8170fef0-ffffffff8170ff5a: devm_platform_ioremap_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
