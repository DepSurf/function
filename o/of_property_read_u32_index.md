# Function: <code>of_property_read_u32_index</code>

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
In drivers/i2c/i2c-core.c (0)
Location: include/linux/of.h:533
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
In drivers/i2c/i2c-core.c (0)
Location: include/linux/of.h:653
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:679
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:710
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:719
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:738
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:738
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:738
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:740
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:747
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:747
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:762
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:762
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:762
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/of.h:762
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:604
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:602
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:614
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:613
Inline: True
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
int of_property_read_u32_index(const struct device_node *np, const char *propname, u32 index, u32 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffff800010b6e5a0)
Location: drivers/of/property.c:113
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-odmi.c:mvebu_odmi_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pctrl_dt_node_to_map
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
  - drivers/clk/sunxi/clk-sun8i-bus-gates.c:sun8i_h3_bus_gates_init
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/regulator/of_regulator.c:of_check_coupling_data
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/edac/altera_edac.c:altr_edac_a10_device_add
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
ffff800010b6e5a0-ffff800010b6e64c: of_property_read_u32_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_property_read_u32_index(const struct device_node *np, const char *propname, u32 index, u32 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c0c51270)
Location: drivers/of/property.c:113
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-gic-v3-mbi.c:mbi_init
  - drivers/irqchip/irq-crossbar.c:crossbar_of_init
  - drivers/irqchip/irq-crossbar.c:crossbar_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/irq-mtk-cirq.c:mtk_cirq_of_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/irqchip/qcom-pdc.c:qcom_pdc_init
  - drivers/bus/imx-weim.c:weim_parse_dt
  - drivers/pinctrl/pinctrl-rza1.c:rza1_parse_pinmux_node
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_dt_node_to_map
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/clk/renesas/clk-mstp.c:cpg_mstp_clocks_init
  - drivers/clk/ti/clk.c:ti_clk_get_reg_addr
  - drivers/clk/ti/divider.c:ti_clk_divider_populate
  - drivers/clk/ti/divider.c:ti_clk_divider_populate
  - drivers/clk/ti/fapll.c:ti_fapll_setup
  - drivers/regulator/of_regulator.c:of_check_coupling_data
  - drivers/regulator/of_regulator.c:of_get_regulation_constraints
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/of/irq.c:of_irq_parse_one
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
```
**Symbols:**

```
c0c51270-c0c512fc: of_property_read_u32_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_property_read_u32_index(const struct device_node *np, const char *propname, u32 index, u32 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (c000000000c48e70)
Location: drivers/of/property.c:113
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/regulator/of_regulator.c:of_check_coupling_data
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
c000000000c48e70-c000000000c48f4c: of_property_read_u32_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_property_read_u32_index(const struct device_node *np, const char *propname, u32 index, u32 *out_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/property.c (ffffffe000722d3e)
Location: drivers/of/property.c:113
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/regulator/of_regulator.c:of_check_coupling_data
  - drivers/i2c/i2c-core-base.c:i2c_new_ancillary_device
  - drivers/of/irq.c:of_irq_parse_one
```
**Symbols:**

```
ffffffe000722d3e-ffffffe000722df8: of_property_read_u32_index (STB_GLOBAL)
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:738
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
In drivers/i2c/i2c-core-base.c (0)
Location: include/linux/of.h:738
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
