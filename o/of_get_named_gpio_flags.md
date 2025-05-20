# Function: <code>of_get_named_gpio_flags</code>

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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:67
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:73
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/of_gpio.h:73
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
In drivers/clk/clk-gpio.c (0)
Location: include/linux/of_gpio.h:71
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/of_gpio.h:73
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:73
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:73
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:69
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:69
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:71
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:67
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:70
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:70
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:70
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:70
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:70
Inline: True
```
</details>
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
int of_get_named_gpio_flags(struct device_node *np, const char *list_name, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c7d50)
Location: drivers/gpio/gpiolib-of.c:288
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
**Symbols:**

```
ffff8000106c7d50-ffff8000106c7da8: of_get_named_gpio_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_get_named_gpio_flags(struct device_node *np, const char *list_name, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0865548)
Location: drivers/gpio/gpiolib-of.c:288
Inline: False
Direct callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - sound/soc/soc-ac97.c:snd_soc_set_ac97_ops_of_reset
  - sound/soc/soc-ac97.c:snd_soc_set_ac97_ops_of_reset
  - sound/soc/soc-ac97.c:snd_soc_set_ac97_ops_of_reset
```
**Symbols:**

```
c0865548-c0865570: of_get_named_gpio_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_get_named_gpio_flags(struct device_node *np, const char *list_name, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c000000000845070)
Location: drivers/gpio/gpiolib-of.c:288
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c000000000845070-c0000000008450d4: of_get_named_gpio_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_get_named_gpio_flags(struct device_node *np, const char *list_name, int index, enum of_gpio_flags *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab626)
Location: drivers/gpio/gpiolib-of.c:288
Inline: False
Direct callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffe0004ab626-ffffffe0004ab688: of_get_named_gpio_flags (STB_GLOBAL)
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:67
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:67
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
