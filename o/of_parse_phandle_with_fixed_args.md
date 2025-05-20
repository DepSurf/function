# Function: <code>of_parse_phandle_with_fixed_args</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:870
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:877
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:892
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
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:892
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: include/linux/of.h:892
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:1002
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: include/linux/of.h:1002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:1001
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: include/linux/of.h:1001
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:1034
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: include/linux/of.h:1034
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/syscon.c (0)
Location: include/linux/of.h:1033
Inline: True
```
```
In drivers/net/mdio/fwnode_mdio.c (0)
Location: include/linux/of.h:1033
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
int of_parse_phandle_with_fixed_args(const struct device_node *np, const char *list_name, int cell_count, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6b960)
Location: drivers/of/base.c:1750
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_of_parse
  - drivers/of/property.c:of_fwnode_get_reference_args
```
**Symbols:**

```
ffff800010b6b960-ffff800010b6b9cc: of_parse_phandle_with_fixed_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_parse_phandle_with_fixed_args(const struct device_node *np, const char *list_name, int cell_count, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4ed58)
Location: drivers/of/base.c:1750
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_unaligned_memaccess
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/of/property.c:of_fwnode_get_reference_args
```
**Symbols:**

```
c0c4ed58-c0c4eda0: of_parse_phandle_with_fixed_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_parse_phandle_with_fixed_args(const struct device_node *np, const char *list_name, int cell_count, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c456c0)
Location: drivers/of/base.c:1750
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_reference_args
```
**Symbols:**

```
c000000000c456c0-c000000000c456f8: of_parse_phandle_with_fixed_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_parse_phandle_with_fixed_args(const struct device_node *np, const char *list_name, int cell_count, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720e1e)
Location: drivers/of/base.c:1750
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/of/property.c:of_fwnode_get_reference_args
  - drivers/of/property.c:of_fwnode_get_reference_args
```
**Symbols:**

```
ffffffe000720e1e-ffffffe000720e72: of_parse_phandle_with_fixed_args (STB_GLOBAL)
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
