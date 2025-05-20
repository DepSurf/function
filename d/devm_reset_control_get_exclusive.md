# Function: <code>devm_reset_control_get_exclusive</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560df8)
Location: include/linux/reset.h:279
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81590f77)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/net/phy/mdio_bus.c (ffffffff8179a562)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c (ffff8000106b6d90)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sun6i-a31-r.c:sun6i_a31_r_pinctrl_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c (ffff8000106b6e80)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sun8i-a23-r.c:sun8i_a23_r_pinctrl_probe
```
```
In drivers/pci/controller/pcie-rockchip.c (ffff800010728a30)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff80001073195c)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010733dec)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736ad4)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f347c)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-de2.c (ffff8000107f9db8)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c0844020)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac090)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
```
```
In drivers/pci/controller/pcie-rockchip.c (c08b3910)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_parse_dt
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb700)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bcb34)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
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
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08bea4c)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090cd64)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
```
```
In drivers/dma/tegra20-apb-dma.c (c092a598)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6467)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81595607)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a69f7)
Location: include/linux/reset.h:317
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
