# Function: <code>of_platform_populate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:80
Inline: True
```
```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:80
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:80
Inline: True
```
```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:80
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:80
Inline: True
```
```
In drivers/mfd/palmas.c (0)
Location: include/linux/of_platform.h:80
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:85
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:92
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:101
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:107
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:107
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
int of_platform_populate(struct device_node *root, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffff800010b6ddf0)
Location: drivers/of/platform.c:468
Inline: False
Direct callers:
  - drivers/bus/arm-cci.c:cci_platform_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
  - drivers/bus/sun50i-de2.c:sun50i_de2_bus_probe
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/net/ethernet/freescale/fman/fman.c:read_dts_node
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_edac_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
```
**Symbols:**

```
ffff800010b6ddf0-ffff800010b6df28: of_platform_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_platform_populate(struct device_node *root, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c0c50c84)
Location: drivers/of/platform.c:468
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pdata-quirks.c:pdata_quirks_init
  - drivers/bus/arm-cci.c:cci_platform_probe
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/vexpress-config.c:vexpress_config_init
  - drivers/pwm/pwm-tipwmss.c:pwmss_probe
  - drivers/clk/ti/clk-814x.c:dm814x_adpll_early_init
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
**Symbols:**

```
c0c50c84-c0c50dc4: of_platform_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_platform_populate(struct device_node *root, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (c000000000c485f0)
Location: drivers/of/platform.c:468
Inline: False
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/of/platform.c:of_platform_default_populate
```
**Symbols:**

```
c000000000c485f0-c000000000c48774: of_platform_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_platform_populate(struct device_node *root, const struct of_device_id *matches, const struct of_dev_auxdata *lookup, struct device *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/platform.c (ffffffe0007227cc)
Location: drivers/of/platform.c:468
Inline: False
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/of/platform.c:devm_of_platform_populate
  - drivers/of/platform.c:of_platform_default_populate_init
  - drivers/of/platform.c:of_platform_default_populate_init
```
**Symbols:**

```
ffffffe0007227cc-ffffffe0007228e0: of_platform_populate (STB_GLOBAL)
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
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
In drivers/mfd/twl-core.c (0)
Location: include/linux/of_platform.h:87
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
