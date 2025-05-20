# Function: <code>clk_disable_unprepare</code>

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
In drivers/tty/serial/max310x.c (ffffffff8150cbb9)
Location: include/linux/clk.h:482
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/misc/sram.c (ffffffff815797be)
Location: include/linux/clk.h:482
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
```
```
In drivers/mfd/twl6040.c (ffffffff8158a29c)
Location: include/linux/clk.h:482
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/phy/phy-generic.c (ffffffff8162180c)
Location: include/linux/clk.h:482
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff8162633f)
Location: include/linux/clk.h:482
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d1dc)
Location: include/linux/clk.h:482
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816440ac)
Location: include/linux/clk.h:482
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
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
In drivers/tty/serial/max310x.c (ffffffff8155eef2)
Location: include/linux/clk.h:498
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/misc/sram.c (ffffffff815ce87e)
Location: include/linux/clk.h:498
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
```
```
In drivers/mfd/twl6040.c (ffffffff815df18c)
Location: include/linux/clk.h:498
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8168475f)
Location: include/linux/clk.h:498
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169ddfc)
Location: include/linux/clk.h:498
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4b7c)
Location: include/linux/clk.h:498
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
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
In drivers/tty/serial/max310x.c (ffffffff8158b63d)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/misc/sram.c (ffffffff815fb4de)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
```
```
In drivers/mfd/arizona-core.c (ffffffff815fde95)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff8160be2c)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b0d32)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cbf3c)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2c7c)
Location: include/linux/clk.h:522
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
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
In drivers/tty/serial/max310x.c (ffffffff8159f7c2)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/misc/sram.c (ffffffff8160f29e)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
```
```
In drivers/mfd/arizona-core.c (ffffffff81611cc0)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff8161ff33)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5e95)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e0669)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7259)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727095)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81604ec8)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8160821f)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81677b1e)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
```
```
In drivers/mfd/arizona-core.c (ffffffff8167a530)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff81688773)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81732188)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174ce69)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753a99)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817986e5)
Location: include/linux/clk.h:654
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk
```
**Symbols:**

```
ffffffff81607a30-ffffffff81607a48: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163e154)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81641c2f)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816b358e)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816b5f8b)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff816c47fd)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771a88)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d77b)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817941bb)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9e65)
Location: include/linux/clk.h:716
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
```
**Symbols:**

```
ffffffff81641110-ffffffff81641128: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560fcf)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8165c394)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165fd8f)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816d47ee)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816d71eb)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff816e5bed)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81796b58)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b3eeb)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba78b)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801075)
Location: include/linux/clk.h:837
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
```
**Symbols:**

```
ffffffff81560840-ffffffff81560858: clk_disable_unprepare (STB_LOCAL)
ffffffff8165f370-ffffffff8165f388: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff8159117b)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8169391c)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8169527d)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81710032)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff817129df)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff8171f1d6)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d5bc8)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f350b)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa0bb)
Location: include/linux/clk.h:915
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818423bb)
Location: include/linux/clk.h:915
Inline: True
```
**Symbols:**

```
ffffffff81590c30-ffffffff81590c4a: clk_disable_unprepare (STB_LOCAL)
ffffffff81694990-ffffffff816949aa: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816b64bc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7e1d)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81734322)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81736cdf)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff817434a6)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81806a78)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8182432b)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182aefb)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873d3b)
Location: include/linux/clk.h:918
Inline: True
```
**Symbols:**

```
ffffffff816b7530-ffffffff816b754a: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81768469)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bec0)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817f18d2)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff817f430f)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff818011c1)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d7298)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f5f8b)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fcd9b)
Location: include/linux/clk.h:921
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819482bb)
Location: include/linux/clk.h:921
Inline: True
```
**Symbols:**

```
ffffffff8176a200-ffffffff8176a21c: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-xilinx.c (ffffffff81bf6c62)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_remove
```
```
In drivers/tty/serial/max310x.c (ffffffff817831c9)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786aa0)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81805f22)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff818086bf)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff81812111)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e12ed)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818feb3b)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819056cb)
Location: include/linux/clk.h:939
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e0bb)
Location: include/linux/clk.h:939
Inline: True
```
**Symbols:**

```
ffffffff81784e50-ffffffff81784e6c: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81bf60d1)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81766a69)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a400)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff817cd42c)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/misc/sram.c (ffffffff817eab92)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed21f)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff817f657e)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4550)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e228b)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e8ebb)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931c0b)
Location: include/linux/clk.h:961
Inline: True
```
**Symbols:**

```
ffffffff81768770-ffffffff8176878c: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81cf4248)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff817eb439)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817eeba0)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81857c2c)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/misc/sram.c (ffffffff81877407)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187f883)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195bfe0)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/dwc2/drd.c (ffffffff8195d00f)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e08b)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819852bb)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4f1b)
Location: include/linux/clk.h:961
Inline: True
```
**Symbols:**

```
ffffffff817edee0-ffffffff817edefc: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma/lgm/lgm-dma.c (ffffffff81ebc3f9)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8192ae60)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192ec6b)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff8199e1ee)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/misc/sram.c (ffffffff819bf697)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c7e60)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab5d49)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ab6f72)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad976b)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae0f2b)
Location: include/linux/clk.h:961
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b3789c)
Location: include/linux/clk.h:961
Inline: True
```
**Symbols:**

```
ffffffff8192dee0-ffffffff8192df01: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff819f2ab0)
Location: include/linux/clk.h:1083
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a775)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89c5b)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8ce7d)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0fa4e)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/misc/sram.c (ffffffff81b34e63)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b3ed8c)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3e669)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81c3fa22)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c6485b)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c7fb)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81cccd9c)
Location: include/linux/clk.h:1083
Inline: True
```
**Symbols:**

```
ffffffff819f2ab0-ffffffff819f2ad1: clk_disable_unprepare (STB_LOCAL)
ffffffff81a8c160-ffffffff81a8c181: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a3b140)
Location: include/linux/clk.h:1083
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a535fc)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad5441)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5db1e)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/mfd/twl6040.c (ffffffff81b9230d)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca5a9b)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ca700c)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccbc6b)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3deb)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d34afc)
Location: include/linux/clk.h:1083
Inline: True
```
**Symbols:**

```
ffffffff81a3b140-ffffffff81a3b161: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a86a00)
Location: include/linux/clk.h:1083
Inline: False
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f3ac)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28797)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb13fe)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_suspend
```
```
In drivers/mfd/twl6040.c (ffffffff81be62ad)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5a6eb)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81d5bc5c)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d80b4b)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88dab)
Location: include/linux/clk.h:1083
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deabac)
Location: include/linux/clk.h:1083
Inline: True
```
**Symbols:**

```
ffffffff81a86a00-ffffffff81a86a21: clk_disable_unprepare (STB_LOCAL)
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
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067da5c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/imx-weim.c (ffff800010685554)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_probe
```
```
In drivers/bus/qcom-ebi2.c (ffff800010685640)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/phy/phy-xgene.c (ffff80001068a0f8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a2070)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b68c8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cdf98)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce690)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d254c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721de4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-rockchip.c (ffff800010728dc4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072aca0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010730e10)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010735158)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff800010735b98)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff800010735f54)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff8000107368a0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010760fb0)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/amba/bus.c (ffff8000107b91fc)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/clk/imx/clk.c (ffff8000114858fc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_clk_disable_uart
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb780)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107eebf0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f37b0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3b7c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-de2.c (ffff8000107f9e28)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
```
```
In drivers/dma/mv_xor.c (ffff800010808280)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808454)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_remove
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148f07c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080cf54)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080dfc0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_off
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
```
```
In drivers/soc/imx/gpcv2.c (ffff80001081826c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff8000108195a0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (ffff800010819ddc)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010890c00)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_suspend
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_suspend
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892038)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend
```
```
In drivers/tty/serial/8250/8250_of.c (ffff800010892e74)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108960ec)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
```
```
In drivers/tty/serial/max310x.c (ffff8000108994bc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (ffff800010899fdc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_thaw
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e690)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0360)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a2184)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_shutdown
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108da710)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_suspend
  - drivers/iommu/qcom_iommu.c:qcom_iommu_suspend
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
```
```
In drivers/misc/sram.c (ffff80001092afd0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffff80001093166c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffff80001093f750)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/ata/ahci_imx.c (ffff8000109b6e08)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:ahci_imx_host_stop
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_enable
```
```
In drivers/ata/libahci_platform.c (ffff8000109bcdb4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_disable_clks
  - drivers/ata/libahci_platform.c:ahci_platform_enable_clks
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d8b28)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_suspend
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_remove
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6104)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a38c9c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e244)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-orion.c (ffff800010a5ead0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/rtc/rtc-mv.c (ffff8000114ba9a8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_remove
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aacd00)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_remove
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aae364)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_suspend
  - drivers/rtc/rtc-xgene.c:xgene_rtc_remove
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab8a34)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abc878)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_suspend
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1950)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_clk_disable_unprepare
```
```
In drivers/mmc/host/mmci.c (ffff800010b46484)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4eb70)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_clk_disable
  - drivers/firmware/qcom_scm.c:qcom_scm_clk_disable
  - drivers/firmware/qcom_scm.c:qcom_scm_clk_disable
```
```
In drivers/clocksource/timer-of.c (ffff8000114a7fcc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/timer-rockchip.c (ffff8000114a82a8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_cleanup
  - drivers/clocksource/timer-rockchip.c:rk_timer_cleanup
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
```
```
In drivers/memory/mtk-smi.c (ffff800010b8babc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
```
**Symbols:**

```
ffff80001089e2d8-ffff80001089e300: clk_disable_unprepare (STB_LOCAL)
ffff80001089fbd8-ffff80001089fc00: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/mach-mvebu/mvebu-soc-id.c (c150d450)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
```
```
In arch/arm/mach-omap2/display.c (c033676c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - arch/arm/mach-omap2/display.c:omap_dss_reset
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c0822f00)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_suspend
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_remove
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/imx-weim.c (c082494c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_probe
```
```
In drivers/bus/qcom-ebi2.c (c08265a8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082be98)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cb78)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083ce84)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_remove
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c08464ac)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c08683c0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (c086bdf0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_suspend
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-vf610.c (c08737bc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_disable_clk
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9f8c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08acefc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_power_off
```
```
In drivers/pci/controller/pcie-rcar.c (c08af21c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-rockchip.c (c08b3c84)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_disable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b6178)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_suspend_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_put_resources
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bac10)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_suspend_noirq
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bdc40)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_deinit_2_1_0
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08be1b8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08be530)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_remove
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf0b0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_remove
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (c08e3770)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/amba/bus.c (c08e5188)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_put_disable_pclk
```
```
In drivers/clk/imx/clk.c (c1557e94)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_clk_disable_uart
```
```
In drivers/clk/imx/clk-imx5.c (c155cfac)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904d44)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/rockchip/clk-cpu.c (c090837c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
```
```
In drivers/clk/tegra/clk-emc.c (c0912e5c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
```
```
In drivers/clk/ti/clk-3xxx.c (c158da4c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
```
```
In drivers/dma/mv_xor.c (c092610c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mxs-dma.c (c158ea9c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_free_chan_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (c0929688)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_remove
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/dma/tegra20-apb-dma.c (c0929e3c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_suspend
```
```
In drivers/soc/imx/gpc.c (c0934360)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
```
```
In drivers/soc/imx/gpcv2.c (c0934f08)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935e70)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (c0936adc)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra30.c (c093a538)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a8e8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
```
```
In drivers/soc/tegra/pmc.c (c093b018)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks
  - drivers/soc/tegra/pmc.c:tegra_powergate_disable_clocks
```
```
In drivers/regulator/fixed.c (c09554a0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/regulator/fixed.c:reg_clock_disable
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098d408)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_suspend
```
```
In drivers/tty/serial/8250/8250_of.c (c098e200)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/tty/serial/amba-pl011.c (c0992214)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_shutdown
```
```
In drivers/tty/serial/max310x.c (c09930c4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (c0994e5c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_thaw
  - drivers/tty/serial/imx.c:imx_uart_resume
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_shutdown
  - drivers/tty/serial/imx.c:imx_uart_shutdown
```
```
In drivers/tty/serial/meson_uart.c (c09992f8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (c099a118)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (c099ba64)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_shutdown
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
```
```
In drivers/iommu/exynos-iommu.c (c09c90b4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_disable_clocks
```
```
In drivers/iommu/qcom_iommu.c (c09cb428)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_suspend
  - drivers/iommu/qcom_iommu.c:qcom_iommu_suspend
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
```
```
In drivers/misc/sram.c (c0a09704)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/t7l66xb.c (c0a12394)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_remove
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_suspend
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_disable
```
```
In drivers/mfd/tc6387xb.c (c0a12b5c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/tc6387xb.c:tc6387xb_remove
  - drivers/mfd/tc6387xb.c:tc6387xb_mmc_disable
  - drivers/mfd/tc6387xb.c:tc6387xb_suspend
```
```
In drivers/mfd/tc6393xb.c (c0a13358)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_remove
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/arizona-core.c (c0a14750)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (c0a28ea0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/omap-usb-host.c (c0a348b0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_suspend
```
```
In drivers/ata/libahci_platform.c (c0a87b38)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_disable_clks
  - drivers/ata/libahci_platform.c:ahci_platform_enable_clks
```
```
In drivers/ata/ahci_imx.c (c0a8995c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:ahci_imx_host_stop
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_disable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac955c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/phy/phy-generic.c (c0b0bb14)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:nop_set_suspend
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c850)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_shutdown
```
```
In drivers/usb/dwc2/platform.c (c0b10e58)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-orion.c (c0b2fe4c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_remove
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/usb/host/ehci-exynos.c (c0b30908)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_resume
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_suspend
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_remove
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In drivers/usb/host/ohci-exynos.c (c0b38940)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_resume
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_suspend
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_remove
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
```
```
In drivers/usb/host/uhci-hcd.c (c0b39af4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_remove
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
```
```
In drivers/rtc/rtc-mv.c (c15c0bd4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_remove
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-omap.c (c0b8c3d8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/rtc/rtc-s3c.c (c0b8f004)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-common.c (c0b98120)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c390)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbdf40)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_remove
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/cpufreq/tegra20-cpufreq.c (c0c00984)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_exit
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate
```
```
In drivers/mmc/host/mmci.c (c0c201c8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_suspend
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a918)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2d0e4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_suspend
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_unregister
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f224)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_suspend
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
```
In drivers/firmware/qcom_scm.c (c0c35474)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_clk_disable
  - drivers/firmware/qcom_scm.c:qcom_scm_clk_disable
  - drivers/firmware/qcom_scm.c:qcom_scm_clk_disable
```
```
In drivers/clocksource/timer-of.c (c15aa5c4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/renesas-ostm.c (c15aa900)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_init
```
```
In drivers/clocksource/timer-rockchip.c (c15aaf2c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_cleanup
  - drivers/clocksource/timer-rockchip.c:rk_timer_cleanup
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
```
```
In drivers/clocksource/arm_global_timer.c (c15ad968)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
```
```
In drivers/devfreq/exynos-bus.c (c0c6b2e4)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_passive_exit
  - drivers/devfreq/exynos-bus.c:exynos_bus_exit
```
```
In drivers/devfreq/event/exynos-nocp.c (c0c6b414)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_remove
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6ba14)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_remove
```
```
In drivers/memory/mtk-smi.c (c0c72a58)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
  - drivers/memory/mtk-smi.c:mtk_smi_clk_disable
```
```
In sound/soc/soc-dapm.c (c0ca7b2c)
Location: include/linux/clk.h:918
Inline: True
```
```
In sound/soc/codecs/sgtl5000.c (c0cbdf8c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_remove
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0c14)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_free
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_shutdown
```
```
In sound/soc/fsl/imx-audmux.c (c0cc1bac)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - sound/soc/fsl/imx-audmux.c:imx_audmux_resume
  - sound/soc/fsl/imx-audmux.c:imx_audmux_suspend
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
```
**Symbols:**

```
c0998bbc-c0998bdc: clk_disable_unprepare (STB_LOCAL)
c09998d4-c09998f4: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (c000000000849790)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093ad48)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/max310x.c (c00000000093bf38)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dd74)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (c0000000009ca080)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (c0000000009d1e58)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (c0000000009e7eb0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (c000000000afe038)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/i2c/busses/i2c-designware-common.c (0)
Location: include/linux/clk.h:918
Inline: True
```
**Symbols:**

```
c00000000093dba0-c00000000093dbcc: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae386)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_remove
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b2c14)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_remove
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000507db8)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559a32)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/max310x.c (ffffffe00055a86a)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d476)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffe0005a2914)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a7a2e)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffe0005b339c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c26a)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_remove
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a1e0)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bd95c)
Location: include/linux/clk.h:918
Inline: True
```
```
In drivers/clocksource/timer-of.c (ffffffe00003a44a)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_cleanup
  - drivers/clocksource/timer-of.c:timer_of_init
  - drivers/clocksource/timer-of.c:timer_of_init
```
**Symbols:**

```
ffffffe00055d0b2-ffffffe00055d0da: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a666b)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8167bf1c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d87d)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816fa3b2)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816faa3f)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bee58)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dc70b)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e32db)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
**Symbols:**

```
ffffffff815a6120-ffffffff815a613a: clk_disable_unprepare (STB_LOCAL)
ffffffff8167cf90-ffffffff8167cfaa: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff8159580b)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8165b00c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c96d)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816ce1c2)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816ce84f)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
**Symbols:**

```
ffffffff815952c0-ffffffff815952da: clk_disable_unprepare (STB_LOCAL)
ffffffff8165c080-ffffffff8165c09a: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6bfb)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff816aa2fc)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816abc5d)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817277e2)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff8172a19f)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff81736966)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fb8f8)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818191ab)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181fd7b)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818691eb)
Location: include/linux/clk.h:918
Inline: True
```
**Symbols:**

```
ffffffff815a66b0-ffffffff815a66ca: clk_disable_unprepare (STB_LOCAL)
ffffffff816ab370-ffffffff816ab38a: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void clk_disable_unprepare(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816c475c)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c60bd)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81742c22)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_remove
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff817455df)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/mfd/twl6040.c (ffffffff81751da6)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81815a08)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_disable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8183319b)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_off
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839ceb)
Location: include/linux/clk.h:918
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_off
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8188317b)
Location: include/linux/clk.h:918
Inline: True
```
**Symbols:**

```
ffffffff816c57d0-ffffffff816c57ea: clk_disable_unprepare (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct clk *clk</code> ➡️ <code>struct clk *clk</code>
</li>
</ul>
</details>
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
