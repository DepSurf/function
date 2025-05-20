# Function: <code>gpio_is_valid</code>

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
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/gpio.h:41
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:41
Inline: True
```
```
In drivers/regulator/core.c (ffffffff814dd885)
Location: include/asm-generic/gpio.h:41
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff8158a188)
Location: include/asm-generic/gpio.h:41
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff815e6946)
Location: include/asm-generic/gpio.h:41
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff815ed2ad)
Location: include/asm-generic/gpio.h:41
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_regs
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
  - drivers/net/phy/fixed_phy.c:fixed_phy_add
```
```
In drivers/usb/phy/phy-generic.c (ffffffff81621472)
Location: include/asm-generic/gpio.h:41
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/asm-generic/gpio.h:41
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/asm-generic/gpio.h:41
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
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff815df2e3)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff81644d16)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c32b)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/asm-generic/gpio.h:45
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
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff8160bf83)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff81675deb)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e03b)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
```
In drivers/i2c/i2c-core.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/asm-generic/gpio.h:45
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
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149eeb2)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff81620093)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff8168a53b)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8169317e)
Location: include/asm-generic/gpio.h:45
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/asm-generic/gpio.h:45
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814dd9f2)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff816888d3)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff816f3d4b)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd08e)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150b56e)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150cbe4)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
```
In drivers/regulator/core.c (ffffffff8160b6e5)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff816c4a5f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff81730794)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8173b26f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815203a9)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81627dca)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/mfd/twl6040.c (ffffffff816e5e4f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff817531bb)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175ea1f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_del
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
In drivers/gpio/gpiolib.c (ffffffff8154e926)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff8171f42b)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff81790f58)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156fd4f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff817436fb)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff817b4b48)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81613f45)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:44
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff81800e4d)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff8187a047)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/gpio/gpiolib.c (ffffffff81638e08)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:44
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff81811d9d)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff818889d7)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/gpio/gpiolib.c (ffffffff8161c9de)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:44
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff817f66e0)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff8186b5d7)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/gpio/gpiolib.c (ffffffff8168beb0)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:44
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff8187f9e0)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff818fa780)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/gpio/gpiolib.c (ffffffff817a9166)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:44
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff819c7fb0)
Location: include/asm-generic/gpio.h:44
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
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
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/gpio.h:153
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:153
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio.h:59
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/gpio.h:59
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio.h:59
Inline: True
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/linux/gpio.h:59
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
In drivers/gpio/gpiolib.c (ffff8000106c5dfc)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff80001073168c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff8000107368ec)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/mfd/stmpe.c (ffff80001092f718)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093f29c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/ata/ahci_imx.c (ffff8000109b848c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/spi/spi.c (ffff8000109c4dfc)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ce94c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_cleanup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9cb4)
Location: include/asm-generic/gpio.h:46
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
In drivers/gpio/gpiolib.c (c0863ec0)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9b30)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb420)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08be57c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/tty/serial/omap-serial.c (c09a00b0)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
```
```
In drivers/mfd/stmpe.c (c0a10d98)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl6040.c (c0a28bc4)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/ata/ahci_imx.c (c0a8ae40)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/spi/spi.c (c0ab1e44)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab738c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_transfer_one
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_cleanup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acaf00)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/phy/phy-generic.c (c0b0b7ec)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
```
In drivers/usb/host/ehci-exynos.c (c0b304bc)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In sound/soc/soc-jack.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
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
In drivers/gpio/gpiolib.c (c000000000842d0c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/stmpe.c (c0000000009cf45c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl6040.c (c0000000009e8334)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (c000000000a89780)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
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
In drivers/gpio/gpiolib.c (ffffffe0004a9c2e)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/stmpe.c (ffffffe0005a60b2)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/twl6040.c (ffffffe0005b2f6c)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffe0006171c2)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156550f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81779628)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155635f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/spi/spi.c (ffffffff817593d8)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156407f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff81736bbb)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff817a99c8)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157df9f)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-legacy.c (0)
Location: include/asm-generic/gpio.h:46
Inline: True
```
```
In drivers/mfd/twl6040.c (ffffffff81751ffb)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi.c (ffffffff817c3858)
Location: include/asm-generic/gpio.h:46
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_validate
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_set_cs
```
</details>
</li>
</ul>

## Differences
