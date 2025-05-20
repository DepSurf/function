# Function: <code>of_get_child_count</code>

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
In drivers/power/charger-manager.c (0)
Location: include/linux/of.h:919
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
In drivers/power/charger-manager.c (0)
Location: include/linux/of.h:977
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1097
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1123
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1176
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1199
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1259
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1259
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1259
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1267
Inline: True
```
</details>
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
Location: include/linux/of.h:1284
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
Location: include/linux/of.h:1310
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
Location: include/linux/of.h:1315
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
Location: include/linux/of.h:1372
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
Location: include/linux/of.h:1371
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
Location: include/linux/of.h:1444
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
Location: include/linux/of.h:1443
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int of_get_child_count(const struct device_node *np);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3.c (ffff800011472a40)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff8000106796a8)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
```
```
In drivers/phy/broadcom/phy-brcm-sata.c (ffff80001068a3f8)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699740)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a9670)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b3aec)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
```
```
In drivers/video/of_display_timing.c (ffff800010762034)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd4b0)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/power/supply/charger-manager.c (ffff800010ad01c8)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/thermal/of-thermal.c (ffff800010ad9da8)
Location: include/linux/of.h:1259
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (ffff800010b7d7d4)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
```
**Symbols:**

```
ffff800010ad9da8-ffff800010ad9df0: of_get_child_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int of_get_child_count(const struct device_node *np);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3.c (c154bd14)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083a364)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083db90)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c08496f0)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c08511c0)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_create_functions
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_create_functions
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_dt_node_to_map
```
```
In drivers/video/of_display_timing.c (c08e4774)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/clk/tegra/clk-emc.c (c0913360)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc
```
```
In drivers/ata/libahci_platform.c (c0a882d0)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfe48)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/power/supply/charger-manager.c (c0bb09ec)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/thermal/of-thermal.c (c0bb9f98)
Location: include/linux/of.h:1259
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c408)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/memory/tegra/mc.c (c0c7410c)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74a04)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c759b8)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
```
**Symbols:**

```
c0bb9f98-c0bb9fdc: of_get_child_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int of_get_child_count(const struct device_node *np);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal-powercap.c (c00000000135df74)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-powercap.c:opal_powercap_init
```
```
In arch/powerpc/platforms/powernv/opal-psr.c (c00000000135e418)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-psr.c:opal_psr_init
```
```
In arch/powerpc/platforms/powernv/opal-sensor-groups.c (c00000000135e6b8)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-sensor-groups.c:opal_sensor_groups_init
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c78c)
Location: include/linux/of.h:1259
Inline: True
```
```
In drivers/video/of_display_timing.c (c0000000008c5d1c)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/power/supply/charger-manager.c (c000000000bb3ed4)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/thermal/of-thermal.c (c000000000bc14bc)
Location: include/linux/of.h:1259
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
**Symbols:**

```
c000000000bc14bc-c000000000bc1530: of_get_child_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int of_get_child_count(const struct device_node *np);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (ffffffe000508bfa)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/video/of_display_timing.c:of_get_display_timings
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006ccadc)
Location: include/linux/of.h:1259
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/thermal/of-thermal.c (ffffffe0006d438e)
Location: include/linux/of.h:1259
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
  - drivers/thermal/of-thermal.c:thermal_of_build_thermal_zone
```
**Symbols:**

```
ffffffe0006d438e-ffffffe0006d43ca: of_get_child_count (STB_LOCAL)
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1259
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
In drivers/power/supply/charger-manager.c (0)
Location: include/linux/of.h:1259
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
