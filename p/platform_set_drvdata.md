# Function: <code>platform_set_drvdata</code>

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
In drivers/pinctrl/pinctrl-amd.c (ffffffff814229b6)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81423583)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a699)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8142ac9c)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/platform_device.h:215
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8142ba89)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8142bd64)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142c31a)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8142da3b)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81477bf7)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814787eb)
Location: include/linux/platform_device.h:215
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81478e1c)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff814ab944)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5c93)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c09bc)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/tps65217-regulator.c (ffffffff814df18d)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150f67d)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81579ce1)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157b924)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81584657)
Location: include/linux/platform_device.h:215
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81589719)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff815962c8)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff815a249b)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/phy/phy-generic.c (ffffffff816216a7)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81626708)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d4b3)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81644362)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/power/charger-manager.c (ffffffff81681e81)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816eb22e)
Location: include/linux/platform_device.h:215
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146b0d5)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c9c5)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814755c9)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81475bbc)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81476a4f)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81476db3)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-zx.c (ffffffff814773b3)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81478dc7)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/host/pcie-designware-plat.c (ffffffff814a5c95)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c613b)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814c6ce6)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814c729e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff814fac26)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505636)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510fcc)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81561b93)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff815ced6d)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0988)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff815da747)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815de763)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff815eb0d1)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff815f9482)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81684d71)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169e0d0)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4e33)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/power/charger-manager.c (ffffffff816e2dcd)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8174fd37)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8148a3ed)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148d107)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148ed72)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497b99)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8149818c)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814983ef)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81498753)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8149a1d7)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e819b)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814e8e60)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814e9445)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff8151d8bb)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529826)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815385a7)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d7e2)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e303)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff815fb9c8)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd597)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81607437)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8160b3f0)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff81617ee1)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81627702)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b1319)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cc212)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2f36)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8171323d)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493c6d)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81496ae8)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81498804)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1849)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814a1df6)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814a2049)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814a2340)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff814a3e27)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff814d3c4e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f3d98)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814f49e2)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814f5050)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff8152e8f2)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c2d5)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8154b857)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bdb8)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81551492)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a234f)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff8160f560)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81611330)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8161b337)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8161f4fc)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff8162bd9e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff8163c8cf)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c645d)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e0946)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7620)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8172741d)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b43e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cff52)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d2e08)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d4a81)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d6656)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e0219)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814e07dc)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814e0a3f)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814e0d4c)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff814e10dc)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff814e2b97)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff815140de)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81534478)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8153520e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815358d0)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff8158f5cd)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159ee06)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815aede7)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af348)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4ccd)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81608146)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81677de0)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679bd0)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81683a17)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81687d3c)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff816946fe)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff816a555f)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8173279a)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d1e8)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753e5f)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817989db)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179cbe7)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff815010d3)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81503e4b)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505b1e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f5b7)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8150fb7c)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8150ffcd)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81510236)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8151055c)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff815108cc)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815123d2)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff815129f6)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81569f26)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8156ae6b)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8156b35a)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff815c6997)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6b1e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7537)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815e77fe)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ecf92)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816417f5)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816b3985)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b5693)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff816bfad7)
Location: include/linux/platform_device.h:216
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816c3eee)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d074e)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff816e174d)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771ead)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178da10)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817944a8)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db806)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd930)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e40b2)
Location: include/linux/platform_device.h:216
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515ba3)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8151888a)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8151a66e)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524c67)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8152522c)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8152567d)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff815258e6)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81525c0c)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81525f7c)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81527b22)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81528246)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:217
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560f01)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81581986)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815828fc)
Location: include/linux/platform_device.h:217
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81582eda)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff815dff57)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f03c9)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601977)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81601c5e)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607b23)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165f975)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816d4c45)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d68f3)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff816e0ea7)
Location: include/linux/platform_device.h:217
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816e52de)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff816f1d7e)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81704b6d)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81796fe3)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b409e)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba9fd)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802baf)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f938)
Location: include/linux/platform_device.h:217
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543d23)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81546896)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815487e5)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81553327)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8155393b)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81553d69)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81553fc7)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff815542b9)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff8155460e)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81554b32)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81556d8f)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff815574d3)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:220
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815911f3)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b2007)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815b2fb7)
Location: include/linux/platform_device.h:220
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815b35e6)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff81611a77)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff816221ac)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816342e1)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816345f3)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b922)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694f70)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817104eb)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81712559)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8171a5e2)
Location: include/linux/platform_device.h:220
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8171e8fc)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff8172b342)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff8173e981)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d619a)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f36a0)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa32d)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843f93)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851645)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bcd00)
Location: include/linux/platform_device.h:220
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564c37)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81567696)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81569795)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815749c3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81574f8b)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff815753b9)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81575617)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81575909)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81575c5e)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81576172)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815783af)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81578b03)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d2f87)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815d3f3e)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815d4826)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff81632f27)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643c8c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81656011)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81656323)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165ddf2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7b10)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817347db)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81736859)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8173e8d2)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81742bcc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff8174f592)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81762b61)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8180704f)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818244c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b169)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875903)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81883125)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818ef820)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81607057)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608aeb)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160ae7f)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81618a09)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81619900)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81619be9)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8161a04c)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8161a3de)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff8161a733)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8161ac42)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8161d34f)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8161db13)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:236
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167ccc9)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8167ddfd)
Location: include/linux/platform_device.h:236
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8167e466)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffffffff816995d4)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan.c (ffffffff816dfeb8)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f15d5)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8170612d)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81706403)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170cdd6)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bb90)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817f1d9d)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3e09)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff817fc23a)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff818006ac)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/intel_msic.c (ffffffff8180c5b7)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8180dcc2)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81822906)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d7bb9)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f6120)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fd009)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a2ce)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81951b23)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3a40)
Location: include/linux/platform_device.h:236
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b937)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d210)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162f59e)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81631710)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff8163f249)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff816400e0)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81640319)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8164077c)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81640ade)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81640d33)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff816412f1)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81643caf)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81644333)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:245
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8169ca59)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81c00020)
Location: include/linux/platform_device.h:245
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8169d246)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffffffff816b66f4)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan.c (ffffffff816fde48)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e975)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817233cd)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81723733)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729bf6)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786770)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff818063cd)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81807a69)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81c123de)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff818116ac)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/intel_msic.c (ffffffff8181b817)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8181c9f2)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81831616)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e1dbc)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fecd0)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81905939)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fe5e)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81957097)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3dc0)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f607)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81610e5d)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8161323b)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8161519a)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81622c99)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff816236b0)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff816238e9)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81623d4c)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff816240a9)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff816242e3)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81626a78)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81627093)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:245
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167f82a)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81bf1b1e)
Location: include/linux/platform_device.h:245
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8167ffc6)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffffffff816987a4)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan.c (ffffffff816dfac6)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff816eff95)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817045d5)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81704983)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709b5d)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e4ad)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a0d0)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817eb00d)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec63b)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81c0455c)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817f5ebb)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff817ffdc2)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81814846)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c50cb)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e2420)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e912b)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933d15)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193afd3)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a86a0)
Location: include/linux/platform_device.h:245
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e5f8)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8167ff8d)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8168237b)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684432)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81692e60)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81693099)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81696953)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:240
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff816f482a)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81cee544)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff8170e524)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan.c (ffffffff81757ce6)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176a085)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177fc06)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81780093)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8178551b)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178ad3d)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817ee740)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff8187798b)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8187921b)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81d076a2)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8187f14b)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff8188a1c2)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff8189f006)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195cd85)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e5a0)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819855db)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7115)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff819db834)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff819df7c3)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55890)
Location: include/linux/platform_device.h:240
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8179a1d0)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179bdad)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179e458)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0a33)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b2a54)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff817b39b0)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff817b3c19)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff817b7873)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:252
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81820ecd)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81eb5c5f)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff8183cf04)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan_core.c (ffffffff8188a99d)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189ec07)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b637f)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff818b6893)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bc0cd)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c26d0)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192e7a3)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff819bfc6a)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c17bb)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81ecff9d)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff819c75ed)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff819d34a2)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff819e8b06)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab6be9)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad9cc1)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae1297)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39d99)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81b3f2e5)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b43ff3)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc5080)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b0851)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2689)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b5167)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7bdc)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cc9d4)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff818cdadc)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff818cde19)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff818d203d)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:252
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81950909)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81951f31)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff81972994)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan_core.c (ffffffff819d1476)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8935)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a030f3)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a0383f)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0ab23)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a12820)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8ca70)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81b354fa)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b3a187)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b3e4ba)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff81b4d91e)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81b64fa2)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3f5c1)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64e36)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6cb97)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf719)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81cd56e5)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cdac44)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6d500)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c183)
Location: include/linux/platform_device.h:252
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f3847)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f56f9)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f8207)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fac55)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190fa44)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81910b3c)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81910e79)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8191503d)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:263
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81996de9)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff819983f4)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff819b9064)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan_core.c (ffffffff81a18a66)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a31286)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a4bf43)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c68f)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a539aa)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b855)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad7ab4)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81b88998)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b8d5e7)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b9194d)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff81ba0d8e)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81bb85a2)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca6b63)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccc266)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd41a7)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37805)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81d3d375)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42f04)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddbe34)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea343)
Location: include/linux/platform_device.h:263
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193b077)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193cd69)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193f237)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941fd5)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819578c3)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8195cfad)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:291
Inline: True
```
```
In drivers/acpi/evged.c (ffffffff81a036a4)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/ac.c (ffffffff81a62713)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/acpi/ac.c:acpi_ac_probe
```
```
In drivers/acpi/fan_core.c (ffffffff81a63d36)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c6f6)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a97b93)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a982df)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f75a)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aaccf8)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2ada8)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81bdc898)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81be1507)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81be58ed)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff81bf4eee)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81c0cbf2)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd6d4d)
Location: include/linux/platform_device.h:291
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b7b3)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d8116e)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d8918f)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81deda85)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81df3cc5)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df98b0)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea05af)
Location: include/linux/platform_device.h:291
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
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
In drivers/irqchip/irq-mbigen.c (ffff8000106764e4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676790)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678d60)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff80001067971c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a1b4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b014)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d88c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/brcmstb_gisb.c (ffff800011476a7c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff800010680d20)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
```
```
In drivers/phy/phy-xgene.c (ffff800010688114)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_probe
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffff800010692680)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692cb8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694e8c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffff8000106971a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699cb0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cbc4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a21d4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3950)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a49f0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a65cc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
```
```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7c8c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a95c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aaafc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff800011477988)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ad384)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afa84)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b39ec)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b64e8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b96cc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba984)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bcd20)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cd160)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce278)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce9a8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf280)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d040c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2164)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffff8000106d3034)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffff8000106d42ac)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (ffff8000106d4f24)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffff8000106d5930)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffff8000106d5c30)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffff8000106d5fa0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffff8000106d647c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d65f0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d6c28)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (ffff800011478568)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d9a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e2ec)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721b38)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffff8000107230b4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725888)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727398)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727fc8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072ad34)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffff800010730734)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731860)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800011479c1c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001147a564)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (ffff80001147a6a8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff80001073456c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff800010735c94)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff80001073673c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736b90)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-al.c (ffff8000107376a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-hisi.c (ffff8000107381f4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e5e8)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760730)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761100)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffff800010778f30)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/fan.c (ffff8000107a1550)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffff8000107aef50)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/clk-fixed-factor.c (ffff8000107c4f4c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_probe
```
```
In drivers/clk/clk-fixed-rate.c (ffff8000107c53cc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
```
```
In drivers/clk/clk-fixed-mmio.c (ffff8000107c7f94)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cd5e0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
```
```
In drivers/clk/mvebu/armada-37xx-xtal.c (ffff8000107e8854)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-tbg.c (ffff8000107e8a38)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e9314)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/mvebu/cp110-system-controller.c (ffff8000107ea36c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb6d4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3600)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
```
```
In drivers/clk/sunxi/clk-sun6i-ar100.c (ffff8000107f4804)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun6i-ar100.c:sun6i_a31_ar100_clk_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804810)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff800010807fb8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808f78)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f390)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e0e0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
```
```
In drivers/soc/bcm/raspberrypi-power.c (ffff80001080f14c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (ffff80001081a4a8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (ffff80001081a8dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826a38)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/reset/reset-meson.c (ffff80001084d948)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_probe
```
```
In drivers/reset/reset-zynqmp.c (ffff80001084e178)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/reset/reset-zynqmp.c:zynqmp_reset_probe
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891b5c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892bfc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/8250/8250_of.c (ffff800010893508)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894708)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
```
```
In drivers/tty/serial/imx.c (ffff80001089c07c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e718)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a00c4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1ee8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a4c4c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a681c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d25dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d759c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7da8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108d9f5c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/misc/sram.c (ffff80001092b8a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/bcm2835-pm.c (ffff80001092d950)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e1f8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffff800010939fc4)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffff80001093ebb0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffff80001094e65c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/altera-sysmgr.c (ffff80001094f9dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd6c8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d8ea4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
```
```
In drivers/net/ethernet/broadcom/bgmac-platform.c (ffff8000109e4ff8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e981c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109ed6a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc324)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a38f18)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e84c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/rtc/rtc-efi.c (ffff80001149dda4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-efi.c:efi_rtc_probe
```
```
In drivers/rtc/rtc-mv.c (ffff80001149df3c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aad07c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad2d0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aadea0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba768)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb7a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abcf58)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/power/reset/gpio-restart.c (ffff800010ac99dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffff800010ac9e24)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/supply/charger-manager.c (ffff800010ad04dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/thermal/armada_thermal.c (ffff800010ade040)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1b28)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
```
In drivers/edac/altera_edac.c (ffff800010b16564)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_sdram_remove
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/leds/leds-syscon.c (ffff800010b4afd0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e930)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
```
In drivers/firmware/ti_sci.c (ffff800010b51348)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b564c4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64600)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65840)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b3ac)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7c0dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7c9ec)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (ffff800010b7d8e4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8aee8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
```
```
In drivers/memory/mtk-smi.c (ffff800010b8bee4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
```
In drivers/perf/arm-ccn.c (ffff800010b9375c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96f4c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b977a4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97fd8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98f68)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9ba14)
Location: include/linux/platform_device.h:226
Inline: True
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
In arch/arm/mach-imx/mmdc.c (c03333a8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f05c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fb4c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820314)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0822258)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c08233a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/brcmstb_gisb.c (c154ebd4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/omap_l3_smx.c (c0825bdc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
```
```
In drivers/bus/omap_l3_noc.c (c0826334)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
```
```
In drivers/bus/ti-sysc.c (c0828ec8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/bus/uniphier-system-bus.c (c0829a34)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
```
```
In drivers/pinctrl/pinctrl-as3722.c (c08340bc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c0835658)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (c083746c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083af40)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rza1.c (c083bc20)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083cbf0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083de7c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c08402d4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c08431c8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c0843fbc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c084661c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/aspeed/pinctrl-aspeed.c (c084707c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinctrl_probe
```
```
In drivers/pinctrl/berlin/berlin.c (c0847cd0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c0849628)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a930)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084f5f8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c0851aac)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (c08533fc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/ti/pinctrl-ti-iodelay.c (c0856b0c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857e20)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085a314)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b648)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (c0868340)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868b04)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-htc-egpio.c (c15508e4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869934)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (c086a414)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (c086c2b8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-omap.c (c086d664)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (c086e8a4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (c086f780)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (c08702e0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c0870bc0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tegra.c (c0871850)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (c0872068)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (c08723c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-twl4030.c (c0872d8c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
```
```
In drivers/gpio/gpio-xilinx.c (c0873ecc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/gpio/gpio-zevio.c (c0874204)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (c1550f80)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a69d0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a74f0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a97a4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac5a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08aef50)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (c08afd84)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b2698)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b3124)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b6200)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (c08b984c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c1552324)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb608)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (c15528b0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bd23c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08be2d0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08beb24)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf230)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/video/fbdev/efifb.c (c08e13b4)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (c08e3170)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (c08e38b8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/amba/tegra-ahb.c (c08e60f8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
```
```
In drivers/clk/clk-fixed-factor.c (c08f071c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_probe
```
```
In drivers/clk/clk-fixed-rate.c (c08f0ae4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
```
```
In drivers/clk/clk-fixed-mmio.c (c08f2f04)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904ca8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c15854a8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090cd58)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
```
```
In drivers/dma/mv_xor.c (c0925e18)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (c158ed90)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/dma/tegra20-apb-dma.c (c092a558)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/dma/ti/edma.c (c092eb14)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/dma/ti/omap-dma.c (c0931790)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
```
In drivers/dma/ti/dma-crossbar.c (c0933794)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (c09371d0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (c0937624)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939d7c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c093a448)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_probe
```
```
In drivers/soc/tegra/pmc.c (c093cf68)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (c0944c20)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/fixed.c (c0955758)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
```
```
In drivers/regulator/ti-abb-regulator.c (c095629c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
```
```
In drivers/regulator/tps65217-regulator.c (c0956d90)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe
```
```
In drivers/regulator/twl-regulator.c (c09575c8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/regulator/twl-regulator.c:twlreg_probe
```
```
In drivers/regulator/twl6030-regulator.c (c09581c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
```
```
In drivers/reset/reset-meson.c (c0959cec)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098e014)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c098e85c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/amba-pl011.c (c0990800)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
```
```
In drivers/tty/serial/imx.c (c09972dc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/meson_uart.c (c0999384)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (c0999e24)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (c099b4b8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/tty/serial/omap-serial.c (c09a0160)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1e78)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/tty/serial/owl-uart.c (c09a321c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
```
In drivers/tty/serial/rda-uart.c (c09a4224)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c27e4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/iommu/omap-iommu.c (c09c39cc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
```
```
In drivers/iommu/rockchip-iommu.c (c09c583c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/exynos-iommu.c (c09ca420)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
```
```
In drivers/iommu/qcom_iommu.c (c09cb488)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/misc/sram.c (c0a0a0ec)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/sm501.c (c0a0e0a4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_plat_probe
```
```
In drivers/mfd/asic3.c (c15991c4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0a0fc7c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/t7l66xb.c (c0a126c8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
```
```
In drivers/mfd/tc6387xb.c (c0a12d24)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
```
```
In drivers/mfd/tc6393xb.c (c0a13918)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/wm8350-core.c (c0a22288)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (c0a28370)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/omap-usb-host.c (c0a34ca8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a35d5c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/mfd/syscon.c (c0a38a90)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mtd/nand/raw/omap2.c (c0aab014)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aad198)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7b64)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acaae8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf72c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad543c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
```
In drivers/auxdisplay/arm-charlcd.c (c159d238)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
```
```
In drivers/usb/phy/phy-generic.c (c0b0ba68)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c4e8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
```
In drivers/usb/dwc2/platform.c (c0b114d0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-exynos.c (c0b30658)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In drivers/usb/host/ohci-exynos.c (c0b3869c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
```
```
In drivers/rtc/rtc-efi.c (c15a03f0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-efi.c:efi_rtc_probe
```
```
In drivers/rtc/rtc-mv.c (c15a0574)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-omap.c (c0b8c7a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/rtc/rtc-s3c.c (c0b8edc8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/rtc/rtc-twl.c (c0b8fd00)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99d14)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bbf4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9ca6c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e4d8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba9298)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
```
```
In drivers/power/reset/gpio-restart.c (c0baa6bc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c0baaaf4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/supply/charger-manager.c (c0bb0d0c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe3b0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/thermal/armada_thermal.c (c0bbfc04)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/edac/armada_xp_edac.c (c0bf21c4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/edac/armada_xp_edac.c:aurora_l2_remove
  - drivers/edac/armada_xp_edac.c:aurora_l2_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_remove
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
```
```
In drivers/cpufreq/tegra20-cpufreq.c (c0c00c38)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c0c00f78)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b190)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2cf04)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_init
```
```
In drivers/leds/leds-syscon.c (c0c3429c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37c7c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/tegra/bpmp.c (c0c424c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
```
```
In drivers/clocksource/sh_cmt.c (c0c45084)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_mtu2.c (c0c456c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
```
```
In drivers/clocksource/sh_tmu.c (c0c467d4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/em_sti.c (c0c46e68)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_probe
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5bd34)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c6084c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/tegra-hsp.c (c0c616b0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
```
```
In drivers/devfreq/exynos-bus.c (c0c6aeec)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
```
In drivers/devfreq/event/exynos-nocp.c (c0c6b920)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c5a8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/memory/omap-gpmc.c (c0c711e4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/memory/mtk-smi.c (c0c72fb4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
```
In drivers/memory/samsung/exynos-srom.c (c0c73394)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
```
In drivers/memory/tegra/mc.c (c0c73f54)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c75ba4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
```
```
In drivers/perf/arm-ccn.c (c0c7c8a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In sound/soc/fsl/imx-sgtl5000.c (c0cc2c58)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
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
In drivers/pinctrl/pinctrl-as3722.c (c00000000082ed9c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f578)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (c00000000083236c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c00000000083520c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/gpio/gpio-mmio.c (c00000000084964c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c000000000849b38)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (c00000000084ab9c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (c00000000084b100)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (c00000000084c234)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c00000000084cf14)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (c00000000084d308)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (c00000000084d758)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (c00000000084dfb0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (c0000000013a1ac0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088e96c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f6fc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-host-common.c (c0000000008917a4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/video/fbdev/simplefb.c (c0000000008c4bfc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d2360)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093b510)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dd04)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (c0000000009cac10)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cdbe0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (c0000000009e1364)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (c0000000009e7248)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (c0000000009faf80)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/usb/dwc2/platform.c (c000000000afe85c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/rtc/rtc-generic.c (c0000000013b4294)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/rtc/rtc-generic.c:generic_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dcf8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-opal.c (c000000000b9e994)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
```
```
In drivers/power/reset/gpio-restart.c (c000000000bab870)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c000000000babb38)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/supply/charger-manager.c (c000000000bb435c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/leds/leds-syscon.c (c000000000c401a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
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
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049db8c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049f158)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049fb14)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0d18)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ae316)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004aebbe)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffe0004aefcc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffe0004af34a)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (ffffffe0004afed4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffffffe0004b0776)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffe0004b09fa)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffe0004b0ce2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b30d8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
```
```
In drivers/pwm/pwm-stmpe.c (ffffffe00002b62a)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e46e2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e54e0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e68f6)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffffffe0004ea626)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000507efe)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/clk/clk-fixed-factor.c (ffffffe00051245c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_probe
```
```
In drivers/clk/clk-fixed-rate.c (ffffffe000512838)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
```
```
In drivers/clk/clk-fixed-mmio.c (ffffffe000514c4a)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d208)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559f4c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d1d8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/sifive.c (ffffffe00055dbe2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_probe
```
```
In drivers/misc/sram.c (ffffffe0005a31d2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4fd0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffe0005aeaea)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffe0005b29c8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffe0005bf4c0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c2e8)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a6b4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf1b4)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/gpio-restart.c (ffffffe0006c7a84)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffffffe0006c7c52)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006ccd5a)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/edac/sifive_edac.c (ffffffe00003947e)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/edac/sifive_edac.c:sifive_edac_init
```
```
In drivers/leds/leds-syscon.c (ffffffe00071e004)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155d227)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155eb66)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a96f)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8156af82)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a66e3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c6f97)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c7f4a)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815c8576)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161c071)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81623c92)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d570)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816fa86b)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff81704502)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81717251)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bf42f)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dc8a0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e3549)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81890b50)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154dca6)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154fda5)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155afd3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8155b682)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81595883)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816105a1)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816108b3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816182e2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c660)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff816ce67b)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d7f82)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff816ef781)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81849ed0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558f67)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155b9c6)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155dac5)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568cf3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff815692bb)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff815696e9)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81569947)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81569c39)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81569f8e)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8156c0ff)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8156c853)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6c73)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c7527)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c84da)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815c8b06)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff81627207)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637acc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649e51)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8164a163)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651c32)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab950)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff81727c9b)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729d19)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81731d92)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8173608c)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff81742a52)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81756021)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fbecf)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81819340)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181ffe9)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868b68)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186adb3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff818785d5)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e4650)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572df7)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815759e6)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815779e5)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582c13)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff815831db)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81583609)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81583867)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81583b59)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81583eae)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff815843c2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815865ff)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81586d53)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e10c7)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815e207e)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815e2966)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff816410b7)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651dfc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816643e1)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816646f3)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166c2c2)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c5db0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/misc/sram.c (ffffffff817430db)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81745159)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8174d1d2)
Location: include/linux/platform_device.h:226
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817514cc)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/syscon.c (ffffffff8175de92)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/e820.c (ffffffff81771491)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81815fdf)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81833330)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839f59)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884d43)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893f75)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819012b0)
Location: include/linux/platform_device.h:226
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
</details>
</li>
</ul>

## Differences
