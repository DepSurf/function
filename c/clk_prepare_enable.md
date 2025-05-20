# Function: <code>clk_prepare_enable</code>

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
In drivers/tty/serial/max310x.c (ffffffff8150dfd7)
Location: include/linux/clk.h:467
Inline: True
```
```
In drivers/misc/sram.c (ffffffff81579ccc)
Location: include/linux/clk.h:467
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8158a2b5)
Location: include/linux/clk.h:467
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/phy/phy-generic.c (ffffffff81621762)
Location: include/linux/clk.h:467
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
```
```
In drivers/usb/dwc2/platform.c (ffffffff81626244)
Location: include/linux/clk.h:467
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d22f)
Location: include/linux/clk.h:467
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816440ff)
Location: include/linux/clk.h:467
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff8156042f)
Location: include/linux/clk.h:483
Inline: True
```
```
In drivers/misc/sram.c (ffffffff815ced61)
Location: include/linux/clk.h:483
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff815df001)
Location: include/linux/clk.h:483
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81684649)
Location: include/linux/clk.h:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169de4f)
Location: include/linux/clk.h:483
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4bcf)
Location: include/linux/clk.h:483
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff8158cb9e)
Location: include/linux/clk.h:507
Inline: True
```
```
In drivers/misc/sram.c (ffffffff815fb9bc)
Location: include/linux/clk.h:507
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff815fef57)
Location: include/linux/clk.h:507
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff8160bca1)
Location: include/linux/clk.h:507
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b0c0c)
Location: include/linux/clk.h:507
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cbf8f)
Location: include/linux/clk.h:507
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2ccf)
Location: include/linux/clk.h:507
Inline: True
Inline callers:
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
In drivers/tty/serial/max310x.c (ffffffff815a0c60)
Location: include/linux/clk.h:639
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a23bd)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff8160f550)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81612db5)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff8161fda9)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5d5e)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e06c1)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e72b1)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727090)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk
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
In drivers/tty/serial/max310x.c (ffffffff81606390)
Location: include/linux/clk.h:639
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816081b9)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81677dd0)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff8167b625)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff816885e9)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8173204e)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174cec1)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753af1)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817986e0)
Location: include/linux/clk.h:639
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:i2c_dw_plat_prepare_clk
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
In drivers/tty/serial/max310x.c (ffffffff8163efc6)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81641b8b)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816b38d3)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816b73c6)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff816c487a)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8177194c)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178d7cd)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8179420d)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9e7b)
Location: include/linux/clk.h:701
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560ca9)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8165d1c6)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165fccb)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816d4b93)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816d85d5)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff816e5c6a)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81796a5c)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b3f3d)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba7dd)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8180108b)
Location: include/linux/clk.h:822
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81591145)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff816930eb)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694fe1)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817104cd)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81713805)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff8171f327)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d5acc)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f355c)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa10e)
Location: include/linux/clk.h:900
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8184238c)
Location: include/linux/clk.h:900
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff816b5c8b)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7b81)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817347bd)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81737b05)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff817435f7)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8180697c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8182437c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182af4e)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873d0c)
Location: include/linux/clk.h:903
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff817692ab)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bc01)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817f1d70)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4a95)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff81801300)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d718c)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f5fdc)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fcdee)
Location: include/linux/clk.h:906
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194828c)
Location: include/linux/clk.h:906
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
In drivers/gpio/gpio-xilinx.c (ffffffff816413aa)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff817840cd)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817867e1)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff818063a0)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81808515)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff81812250)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e1701)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818feb8c)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8190571e)
Location: include/linux/clk.h:924
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e08c)
Location: include/linux/clk.h:924
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81709642)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff817679c1)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a141)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff817ccf5f)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
```
```
In drivers/misc/sram.c (ffffffff817eafe0)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed0e5)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff817f65ca)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4951)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e22dc)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e8f0e)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931bdc)
Location: include/linux/clk.h:946
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
In drivers/dma/lgm/lgm-dma.c (ffffffff81784ff2)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec3e4)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817ee7b1)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff8185753f)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
```
```
In drivers/misc/sram.c (ffffffff8187794e)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187f8cf)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c2b1)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff8195cee7)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e118)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8198534c)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4eec)
Location: include/linux/clk.h:946
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
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbc05)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8192af72)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192e815)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff8199dfb1)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
```
```
In drivers/misc/sram.c (ffffffff819bfc2d)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c7ea6)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab6161)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ab6eb3)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad980d)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae0fcd)
Location: include/linux/clk.h:946
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b3785c)
Location: include/linux/clk.h:946
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int clk_prepare_enable(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff819f3177)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a73f)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89706)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8cade)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0f7c5)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
```
```
In drivers/misc/sram.c (ffffffff81b354bd)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b3ee06)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3ead1)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81c3f963)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c6490d)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c8ad)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81cccd5c)
Location: include/linux/clk.h:1068
Inline: True
```
**Symbols:**

```
ffffffff819f2de0-ffffffff819f2e27: clk_prepare_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int clk_prepare_enable(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a3b807)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a535bf)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4ed5)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5d885)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
```
```
In drivers/mfd/twl6040.c (ffffffff81b92164)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca5fb3)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81ca6eeb)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccbd1d)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3e9d)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d34abc)
Location: include/linux/clk.h:1068
Inline: True
```
**Symbols:**

```
ffffffff81a3b470-ffffffff81a3b4b7: clk_prepare_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int clk_prepare_enable(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a870c7)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f36f)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28397)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb1165)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
```
```
In drivers/mfd/twl6040.c (ffffffff81be6104)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5ac03)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/dwc2/drd.c (ffffffff81d5bb3b)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_role_sw_set
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d80bfd)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88e5d)
Location: include/linux/clk.h:1068
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deab6c)
Location: include/linux/clk.h:1068
Inline: True
```
**Symbols:**

```
ffffffff81a86d30-ffffffff81a86d77: clk_prepare_enable (STB_LOCAL)
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
int clk_prepare_enable(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d944)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/imx-weim.c (ffff80001068550c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_probe
```
```
In drivers/bus/qcom-ebi2.c (ffff8000106855e8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/phy/phy-xgene.c (ffff80001068a0e8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
  - drivers/phy/phy-xgene.c:xgene_phy_hw_init
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a1f58)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b6840)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cdd7c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce78c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d0464)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2304)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f488)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721c48)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-rockchip.c (ffff800010728e44)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072ac24)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731c78)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff8000107350e8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff800010735b28)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff800010735e94)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_clk_ctrl
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736bc0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/pci-xgene.c (ffff80001073a08c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff8000107613d0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/amba/bus.c (ffff8000107b9358)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_pm_runtime_resume
  - drivers/amba/bus.c:amba_pm_runtime_resume
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cd658)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
```
```
In drivers/clk/imx/clk.c (ffff8000107d1ea8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_register_uart_clocks
```
```
In drivers/clk/mediatek/clk-mt7622.c (ffff8000107e4f2c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
```
```
In drivers/clk/mediatek/clk-mt8173.c (ffff8000107e56c0)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb698)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/rockchip/clk.c (ffff800011489db0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical
```
```
In drivers/clk/rockchip/clk-cpu.c (ffff8000107eead8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
```
```
In drivers/clk/sunxi/clk-simple-gates.c (ffff80001148cf78)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-simple-gates.c:sunxi_simple_gates_setup
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3738)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_deassert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_mmc_reset_assert
```
```
In drivers/clk/sunxi/clk-usb.c (ffff8000107f3af4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_deassert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_reset_assert
```
```
In drivers/clk/sunxi-ng/ccu-sun8i-de2.c (ffff8000107f9de0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
  - drivers/clk/sunxi-ng/ccu-sun8i-de2.c:sunxi_de2_clk_probe
```
```
In drivers/dma/mv_xor.c (ffff800010808010)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808fdc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148eff0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f4a0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e344)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_asb_power_on
```
```
In drivers/soc/imx/gpcv2.c (ffff80001081818c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff80001081914c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (ffff800010819fb4)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891370)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_runtime_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff8000108929b4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
```
```
In drivers/tty/serial/8250/8250_of.c (ffff8000108935ec)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108947c8)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffff8000108995b0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (ffff80001089a14c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_setup
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e54c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a0118)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1c3c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a4c68)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108dac9c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
```
```
In drivers/misc/sram.c (ffff80001092b854)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffff800010932bd4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffff80001093f89c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/ata/ahci_imx.c (ffff8000109b80ac)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
```
```
In drivers/ata/libahci_platform.c (ffff8000109bcce8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_enable_clks
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d8cec)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_resume
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_resume
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e60b8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a398bc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e15c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-orion.c (ffff800010a5eccc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/rtc/rtc-mv.c (ffff80001149de88)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aad0d4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad3ac)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aae220)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
  - drivers/rtc/rtc-xgene.c:xgene_rtc_resume
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffff800010ab89fc)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abcd34)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_resume
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_runtime_resume
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1a7c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
```
In drivers/mmc/host/mmci.c (ffff800010b46254)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4f3f4)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/clocksource/timer-of.c (ffff8000114a7da4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/timer-rockchip.c (ffff800010b66500)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b440)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/memory/mtk-smi.c (ffff800010b8c234)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
```
**Symbols:**

```
ffff8000107e56c0-ffff8000107e5704: clk_prepare_enable (STB_LOCAL)
ffff800010b66500-ffff800010b66544: clk_prepare_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int clk_prepare_enable(struct clk *clk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_twd.c (c1505e94)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - arch/arm/kernel/smp_twd.c:twd_local_timer_of_register
```
```
In arch/arm/mach-mvebu/mvebu-soc-id.c (c150d3f4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/mvebu-soc-id.c:mvebu_soc_id_init
```
```
In arch/arm/mach-mvebu/platsmp.c (c0331a8c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_sync_secondary_clk
Direct callers:
  - arch/arm/mach-mvebu/platsmp.c:armada_xp_smp_prepare_cpus
```
```
In arch/arm/mach-imx/pm-imx5.c (c150eb84)
Location: include/linux/clk.h:903
Inline: True
```
```
In arch/arm/mach-imx/mmdc.c (c03331bc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In arch/arm/mach-omap2/display.c (c033659c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - arch/arm/mach-omap2/display.c:omap_dss_reset
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c0823450)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_resume
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/imx-weim.c (c0824914)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/bus/imx-weim.c:weim_probe
```
```
In drivers/bus/qcom-ebi2.c (c0826548)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
  - drivers/bus/qcom-ebi2.c:qcom_ebi2_probe
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082be48)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_off
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_power_on
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082caf4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083db30)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0846368)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-dove.c (c084bc6c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c086890c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mvebu.c (c086a478)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (c086c3fc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_syscore_resume
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-vf610.c (c0873884)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a8098)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9c08)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08aca0c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
```
```
In drivers/pci/controller/pcie-rcar.c (c08af09c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b0e58)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/pcie-rockchip.c (c08b3cf4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
  - drivers/pci/controller/pcie-rockchip.c:rockchip_pcie_enable_clocks
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b6104)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_resume_noirq
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_enable_port
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb9fc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bdbd0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_3
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_post_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_3_2
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_1_0_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_init_2_1_0
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08be154)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08beb50)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf238)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (c08e3a6c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/amba/bus.c (c08e5694)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_get_enable_pclk
  - drivers/amba/bus.c:amba_pm_runtime_resume
  - drivers/amba/bus.c:amba_pm_runtime_resume
```
```
In drivers/clk/imx/clk.c (c08f986c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/imx/clk.c:imx_register_uart_clocks
```
```
In drivers/clk/imx/clk-imx5.c (c08fe42c)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/imx/clk-imx5.c:mx53_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx51_clocks_init
  - drivers/clk/imx/clk-imx5.c:mx50_clocks_init
```
```
In drivers/clk/imx/clk-imx6q.c (c08fe680)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
  - drivers/clk/imx/clk-imx6q.c:imx6q_clocks_init
```
```
In drivers/clk/imx/clk-imx6sl.c (c08fe76c)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
  - drivers/clk/imx/clk-imx6sl.c:imx6sl_clocks_init
```
```
In drivers/clk/imx/clk-imx6sx.c (c08fe7a8)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
  - drivers/clk/imx/clk-imx6sx.c:imx6sx_clocks_init
```
```
In drivers/clk/imx/clk-imx6ul.c (c08fe7e4)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
  - drivers/clk/imx/clk-imx6ul.c:imx6ul_clocks_init
```
```
In drivers/clk/imx/clk-vf610.c (c157bba8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/imx/clk-vf610.c:vf610_clocks_init
```
```
In drivers/clk/mediatek/clk-mt7622.c (c0900c00)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7622.c:mtk_topckgen_init
```
```
In drivers/clk/mediatek/clk-mt7629.c (c0901500)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_apmixedsys_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_pericfg_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
  - drivers/clk/mediatek/clk-mt7629.c:mtk_topckgen_init
```
```
In drivers/clk/mediatek/clk-mt8135.c (c09019f4)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/mediatek/clk-mt8135.c:mtk_infrasys_init
  - drivers/clk/mediatek/clk-mt8135.c:mtk_topckgen_init
```
```
In drivers/clk/mediatek/clk-mt8173.c (c0901a30)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
  - drivers/clk/mediatek/clk-mt8173.c:mtk_clk_enable_critical
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904c5c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/rockchip/clk.c (c158300c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_clk_protect_critical
```
```
In drivers/clk/rockchip/clk-cpu.c (c0908268)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk-cpu.c:rockchip_clk_register_cpuclk
```
```
In drivers/clk/samsung/clk-exynos5420.c (c1585a44)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5420.c:exynos5x_clk_init
```
```
In drivers/clk/tegra/clk.c (c1586140)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/tegra/clk.c:tegra_init_from_table
```
```
In drivers/clk/tegra/clk-emc.c (c0912d80)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-emc.c:emc_set_timing
```
```
In drivers/clk/ti/clk.c (c0915d14)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/ti/clk.c:omap2_clk_enable_init_clocks
```
```
In drivers/clk/ti/clk-814x.c (c158d684)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/ti/clk-814x.c:dm814x_adpll_enable_init_clocks
```
```
In drivers/clk/ti/clk-3xxx.c (c091a5cc)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
  - drivers/clk/ti/clk-3xxx.c:omap3_clk_lock_dpll5
```
```
In drivers/clk/ti/clk-7xx.c (c158de24)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clk/ti/clk-7xx.c:dra7xx_dt_clk_init
```
```
In drivers/dma/mv_xor.c (c0925e88)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mxs-dma.c (c158ea10)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
  - drivers/dma/mxs-dma.c:mxs_dma_alloc_chan_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (c158ee44)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/dma/tegra20-apb-dma.c (c0929b40)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_runtime_resume
```
```
In drivers/soc/imx/gpc.c (c0934278)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/imx/gpc.c:imx6_pm_domain_power_on
```
```
In drivers/soc/imx/gpcv2.c (c0934df4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c09359f4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (c0936cc4)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra30.c (c093a504)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_read
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (c093a89c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
```
```
In drivers/soc/tegra/pmc.c (c093afec)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_enable_clocks
```
```
In drivers/regulator/fixed.c (c09554e4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/regulator/fixed.c:reg_clock_enable
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098ddb8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_runtime_resume
```
```
In drivers/tty/serial/8250/8250_of.c (c098e938)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/tty/serial/amba-pl011.c (c09908dc)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/tty/serial/max310x.c (c09938f4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (c0996414)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_console_setup
  - drivers/tty/serial/imx.c:imx_uart_console_setup
```
```
In drivers/tty/serial/meson_uart.c (c09991c0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (c0999e80)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (c099b650)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_console_setup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
  - drivers/tty/serial/msm_serial.c:msm_startup
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1e90)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/iommu/exynos-iommu.c (c09c9df8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
  - drivers/iommu/exynos-iommu.c:__sysmmu_enable_clocks
```
```
In drivers/iommu/qcom_iommu.c (c09cc59c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
  - drivers/iommu/qcom_iommu.c:qcom_iommu_resume
```
```
In drivers/misc/sram.c (c0a0a0a4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/t7l66xb.c (c0a12780)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_resume
  - drivers/mfd/t7l66xb.c:t7l66xb_resume
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable
  - drivers/mfd/t7l66xb.c:t7l66xb_mmc_enable
```
```
In drivers/mfd/tc6387xb.c (c0a12e50)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/tc6387xb.c:tc6387xb_mmc_enable
  - drivers/mfd/tc6387xb.c:tc6387xb_mmc_enable
  - drivers/mfd/tc6387xb.c:tc6387xb_resume
  - drivers/mfd/tc6387xb.c:tc6387xb_resume
```
```
In drivers/mfd/tc6393xb.c (c0a13d50)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/arizona-core.c (c0a15b14)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (c0a2900c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/mfd/omap-usb-host.c (c0a35694)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
  - drivers/mfd/omap-usb-host.c:usbhs_runtime_resume
```
```
In drivers/ata/libahci_platform.c (c0a87a90)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_enable_clks
```
```
In drivers/ata/ahci_imx.c (c0a8aaa0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
  - drivers/ata/ahci_imx.c:imx8_sata_enable
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac951c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_runtime_resume
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/phy/phy-generic.c (c0b0bce4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:usb_gen_phy_init
  - drivers/usb/phy/phy-generic.c:nop_set_suspend
  - drivers/usb/phy/phy-generic.c:nop_set_suspend
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c898)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/dwc2/platform.c (c0b10d68)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-orion.c (c0b30010)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe
```
```
In drivers/usb/host/ehci-exynos.c (c0b30884)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_resume
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_resume
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In drivers/usb/host/ohci-exynos.c (c0b388dc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_resume
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_resume
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
```
```
In drivers/usb/host/uhci-hcd.c (c0b3aa14)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe
```
```
In drivers/rtc/rtc-mv.c (c15a04cc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-omap.c (c0b8c768)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/rtc/rtc-s3c.c (c0b8ee3c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-common.c (c0b98178)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bb84)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e424)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe88c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/cpufreq/tegra20-cpufreq.c (c0c00d20)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_init
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_cpu_init
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate
  - drivers/cpufreq/tegra20-cpufreq.c:tegra_target_intermediate
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c0c00f18)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
```
```
In drivers/mmc/host/mmci.c (c0c20050)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_runtime_resume
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c238)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_ios
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2d0a8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_resume
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2f1ac)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_runtime_resume
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
```
In drivers/firmware/qcom_scm.c (c0c35c98)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/clocksource/timer-of.c (c15aa36c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
```
```
In drivers/clocksource/renesas-ostm.c (c15aa85c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/renesas-ostm.c:ostm_init
```
```
In drivers/clocksource/dw_apb_timer_of.c (c0c490cc)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
```
```
In drivers/clocksource/timer-rockchip.c (c0c49230)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
  - drivers/clocksource/timer-rockchip.c:rk_timer_probe
```
```
In drivers/clocksource/timer-armada-370-xp.c (c0c49668)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_375_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_xp_timer_init
```
```
In drivers/clocksource/timer-orion.c (c15ab7e0)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/timer-orion.c:orion_timer_init
```
```
In drivers/clocksource/exynos_mct.c (c15ac0c4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/exynos_mct.c:mct_init_dt
```
```
In drivers/clocksource/arm_global_timer.c (c15ad8fc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/arm_global_timer.c:global_timer_of_register
```
```
In drivers/clocksource/timer-imx-gpt.c (c0c4c108)
Location: include/linux/clk.h:903
Inline: True
Direct callers:
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
```
```
In drivers/clocksource/timer-imx-tpm.c (c15ae60c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c608d8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/devfreq/exynos-bus.c (c0c6af4c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
```
In drivers/devfreq/event/exynos-nocp.c (c0c6b928)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c684)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/memory/mvebu-devbus.c (c0c724f8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
```
```
In drivers/memory/mtk-smi.c (c0c731e4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_common_resume
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
```
```
In sound/soc/soc-dapm.c (c0ca7b40)
Location: include/linux/clk.h:903
Inline: True
```
```
In sound/soc/codecs/sgtl5000.c (c0cbe860)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0b40)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_read
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_ac97_write
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_hw_params
```
```
In sound/soc/fsl/imx-audmux.c (c0cc1b5c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - sound/soc/fsl/imx-audmux.c:imx_audmux_resume
  - sound/soc/fsl/imx-audmux.c:imx_audmux_resume
  - sound/soc/fsl/imx-audmux.c:imx_audmux_suspend
  - sound/soc/fsl/imx-audmux.c:imx_audmux_suspend
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port
  - sound/soc/fsl/imx-audmux.c:imx_audmux_v2_configure_port
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
  - sound/soc/fsl/imx-audmux.c:audmux_read_file
```
**Symbols:**

```
c0331918-c033195c: clk_prepare_enable (STB_LOCAL)
c08fe42c-c08fe468: clk_prepare_enable (STB_LOCAL)
c08fe680-c08fe6bc: clk_prepare_enable (STB_LOCAL)
c08fe76c-c08fe7a8: clk_prepare_enable (STB_LOCAL)
c08fe7a8-c08fe7e4: clk_prepare_enable (STB_LOCAL)
c08fe7e4-c08fe820: clk_prepare_enable (STB_LOCAL)
c09019f4-c0901a30: clk_prepare_enable (STB_LOCAL)
c0901a30-c0901a6c: clk_prepare_enable (STB_LOCAL)
c091a5cc-c091a608: clk_prepare_enable (STB_LOCAL)
c0c490cc-c0c49108: clk_prepare_enable (STB_LOCAL)
c0c49230-c0c4926c: clk_prepare_enable (STB_LOCAL)
c0c49668-c0c496a4: clk_prepare_enable (STB_LOCAL)
c0c4c108-c0c4c144: clk_prepare_enable (STB_LOCAL)
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
In drivers/gpio/gpio-ftgpio010.c (c0000000008498d8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008910b4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093ac54)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
```
```
In drivers/tty/serial/max310x.c (c00000000093c058)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dd4c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (c0000000009cabac)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (c0000000009d1d58)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (c0000000009e8070)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (c000000000afdef4)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/i2c/busses/i2c-designware-common.c (c000000000b9b90c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_prepare_clk
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
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae9b8)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b3090)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e62fa)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000508078)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559d62)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffe00055afc2)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d226)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffe0005a318a)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a8b2c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffe0005b34c6)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c372)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a12c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffe0006bd92a)
Location: include/linux/clk.h:903
Inline: True
```
```
In drivers/clocksource/timer-of.c (ffffffe00003a22c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/clocksource/timer-of.c:timer_of_init
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6635)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8167b6eb)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d5e1)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816fa84d)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816fb865)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bed5c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dc75c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e332e)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815957d5)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a7db)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c6d1)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816ce65d)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816cf675)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
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
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6bc5)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff816a9acb)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab9c1)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81727c7d)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff8172afc5)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff81736ab7)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fb7fc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818191fc)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181fdce)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818691bc)
Location: include/linux/clk.h:903
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff816c3f2b)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c5e21)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817430bd)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81746405)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/twl6040.c (ffffffff81751ef7)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_set_pll
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/twl6040.c:twl6040_power
```
```
In drivers/usb/dwc2/platform.c (ffffffff8181590c)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:__dwc2_lowlevel_hw_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818331ec)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_power_on
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839d3e)
Location: include/linux/clk.h:903
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_power_on
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8188314c)
Location: include/linux/clk.h:903
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
