# Function: <code>of_property_count_strings</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: include/linux/of.h:804
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (0)
Location: include/linux/of.h:856
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
In drivers/base/property.c (0)
Location: include/linux/of.h:976
Inline: True
```
</details>
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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1159
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1183
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1188
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1121
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1120
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1178
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1177
Inline: True
```
</details>
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
In drivers/bus/brcmstb_gisb.c (ffff8000114769ac)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/pinctrl/pinconf-generic.c (ffff800010691968)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
```
```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7ae8)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aa798)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b0754)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b2bdc)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_dt_node_to_map
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b4974)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
```
```
In drivers/pci/controller/pcie-cadence.c (ffff80001071d4d0)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/clk/clk-qoriq.c (ffff800011484648)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:legacy_pll_init
```
```
In drivers/dma/of-dma.c (ffff8000107ff84c)
Location: include/linux/of.h:1134
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892b58)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/of/property.c (ffff800010b6eae0)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_string_array
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
In arch/arm/mach-omap2/omap_hwmod.c (c033710c)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_hwmod.c:of_dev_hwmod_lookup
```
```
In arch/arm/mach-omap2/omap_device.c (c033ad08)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
```
```
In drivers/bus/brcmstb_gisb.c (c154eafc)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/pinctrl/pinconf-generic.c (c08334a8)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c0842c98)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_dt_node_to_map
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c0843e40)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_dt_node_to_map
```
```
In drivers/pinctrl/berlin/berlin.c (c0847b54)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_dt_node_to_map
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a5e4)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_dt_node_to_map
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c0850bb4)
Location: include/linux/of.h:1134
Inline: True
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (c0854938)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map
```
```
In drivers/pci/controller/pcie-cadence.c (c08a653c)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c155214c)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/clk/clk-qoriq.c (c15565e4)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:legacy_pll_init
```
```
In drivers/clk/renesas/clk-rz.c (c157e730)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-r8a7740.c (c157ec5c)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7740.c:r8a7740_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-r8a7778.c (c157f2dc)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7778.c:r8a7778_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-r8a7779.c (c157f5cc)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-r8a7779.c:r8a7779_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-sh73a0.c (c1580230)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-sh73a0.c:sh73a0_cpg_clocks_init
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (c1580bf8)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
```
```
In drivers/dma/of-dma.c (c0920074)
Location: include/linux/of.h:1134
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098df4c)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/of/property.c (c0c51940)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_string_array
```
```
In sound/soc/soc-core.c (c0ca1524)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_of_parse_audio_routing
  - sound/soc/soc-core.c:snd_soc_of_parse_audio_simple_widgets
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
In arch/powerpc/platforms/powernv/opal-sysparam.c (c00000000135d274)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sysparam.c:opal_sys_param_init
```
```
In drivers/pinctrl/pinconf-generic.c (c00000000082dba0)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
```
```
In drivers/pci/controller/pcie-cadence.c (c00000000088e2b4)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/dma/of-dma.c (c0000000008c9918)
Location: include/linux/of.h:1134
Inline: True
```
```
In drivers/of/property.c (c000000000c49840)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_string_array
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049d042)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dt_subnode_to_map
```
```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e427a)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
```
```
In drivers/dma/of-dma.c (ffffffe000517a36)
Location: include/linux/of.h:1134
Inline: True
```
```
In drivers/of/property.c (ffffffe0007231bc)
Location: include/linux/of.h:1134
Inline: True
Inline callers:
  - drivers/of/property.c:of_fwnode_property_read_string_array
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
