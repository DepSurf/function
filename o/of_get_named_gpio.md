# Function: <code>of_get_named_gpio</code>

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
Location: include/linux/of_gpio.h:136
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:145
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:140
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
In drivers/mfd/twl6040.c (0)
Location: include/linux/of_gpio.h:142
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
Location: include/linux/of_gpio.h:142
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
Location: include/linux/of_gpio.h:138
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
Location: include/linux/of_gpio.h:138
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
Location: include/linux/of_gpio.h:140
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
Location: include/linux/of_gpio.h:129
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
Location: include/linux/of_gpio.h:132
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
Location: include/linux/of_gpio.h:132
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
Location: include/linux/of_gpio.h:132
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
Location: include/linux/of_gpio.h:133
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
Location: include/linux/of_gpio.h:133
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731648)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff8000107365a0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093f468)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/ata/ahci_imx.c (ffff8000109b8470)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/spi/spi.c (ffff8000109c7cb0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9c8c)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
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
In arch/arm/mach-mvebu/pm-board.c (c150e2fc)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/pm-board.c:mvebu_armada_pm_init
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb3dc)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/tty/serial/omap-serial.c (c09a00a0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/mfd/twl6040.c (c0a28ba0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/ata/ahci_imx.c (c0a8ae1c)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/spi/spi.c (c0ab0a3c)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acaed8)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/host/ehci-exynos.c (c0b304a0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In sound/soc/soc-ac97.c (c0cbbee0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - sound/soc/soc-ac97.c:snd_soc_set_ac97_ops_of_reset
  - sound/soc/soc-ac97.c:snd_soc_set_ac97_ops_of_reset
  - sound/soc/soc-ac97.c:snd_soc_set_ac97_ops_of_reset
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
In drivers/mfd/twl6040.c (c0000000009e8540)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/spi/spi.c (c000000000a887e0)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
In drivers/mfd/twl6040.c (ffffffe0005b30ea)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/spi/spi.c (ffffffe0006183cc)
Location: include/linux/of_gpio.h:129
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
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
Location: include/linux/of_gpio.h:129
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
Location: include/linux/of_gpio.h:129
Inline: True
```
</details>
</li>
</ul>

## Differences
