# Function: <code>__devm_reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, int shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81530410)
Location: drivers/reset/core.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff81530410-ffffffff81530483: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, int shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155c9e0)
Location: drivers/reset/core.c:381
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
**Symbols:**

```
ffffffff8155c9e0-ffffffff8155ca53: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81571430)
Location: drivers/reset/core.c:427
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81571430-ffffffff815714de: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5700)
Location: drivers/reset/core.c:542
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff815d5700-ffffffff815d57ae: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160ebd0)
Location: drivers/reset/core.c:636
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8160ebd0-ffffffff8160ec74: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b3c0)
Location: drivers/reset/core.c:637
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8162b3c0-ffffffff8162b464: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165f330)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8165f330-ffffffff8165f3d6: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681a50)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81681a50-ffffffff81681afa: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732b50)
Location: drivers/reset/core.c:779
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81732b50-ffffffff81732bfb: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174ed10)
Location: drivers/reset/core.c:853
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8174ed10-ffffffff8174edbb: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817329d0)
Location: drivers/reset/core.c:1033
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817329d0-ffffffff81732a7b: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b32d0)
Location: drivers/reset/core.c:1034
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817b32d0-ffffffff817b3382: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818eed60)
Location: drivers/reset/core.c:1035
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff818eed60-ffffffff818eee22: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a469e0)
Location: drivers/reset/core.c:1035
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81a469e0-ffffffff81a46aa2: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a90b80)
Location: drivers/reset/core.c:1035
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81a90b80-ffffffff81a90c42: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae35f0)
Location: drivers/reset/core.c:1035
Inline: False
Direct callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/usb/dwc2/platform.c:dwc2_lowlevel_hw_init
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81ae35f0-ffffffff81ae36b2: __devm_reset_control_get (STB_GLOBAL)
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
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c7f0)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
**Symbols:**

```
ffff80001084c7f0-ffff80001084c8cc: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958b28)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_4_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_get_resources_2_1_0
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
**Symbols:**

```
c0958b28-c0958bdc: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ec6f0)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c0000000008ec6f0-c0000000008ec824: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052bfb0)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe00052bfb0-ffffffe00052c050: __devm_reset_control_get (STB_GLOBAL)
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
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816474d0)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff816474d0-ffffffff8164757a: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627930)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
**Symbols:**

```
ffffffff81627930-ffffffff816279da: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675890)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81675890-ffffffff8167593a: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct reset_control *__devm_reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168fef0)
Location: drivers/reset/core.c:778
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8168fef0-ffffffff8168ff9a: __devm_reset_control_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool optional</code>
</li>
<li>
<b>Param type changed. </b>
<code>int shared</code> ➡️ <code>bool shared</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool acquired</code>
</li>
</ul>
</details>
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
