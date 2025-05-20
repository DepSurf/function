# Function: <code>devm_clk_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff816e3b90)
Location: drivers/clk/clk-devres.c:17
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff816e3b90-ffffffff816e3c0a: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81747ed0)
Location: drivers/clk/clk-devres.c:17
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81747ed0-ffffffff81747f4b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81530740)
Location: drivers/clk/clk-devres.c:17
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81530740-ffffffff815307bb: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81543830)
Location: drivers/clk/clk-devres.c:17
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81543830-ffffffff815438b8: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff815a6940)
Location: drivers/clk/clk-devres.c:17
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815a6940-ffffffff815a69c8: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff815de4a0)
Location: drivers/clk/clk-devres.c:17
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815de4a0-ffffffff815de525: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff815f7cc0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815f7cc0-ffffffff815f7d45: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81629cb0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81629cb0-ffffffff81629d2b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff8164b7a0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8164b7a0-ffffffff8164b81b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff816fa8a0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816fa8a0-ffffffff816fa91b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81717250)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81717250-ffffffff817172cb: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff816f8520)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816f8520-ffffffff816f859b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81772cc0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81772cc0-ffffffff81772d42: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff818a84b0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff818a84b0-ffffffff818a853e: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff819f2a20)
Location: drivers/clk/clk-devres.c:63
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff819f2a20-ffffffff819f2a4b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a3b0b0)
Location: drivers/clk/clk-devres.c:63
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81a3b0b0-ffffffff81a3b0db: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a86970)
Location: drivers/clk/clk-devres.c:63
Inline: False
Direct callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
```
**Symbols:**

```
ffffffff81a86970-ffffffff81a8699b: devm_clk_get (STB_GLOBAL)
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
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffff8000107b9fc0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/bus/imx-weim.c:weim_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
**Symbols:**

```
ffff8000107b9fc0-ffff8000107ba050: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (c08e6284)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/bus/imx-weim.c:weim_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/soc/imx/gpc.c:imx_gpc_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_probe
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/tty/serial/amba-pl011.c:pl011_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_control_unlocked
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
```
**Symbols:**

```
c08e6284-c08e6304: devm_clk_get (STB_GLOBAL)
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
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/pci/controller/pci-ftpci100.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/mfd/arizona-core.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/clk.h:768
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (0)
Location: include/linux/clk.h:768
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffe0005091d6)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe0005091d6-ffffffe000509254: devm_clk_get (STB_GLOBAL)
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
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81611800)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffff81611800-ffffffff8161187b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81605d50)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffff81605d50-ffffffff81605dcb: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff8163f5e0)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8163f5e0-ffffffff8163f65b: devm_clk_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk *devm_clk_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81659930)
Location: drivers/clk/clk-devres.c:12
Inline: False
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81659930-ffffffff816599ab: devm_clk_get (STB_GLOBAL)
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
