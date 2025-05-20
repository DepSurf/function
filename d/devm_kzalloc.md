# Function: <code>devm_kzalloc</code>

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
In fs/debugfs/file.c (ffffffff8131ebc6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814227a6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814234e7)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429dfb)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a656)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8142abe6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-sx150x.c (ffffffff8142b404)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:653
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8142b9d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8142bc06)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142c1d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8142d9e6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/acpi/fan.c (ffffffff814ab905)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c08ea)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150a493)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8150df60)
Location: include/linux/device.h:653
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150f65f)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815290f8)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
```
In drivers/base/regmap/regmap.c (ffffffff81562856)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff8156c3f6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff815798b6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157af2f)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157b8b4)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff815821d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81583f96)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff815840ba)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff815854c6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65217.c (ffffffff815855f5)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81585a1a)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81586a96)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81586cb6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81587164)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff81587ab7)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:653
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815895e5)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81589d38)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158ba06)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8158bd76)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8158c1d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8158d48c)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8158d616)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/axp20x.c (ffffffff8158d7d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8158db96)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8158de60)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8158e176)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8158e6f6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8158e91f)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8158ee26)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8158f2c6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81590218)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81590ae6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff815916c6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81591fd6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff815929d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8159327b)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81593b26)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8159401f)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff815947d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81594d35)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff8159512d)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81595ca6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff81596206)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81596418)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81596779)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/region.c (ffffffff8159ad35)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/ata/ata_piix.c (ffffffff815e3253)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/usb/phy/phy-generic.c (ffffffff81621381)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8162646d)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff8162f7ac)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/power/charger-manager.c (ffffffff81681c1e)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff816cd0b7)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff816e37ab)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/clk/clk-gpio.c (ffffffff816eaf6e)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816eb1d6)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff816ed267)
Location: include/linux/device.h:653
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff816ef15c)
Location: include/linux/device.h:653
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In fs/debugfs/file.c (ffffffff81353e56)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff81413198)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146aef6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c6c9)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81475586)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81475b06)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-sx150x.c (ffffffff81476462)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:657
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81476996)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81476c36)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-zx.c (ffffffff81477276)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81478d76)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff81498466)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/host/pcie-designware-plat.c (ffffffff814a5bb6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/acpi/fan.c (ffffffff814fabdf)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510efa)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8155c2a5)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155c873)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff815603be)
Location: include/linux/device.h:657
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81561b75)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8157cc46)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
```
In drivers/base/regmap/regmap.c (ffffffff815b7226)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff815c17c6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff815ce979)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815cff7f)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0917)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff815d82b6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff815da056)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff815da17a)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff815db5a6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff815db73a)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff815dbbd6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff815dbc86)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff815dc194)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff815dcb29)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:657
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815de645)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff815dead8)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e0c86)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff815e0fc6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff815e1426)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff815e269c)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff815e2826)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff815e2a76)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff815e2d40)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff815e3056)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff815e35a6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff815e37cf)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff815e3cd6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff815e4136)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff815e5098)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff815e58d6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff815e6496)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff815e6dc6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff815e7826)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff815e80bb)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff815e89c6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff815e8ecf)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff815e9676)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff815e9bd5)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff815e9fbd)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff815eaa96)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff815eafdb)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff815eb218)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff815eb559)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff815f0742)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815f7b4f)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f85b3)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/dax_devs.c (ffffffff815f92a4)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
```
In drivers/ata/ata_piix.c (ffffffff8163cf6a)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/usb/dwc2/platform.c (ffffffff816848bb)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff8169065c)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/power/charger-manager.c (ffffffff816e2b5e)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8173000c)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81747ac9)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/clk/clk-gpio.c (ffffffff8174f9be)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8174fce6)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff817521f2)
Location: include/linux/device.h:657
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81753e6a)
Location: include/linux/device.h:657
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In fs/debugfs/file.c (ffffffff8136a106)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff8142e6c8)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8148a206)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148b02c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148cdf8)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e9a4)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497b56)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814980d6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81498336)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814985d6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8149a186)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814b9d16)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/host/pcie-designware-plat.c (ffffffff814c7ce6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/acpi/fan.c (ffffffff8151d874)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff8153822e)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81538556)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d679)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81588b10)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff815891b3)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8158cb26)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e2e5)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815a9106)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
```
```
In drivers/base/regmap/regmap.c (ffffffff815e6536)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff815f0c06)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff815fb5d9)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fcb8f)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd527)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81604fa6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81606d46)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81606e6a)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81608276)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8160840a)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816088a6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81608956)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81608e64)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816097f9)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8160b2d5)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8160b768)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160d926)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8160dc66)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8160e0c6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8160f54c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8160f6d6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8160f926)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8160fbf0)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8160ff06)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81610456)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8161067f)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81610b86)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81610fe6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81611f48)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81612786)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81613336)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81613c36)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff81614636)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81614ecb)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816157d6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81615cdf)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81616486)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff816169e5)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81616dcd)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816178a6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff81617deb)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81618028)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81618369)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161d676)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81625dbf)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626823)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81627524)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
```
In drivers/ata/ata_piix.c (ffffffff8166dfea)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8167dda4)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b0e66)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff816be70c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700f20)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff81712fce)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81714336)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8176300c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8177b3e1)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff8177dfd5)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8178040a)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In kernel/irq/devres.c (ffffffff810ea9e3)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8137e776)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff8143b9e8)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493a36)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8149495c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814966fd)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814983bf)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1806)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814a1d46)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814a1f96)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814a2216)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff814a3dd6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/probe.c (ffffffff814a633d)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814c43f6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff814d3bc6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/acpi/fan.c (ffffffff8152e8cd)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff8154b4ce)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8154b806)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154baae)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8155131a)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8159cff9)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159d48c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff815a0bf2)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a2331)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815badc1)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff815beec6)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff815faf16)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff81604d64)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff8160f336)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8161092b)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816112ba)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81618e76)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8161ab86)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8161ad01)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8161c126)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8161c2ba)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8161c716)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8161c7c6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8161ccd8)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8161d8e5)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8161f404)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8161f878)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81621a26)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81621d66)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816221b6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8162360c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81623796)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816239e6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81623cb3)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81623fb6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816244f6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8162472f)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81624c36)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81625086)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81625fb8)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81626826)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81627396)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81627c06)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff81628626)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81628ebb)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81629755)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81629c2a)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8162a3c6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8162a8ec)
Location: include/linux/device.h:662
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8162accd)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8162b7b6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8162bcab)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8162bf18)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8162c244)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81631b01)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8163aecc)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163c3f2)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/dax_devs.c (ffffffff8163c725)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81682580)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81692ed2)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c5fb6)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff816d2f76)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81716770)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/nvmem.c (ffffffff8171b4dc)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817273cf)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b201)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c80c)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8178162b)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81799db9)
Location: include/linux/device.h:662
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff8179ca77)
Location: include/linux/device.h:662
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
In kernel/irq/devres.c (ffffffff810f2f33)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff813a3376)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff814679f8)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cfcc6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0c12)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d29ff)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d4603)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5f42)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e01d6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814e0726)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814e0986)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814e0c16)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff814e1026)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff814e2b46)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/probe.c (ffffffff814e517d)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff81504550)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff81514056)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/acpi/fan.c (ffffffff8158f5a7)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815a02f5)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff815aeab6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815aed96)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af03e)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4b3e)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816024a3)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160299c)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff81606322)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81608128)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81621417)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816254a6)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffff816630d6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff8166d144)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81677bb6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816791ab)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679b5a)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81681516)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81683266)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816833e1)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81684816)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816849aa)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81684e06)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81684eb6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81685518)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8168612b)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81687c44)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816880b8)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168a256)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8168a596)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8168aa06)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8168beec)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8168c086)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8168c2d6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8168c5a3)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8168c8a6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8168cde6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8168d01f)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8168d526)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8168d976)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8168e8ab)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8168f0f6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8168fc66)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81690516)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff81690f36)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816917d1)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81692075)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8169254a)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81692cf6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8169322c)
Location: include/linux/device.h:659
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8169360d)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816940f6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8169460b)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81694878)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81694be5)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81694edf)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a461)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816a3adc)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a5082)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/dax_devs.c (ffffffff816a53b5)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
```
In drivers/ata/ata_piix.c (ffffffff816ebdb0)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff816fcd31)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/dwc2/platform.c (ffffffff817322b6)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff8173f636)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787975)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/nvmem.c (ffffffff8178c77c)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/rtc/nvmem.c:rtc_nvmem_register
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8179898d)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c9a1)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8179dfde)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff817f7c0b)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81810159)
Location: include/linux/device.h:659
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff81813a7c)
Location: include/linux/device.h:659
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
In kernel/irq/devres.c (ffffffff810fb2e5)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff813d2bcf)
Location: include/linux/device.h:674
Inline: True
```
```
In block/badblocks.c (ffffffff8149b868)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500ecd)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501b00)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81503a2e)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505624)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f593)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8150fafa)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8150ff23)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff815101a3)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81510443)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff8151082e)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8151239d)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815124bd)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/probe.c (ffffffff81514725)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/dpc.c (ffffffff815358a0)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:674
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff81581068)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/fan.c (ffffffff815c6975)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815d7f85)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff815e6d23)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7252)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815e77be)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ece0e)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8163b762)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163bc77)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8163ef50)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816417d7)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8165f7c5)
Location: include/linux/device.h:674
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8166009e)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff8169e9e5)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff816a8ba1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff816b365a)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4c8b)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b5626)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff816bd585)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff816bf2e6)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816bf482)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816c08cc)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816c0a4b)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816c0eb9)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff816c0f65)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff816c15c8)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816c2121)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:674
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816c3dc1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816c41e8)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c6373)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff816c66c5)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816c6af3)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff816c7fbc)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816c817a)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816c83bc)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816c8673)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff816c8989)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816c8ef9)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816c911f)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff816c965a)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816c9aaa)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816caa6b)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816cb22d)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816cbd9d)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff816cc615)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff816cd094)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816cd8f1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce1a5)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff816ce65e)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff816cee6e)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff816cf355)
Location: include/linux/device.h:674
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff816cf739)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816d0283)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d06b6)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff816d0948)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816d0cb1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816d0f9f)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d672f)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816dfc48)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e0970)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/dax_devs.c (ffffffff816e15c7)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
```
In drivers/ata/ata_piix.c (ffffffff817286f1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff81733d90)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8173a4d1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:674
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771bf2)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff817800aa)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8a16)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/rtc/nvmem.c (ffffffff817cedef)
Location: include/linux/device.h:674
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db779)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd7da)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e45da)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff817e5336)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818411d6)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8185a0e1)
Location: include/linux/device.h:674
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff8185d8b5)
Location: include/linux/device.h:674
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
In kernel/irq/devres.c (ffffffff81106aa5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In mm/hmm.c (ffffffff812a6ec0)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_add
```
```
In fs/debugfs/file.c (ffffffff813ed4af)
Location: include/linux/device.h:678
Inline: True
```
```
In block/badblocks.c (ffffffff814b5b78)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8151599d)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815165d0)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8151846d)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8151a174)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524c43)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff815251aa)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff815255d3)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81525853)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81525af3)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81525ede)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81527aed)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81527c0d)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/probe.c (ffffffff81529e85)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff8154aff9)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff8154cf30)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:678
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560af0)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/acpi/acpi_apd.c (ffffffff81599208)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/fan.c (ffffffff815dff35)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff815f1895)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81601153)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601682)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81601c1e)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607a0d)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81659992)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81659ea7)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8165d150)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165f957)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8167dc85)
Location: include/linux/device.h:678
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e6f1)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff816bf1e5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff816c9781)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff816d491a)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d5ebb)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d6886)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff816de7d5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff816e06b6)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816e0852)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816e1d0c)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816e1e8b)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816e22f9)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff816e23a5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff816e2a08)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff816e3561)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:678
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816e51b1)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816e55d8)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e7773)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff816e7ac5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816e7f13)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff816e947c)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816e967a)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816e98bc)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff816e9b73)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff816e9ee9)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816ea43e)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816ea69f)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff816eabda)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816eb02a)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ebf2b)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816ec7cd)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816ed34d)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff816edbd5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff816ee654)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816eeeb1)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816ef7c5)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff816efc7e)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff816f041e)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff816f0975)
Location: include/linux/device.h:678
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff816f0d59)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816f18a3)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff816f1ce6)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff816f1fe8)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816f2354)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816f2642)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f850e)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81702008)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81702eeb)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81703c17)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
```
```
In drivers/ata/ata_piix.c (ffffffff8174aed1)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff8175690b)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8175dc11)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:678
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81796cfe)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff817a68aa)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f00b6)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802b22)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f8bc)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81810dc6)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8186d095)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81879381)
Location: include/linux/device.h:678
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff8187d1fb)
Location: include/linux/device.h:678
Inline: True
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
In kernel/irq/devres.c (ffffffff81110096)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff81418f57)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff814e40c8)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543b1d)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815447f0)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815465ce)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815485fb)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81553302)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81553890)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81553ce4)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81553f30)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff815541bd)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81554569)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81554b09)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81556d5a)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81556e64)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/probe.c (ffffffff81559125)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff8157aecd)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff8157c9b0)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:681
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81590eeb)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/acpi/acpi_apd.c (ffffffff815ca6c9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/fan.c (ffffffff81611a57)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8162378d)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81633aa4)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81633fc5)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816345a9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b7fd)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8168ee7d)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8168f2a7)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8169308a)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694f52)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81695455)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816b49c5)
Location: include/linux/device.h:681
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5696)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff816fa345)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff81704d15)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81710410)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81710e57)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817124f2)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81717fc5)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81719e22)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81719f9b)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8171b3c8)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8171b52a)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8171b99f)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8171ba45)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8171bf68)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8171d0ed)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:681
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8171e841)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8171ed28)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81720f30)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81721295)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff817216f3)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81722bfc)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81722dda)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8172301c)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81723303)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81723699)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81723b9e)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81723dff)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8172431a)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8172477a)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817256c5)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81725f4d)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81726acd)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81727345)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff81727bd0)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81728540)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81728ed1)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff817293ae)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81729ade)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8172a036)
Location: include/linux/device.h:681
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8172a3b9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8172af23)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8172b2a6)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8172b578)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8172b8cb)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8172bba1)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731bd3)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8173be7b)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81786dff)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff81792ed8)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff8179b23d)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:681
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d5d89)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff817e5ac9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830515)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843f25)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8184faa9)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff8185198f)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81852cde)
Location: include/linux/device.h:681
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818b0f25)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818be49f)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/soundwire/mipi_disco.c (ffffffff818c2fec)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
```
```
In drivers/devfreq/devfreq.c (ffffffff818c747e)
Location: include/linux/device.h:681
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff8111c316)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff81432e17)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff814fd488)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564a2b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815656d0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8156738e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815692c1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8157499d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81574ee0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81575334)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81575580)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8157580d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81575bb9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81576149)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8157837a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81578484)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/probe.c (ffffffff8157a6f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff8159c90d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff8159e419)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff815eb8d9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/fan.c (ffffffff81632f07)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8164527d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff816557d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655cf5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816562d9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165dccd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816b16ad)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b1ace)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff816b5c2a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7af2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b7fe5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816d76a5)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d8376)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff8171e6f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff81728fd5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81734700)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81735147)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817367f2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8173c2d5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8173e112)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8173e28b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8173f698)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8173f7fa)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8173fc6f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8173fd15)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81740234)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff817413bd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81742b11)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81742ff8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817450b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81745535)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81745993)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81746e9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8174707a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff817472bc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817475a3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81747939)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81747e3e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8174809f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff817485ba)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81748a2a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81749975)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8174a20d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8174ad8d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff8174b5f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff8174be80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8174c790)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d121)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8174d5ee)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174dd1e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8174e236)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8174e5b9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8174f123)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8174f4f6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8174f7c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8174fb1b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8174fdf1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755d43)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175fb9b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff817aaa3f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff817b6a28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817beced)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81806c39)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff81816989)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861e45)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875895)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff818814b9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff8188346f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818e33e5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818f0fef)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff818f993a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff81128646)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff81482407)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff8155c8e8)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606e4b)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff816078b1)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608a16)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160ac94)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff816189e3)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81619850)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81619b64)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81619fb0)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8161a2dd)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff8161a689)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8161ac19)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8161d31a)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8161d580)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff8163c555)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:210
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff81697329)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff81699579)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan.c (ffffffff816dfe98)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f2889)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f3acd)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff817058fc)
Location: include/linux/device.h:210
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81706044)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff817063b9)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170ccc9)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/reset/reset-brcmstb-rescal.c (ffffffff817332d9)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81764cca)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8176504e)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8176924a)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bb72)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c0c5)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8178bb75)
Location: include/linux/device.h:210
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178ca66)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff817da5f5)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff817e57e5)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff817f1cfe)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f2707)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3da2)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff817f9bef)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817fbaa2)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff817fbc1b)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff817fd138)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff817fd29a)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff817fd70f)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff817fd7b5)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817fdce2)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff817ff04b)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:210
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff818005f1)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff818013b8)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81802e3f)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81803215)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81803613)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81804b9c)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81804cfa)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81804fbc)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff818052a3)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81805639)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81805bae)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81805f0f)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff818063ca)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8180684a)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff818078b5)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81807f6d)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81808cfd)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81809685)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff81809f0a)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8180a7e0)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b2e2)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8180b7ee)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180bf5e)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/intel_msic.c (ffffffff8180c55f)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_probe
```
```
In drivers/mfd/palmas.c (ffffffff8180c786)
Location: include/linux/device.h:210
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8180cc2b)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8180d7f3)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8180dc26)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8180df18)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8180e26b)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8180e541)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81815479)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8181f6bb)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81870abb)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff8187d838)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81887acd)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:210
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d78c9)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff818e7a0e)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935675)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a292)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff8194dc2c)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8194fc9d)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff81951e60)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b64c5)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c65db)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff819d04c2)
Location: include/linux/device.h:210
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff81123f86)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8149faa7)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff81578a38)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b71d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162c05f)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d14f)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162f386)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff816314c8)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff8163f223)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81640030)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81640294)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff816406e0)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff816409dd)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81640c89)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff816412ce)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81643c7a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81643dc0)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff81663414)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167ceb9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff816b4379)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff816b6699)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan.c (ffffffff816fde28)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8170fab9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81710c4d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81722bec)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817232e4)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff817236e9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729ae9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/reset/reset-brcmstb-rescal.c (ffffffff8174f479)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8177fbea)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8177ffae)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff81784076)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786752)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786bf7)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff817a2125)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a3006)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff817ef3a5)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff817fa475)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff8180632e)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806cc7)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81807a02)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8180c6df)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8180dbb2)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8180dceb)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8180eb78)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8180ecba)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8180f03f)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8180f0d8)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8180f562)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8181047b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff818115f1)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81812308)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813ccf)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81814363)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8181551c)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8181565a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff818158dc)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81815b93)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81815ee9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81816354)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8181672f)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff818169ea)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81816b4a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff818178f5)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81817f2d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81818bcd)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff818194d3)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff81819b4a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8181a110)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8181aa62)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8181abbe)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181b29e)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/intel_msic.c (ffffffff8181b7bf)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_probe
```
```
In drivers/mfd/palmas.c (ffffffff8181b906)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8181bd3b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8181c573)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8181c956)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8181cc28)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8181ce7b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8181d101)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824669)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8182e5fb)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff8187f78b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff8188bd58)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81895d83)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e1a67)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff818f09ee)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c6e5)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fe22)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff8195361c)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8195565d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff819573b1)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b8a05)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819c64cb)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff819cff2c)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff811242d6)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff814a5aa7)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff81580788)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f3ed)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160fc7e)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81610ae5)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81613026)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81614c41)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81622c73)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81623600)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81623864)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81623cb0)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81623fad)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81624239)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81626a4a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626b80)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff816458cf)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fd38)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff816965a9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff81698749)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan.c (ffffffff816dfaa7)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff816f1389)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816f251d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81703e8a)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8170444b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81704939)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff817095d9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e38b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8176351a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817638de)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8176796b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a0b2)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a557)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81784e17)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785d16)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff817d3c45)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff817df185)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff817eaf6e)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb8f7)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec5d2)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff817f0f55)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817f2396)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff817f24cf)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff817f33ac)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff817f34ea)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff817f386f)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff817f3908)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817f3d92)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff817f4abb)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817f5d61)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817f6a48)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f83df)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff817f8a43)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff817f9bfc)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817f9d3a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff817f9fac)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff817fa253)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff817fa599)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff817fa979)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817fab94)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff817fae4a)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff817fafaa)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fbd65)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff817fc36d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff817fcfed)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff817fd830)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff817fe191)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff817fe2fe)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff817fe9fe)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff817fecf6)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff817ff09d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817ff933)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff817ffd26)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff817fffc8)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8180020b)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81800491)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81807893)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff818118cb)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81861ffb)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff8186e6b8)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff818785f3)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:215
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c4d77)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff818d41de)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191ff7c)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933cd9)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819374ac)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff8193943d)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193b2f3)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8199d135)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a8a86)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff819ab37c)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff819b5089)
Location: include/linux/device.h:215
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff811448d6)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff814fdc67)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff815e5aa8)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e319)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167ed0e)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8167fc15)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81682166)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81683ed1)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81692400)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81692db0)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81693014)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8169353a)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8169378a)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81693a59)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff816960a5)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81696410)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff816b6abf)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d2958)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff8170c349)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff8170e4c9)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan.c (ffffffff81757cc7)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff8176b489)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8176c75d)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff8177ec8a)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177fa4e)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81780049)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784f89)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178ac1b)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b1f65)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff817e77ba)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e7cbe)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec370)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817ee722)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef557)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8180b947)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180cba6)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f4be)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/regmap/regmap.c (ffffffff8185fa55)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff8186abf5)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff818778a2)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81878477)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff818791b2)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff818795e5)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8187afe6)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8187b11f)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8187c2fc)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8187c40a)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8187c7ef)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8187c888)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8187cc36)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8187db1b)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8187eff1)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187fd58)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8188182f)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81881e93)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff818830ac)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff818831ea)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8188345c)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81883743)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81883a89)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81883e69)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81884084)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8188433a)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8188449a)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81885315)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8188591d)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81886acd)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff818875d0)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81888043)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff818881ae)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff818888fe)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81888c96)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81888e9d)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff8188a126)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8188a3b8)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8188a5fb)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8188a891)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81892183)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8189bf7c)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff818f0fd2)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff818fe758)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81909503)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:206
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195c9d9)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff8196ee1e)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2c1c)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d70d9)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819db54c)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff819db819)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff819ddb3d)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff819dfad8)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81a49b55)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a56cf6)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81a58e59)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff81a63bf9)
Location: include/linux/device.h:206
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff81168819)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8158e80c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff81694c98)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799f39)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179a80e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179ba71)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179e216)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0352)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b29db)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff817b2e60)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff817b3900)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff817b3b94)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff817b416e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff817b4420)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff817b6f05)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7290)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff817da68f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbdee)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff8183a9c3)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff8183cea9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan_core.c (ffffffff8188a97e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff818a0129)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff818a170b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff818b5b7a)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b6199)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff818b6849)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbb71)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c25bb)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/xen/grant-dma-ops.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/regulator/irq_helpers.c (ffffffff818ed8c5)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81927157)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192783e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8192aef8)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192e785)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f8f5)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8194beb1)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194d20e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff819706ae)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/regmap/regmap.c (ffffffff819a7f25)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff819b38db)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff819bfb80)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c082a)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c1752)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff819c1c05)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff819c3826)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff819c3970)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff819c4c9c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff819c4dd5)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff819c51e9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff819c5298)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl-core.c (ffffffff819c6007)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff819c7501)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c8358)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819ca08f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff819ca71a)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff819cbab9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff819cbc7a)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff819cbedc)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff819cc233)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff819cc5ee)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff819cca19)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff819ccce4)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff819ccfb1)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff819cd141)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819ce096)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff819ce6fd)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff819cf9ad)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff819d0591)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff819d10dd)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff819d129e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff819d1a6e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff819d1e25)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff819d213d)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff819d3406)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff819d36f6)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff819d3929)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff819d3bda)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dc41f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff819e57c4)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81a433aa)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff81a50038)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81a5cb5f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab685f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff81ac955e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b23070)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39d5a)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81b3ef9c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81b3f2cd)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b3fbdf)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81b42137)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b4430c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81bb7f60)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc649c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81bc8c59)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/mailbox/pcc.c (ffffffff81bcaa3e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd498b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff8119cfc9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8163587c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff81753cb8)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b0521)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b10de)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2351)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b4f26)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b74b2)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cc95b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff818cce61)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff818cda30)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff818cdd94)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff818ce40e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff818ce710)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff818d1535)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1970)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff818fc054)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/p2pdma.c (ffffffff8191c3ef)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/doe.c (ffffffff8192040f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pci/doe.c:pcim_doe_create_mb
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81929075)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/video/aperture.c (ffffffff8192ed0c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81970033)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff81972939)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan_core.c (ffffffff819d1457)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff819e9579)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff819eae04)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81a02c2a)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a030a9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a03659)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07a7b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a6b1)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a1270b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a3554c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a453d5)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/reset/reset-simple.c (ffffffff81a477b0)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81a83db7)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a8452e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81a88020)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89688)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8ca52)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8dcc5)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81aaff71)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab14b1)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb4ce)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/regmap/regmap.c (ffffffff81b19745)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff81b285eb)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81b35410)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36b5a)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81b37515)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81b39d4b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81b39edf)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81b3bacc)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81b3bdea)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81b3c1c9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81b3c2d8)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl-core.c (ffffffff81b3c98b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b3e381)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b3ef78)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b4151f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b41c2f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81b436e9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81b438cf)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81b43bbc)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b43fd3)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81b4443e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b4498f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81b44ede)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81b454b6)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b45967)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46cf6)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b473f7)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b488f7)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b497c8)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a776)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81b4abcd)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b4b51e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81b4b975)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81b4c24d)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff81b4d886)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81b4dbd6)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81b4def9)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81b4e2ca)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b579e5)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81b61694)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81bc995b)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff81bd9168)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81be770f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81bf36b0)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:207
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3f27f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff81c5397e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb5902)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf6da)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81cd536c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81cd56cd)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd616f)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81cd8847)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cdb11c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81d5cc30)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6e61c)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
```
In drivers/platform/x86/intel/pmc/tgl.c (ffffffff81d6f36a)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81d71f55)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/mailbox/pcc.c (ffffffff81d7412e)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c046)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81d80a88)
Location: include/linux/device.h:207
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff811aee5f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8166db8c)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff8178fe68)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f3505)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f4162)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f53a5)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f7fc6)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fa572)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190f9cb)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff8190fec1)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81910a90)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81910df4)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8191146e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81911770)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81914525)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914960)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff8193f17f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/p2pdma.c (ffffffff8195f793)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d2b5)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:312
Inline: True
```
```
In drivers/video/aperture.c (ffffffff81972fdc)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff819b65f5)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff819b9009)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan_core.c (ffffffff81a18a47)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a31c99)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a33524)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81a4ba7a)
Location: include/linux/device.h:312
Inline: True
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a4bef9)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c4a9)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50908)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53531)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81a7ef6e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8f585)
Location: include/linux/device.h:312
Inline: True
```
```
In drivers/reset/reset-simple.c (ffffffff81a91960)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81acf417)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81acfd1e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81ad3710)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4e60)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad7a96)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9475)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81afbdc1)
Location: include/linux/device.h:312
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afd5de)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b2978e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/regmap/regmap.c (ffffffff81b6aa05)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff81b7879b)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81b888d0)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b89fda)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81b8a985)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81b8d1a8)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81b8d33f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81b8eeec)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81b8f20a)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81b8f619)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81b8f6f8)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl-core.c (ffffffff81b8fdae)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:312
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b91811)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b923f8)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b9488f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b94f9f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81b96a59)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81b96c6f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81b96f6c)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81b973b3)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81b9783e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b97d3f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81b98289)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81b98886)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b98d37)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b9a0c6)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b9a7c7)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b9bd57)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b9cc15)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9dbc7)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81b9e00e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b9e96e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81b9edc5)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81b9f69d)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff81ba0cf6)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81ba1042)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81ba13b9)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81ba172a)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81baaf65)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81bb4c54)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81c2150b)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fb68)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81c3fadd)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81c569f0)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:312
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca681f)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff81cbaf4e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cf70)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d377a8)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81d3cffc)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81d3d35d)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3e182)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81d40a77)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d433f6)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81dc7700)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddbe16)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
```
In drivers/platform/x86/intel/pmc/core_ssram.c (ffffffff81ddcb5d)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
```
```
In drivers/platform/x86/intel/pmc/tgl.c (ffffffff81ddcf01)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81ddfc35)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/mailbox/pcc.c (ffffffff81de214e)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea206)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81deee34)
Location: include/linux/device.h:312
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff811bea5f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff816a82dc)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff817d23bc)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193ad35)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193b988)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193ca15)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193efc1)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff819418f2)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819575ee)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81957d91)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8195895e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81958caf)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8195931e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81959620)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8195c495)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195c8d0)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
```
In drivers/pci/pcie/aer.c (ffffffff81988585)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/p2pdma.c (ffffffff819a8e02)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b63c3)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/video/aperture.c (ffffffff819bd04c)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00b75)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
```
```
In drivers/acpi/evged.c (ffffffff81a03649)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan_core.c (ffffffff81a63d17)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/intel_pmic.c (ffffffff81a7d109)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff81a7e994)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81a976ca)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a97b49)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a980f9)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c5d8)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f2e1)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/xen/grant-dma-ops.c (ffffffff81ad14de)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae1df5)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/reset/reset-simple.c (ffffffff81ae42ed)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff81b224d7)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81b22de6)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b23b7e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff81b28322)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2ad8a)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c765)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81b4f451)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b50bf5)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b8077e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbe6c5)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff81bcc66b)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81bdc7d0)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddeda)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81bde885)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81be10ce)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81be1268)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81be2e0c)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81be312a)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81be3539)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81be3618)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl-core.c (ffffffff81be3cd1)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81be57b1)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81be6398)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be885f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81be8f6f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81beaa29)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81beac3f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81beaf3c)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81beb383)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81beb80e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81bebd0f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81bec24b)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81bec836)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81becce7)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bee076)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81bee768)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81befd08)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81bf0c05)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1bb7)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81bf213e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81bf2ace)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81bf2f25)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81bf37fd)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff81bf4e56)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81bf51d2)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81bf5549)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81bf58ba)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bff2a5)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c091d4)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff81c766cb)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/gpu/drm/bridge/panel.c (ffffffff81cd0f2a)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/gpu/drm/bridge/panel.c:drmm_panel_bridge_add
  - drivers/gpu/drm/bridge/panel.c:devm_drm_panel_bridge_add_typed
  - drivers/gpu/drm/bridge/panel.c:drm_panel_bridge_add
```
```
In drivers/gpu/drm/tiny/simpledrm.c (0)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2a28)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff81cf50dd)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c (ffffffff81d0d190)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:311
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b46f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff81d6fcbe)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2cc2)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81deda28)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81df394c)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81df3cad)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df4ad2)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81df7427)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df9d7f)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81e80060)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e95be5)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/mailbox/pcc.c (ffffffff81e9812e)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea0476)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea53e7)
Location: include/linux/device.h:311
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffff8000101809c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffff8000105185f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffff8000105fe6a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/irqchip/irq-gic.c (ffff80001066cb9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init_child
```
```
In drivers/irqchip/irq-mbigen.c (ffff8000106763cc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676760)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678bfc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff800010679658)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_subset_probe
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a0d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a6c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b2a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/irqchip/qcom-irq-combiner.c (ffff8000114762c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d6b4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/irqchip/irq-ti-sci-intr.c (ffff80001067dfdc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
```
```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e614)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f6d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
```
```
In drivers/bus/brcmstb_gisb.c (ffff800011476898)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff800010680d14)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
```
```
In drivers/bus/fsl-mc/mc-io.c (ffff80001068173c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/mc-io.c:fsl_create_mc_io
```
```
In drivers/bus/fsl-mc/fsl-mc-allocator.c (ffff800010684658)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/phy/phy-xgene.c (ffff800010687fb0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_probe
```
```
In drivers/phy/broadcom/phy-brcm-sata.c (ffff80001068a430)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
```
```
In drivers/pinctrl/core.c (ffff80001068ca74)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffff80001068f3d4)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffff800010692630)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692acc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694de0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (ffff800010695ff8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffff800010697124)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699994)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069ca18)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069ef60)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069ff20)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a1ef8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3944)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a49c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a65a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
```
```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7c74)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/berlin/berlin-bg4ct.c (ffff8000106a7fcc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
```
```
In drivers/pinctrl/berlin/pinctrl-as370.c (ffff8000106a80d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a9448)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aaa9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-cp110.c (ffff8000106ab5b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-cp110.c:armada_cp110_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff8000114773e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ad020)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106af6f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b19dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b397c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b64dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b96c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba690)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bb1c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bcd08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106ccfcc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106cde0c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce71c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf26c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d03f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d1e6c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffff8000106d2f78)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3134)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffff8000106d4224)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffff8000106d57c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffff8000106d5b9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffff8000106d5e9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffff8000106d63d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d6540)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d6c1c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (ffff8000114784c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/probe.c (ffff8000106dd11c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/of.c (ffff8000106f9798)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/pcie/aer.c (ffff80001070461c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffff8000107068b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e23c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-iproc-msi.c (ffff80001072602c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727e94)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff800010729568)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072a48c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffff8000107306c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731588)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff8000114798d0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001147a49c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (ffff80001147a604)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff8000107343d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff800010735ac4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff800010736400)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736978)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-al.c (ffff8000107375c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_init
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_init
```
```
In drivers/pci/controller/dwc/pcie-hisi.c (ffff80001073815c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_init
```
```
In drivers/pci/controller/pci-thunder-pem.c (ffff800010738f28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_acpi_init
```
```
In drivers/pci/controller/pci-xgene.c (ffff800010739554)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c150)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760698)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/acpi/evged.c (ffff800010778ed0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
```
```
In drivers/acpi/fan.c (ffff8000107a1538)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffff8000107b1020)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffff8000107c75fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/clk-hsdk-pll.c (ffff8000107c81c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
```
```
In drivers/clk/actions/owl-s700.c (ffff8000107cb0e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/actions/owl-s700.c:s700_clk_probe
```
```
In drivers/clk/actions/owl-s900.c (ffff8000107cb1a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/actions/owl-s900.c:s900_clk_probe
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cd558)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_clock
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_pll_divider
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_debugfs_regset
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (ffff8000107d090c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:clk_register_hisi_phase
```
```
In drivers/clk/hisilicon/clk-hi6220-stub.c (ffff8000107d16a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
```
```
In drivers/clk/imx/clk-imx8qxp.c (ffff8000107e09e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
```
```
In drivers/clk/imx/clk-imx8qxp-lpcg.c (ffff8000107e1594)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe
```
```
In drivers/clk/meson/meson-aoclk.c (ffff8000107e5fb0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/meson/meson-aoclk.c:meson_aoclkc_probe
```
```
In drivers/clk/mvebu/armada-37xx-xtal.c (ffff8000107e884c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-tbg.c (ffff8000107e8a18)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e90f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/mvebu/cp110-system-controller.c (ffff8000107e9f5c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (ffff800011487774)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb644)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff800011488b08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
```
```
In drivers/clk/socfpga/clk-s10.c (ffff8000107f03f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f33dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
```
```
In drivers/clk/sunxi/clk-sun6i-apb0-gates.c (ffff8000107f4540)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
```
```
In drivers/clk/versatile/clk-vexpress-osc.c (ffff8000107fa2a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
```
```
In drivers/dma/amba-pl08x.c (ffff800010802bfc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff8000108046a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff800010807f1c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808f10)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148eeb0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/soc/actions/owl-sps.c (ffff80001080da58)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e0d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
```
```
In drivers/soc/bcm/raspberrypi-power.c (ffff80001080ef8c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
```
```
In drivers/soc/fsl/qbman/dpaa_sys.c (ffff800010817acc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
```
```
In drivers/soc/fsl/guts.c (ffff800010817c68)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/imx/soc-imx-scu.c (ffff800010818890)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff800010818c7c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
```
```
In drivers/soc/amlogic/meson-clk-measure.c (ffff8000108196b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (ffff80001081a3d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (ffff80001081a848)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b264)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
```
```
In drivers/soc/qcom/rpmhpd.c (ffff80001081db88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmhpd.c:rpmhpd_probe
```
```
In drivers/soc/rockchip/pm_domains.c (ffff80001081f3b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
```
```
In drivers/soc/xilinx/zynqmp_pm_domains.c (ffff800010820650)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
```
```
In drivers/virtio/virtio_mmio.c (ffff8000108268f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/of_regulator.c (ffff80001084b7f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
```
In drivers/reset/reset-berlin.c (ffff80001084d4a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
```
```
In drivers/reset/reset-imx7.c (ffff80001084d7e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-imx7.c:imx7_reset_probe
```
```
In drivers/reset/reset-meson.c (ffff80001084d908)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_probe
```
```
In drivers/reset/reset-qcom-aoss.c (ffff80001084dc70)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe
```
```
In drivers/reset/reset-simple.c (ffff80001084dd30)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/reset/reset-zynqmp.c (ffff80001084e150)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-zynqmp.c:zynqmp_reset_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffff80001088ce78)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088d278)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891744)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892ae0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894614)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
```
```
In drivers/tty/serial/max310x.c (ffff800010899538)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (ffff80001089bc00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e504)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a00ac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a4c20)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a676c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a77b4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c29b0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3a28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d20cc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/iommu/arm-smmu-impl.c (ffff8000108d32f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-impl.c:arm_smmu_impl_init
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d7294)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7d94)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108da7e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbea0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
```
In drivers/base/regmap/regmap.c (ffff80001091277c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffff80001091ec3c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffff80001092b78c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/misc/vexpress-syscfg.c (ffff80001092ba80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092d124)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/bcm2835-pm.c (ffff80001092d938)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e190)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/stmpe.c (ffff80001092f6cc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (ffff800010930c74)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (ffff8000109312f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/wm8400-core.c (ffff8000109372d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffff80001093940c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffff800010939580)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffff80001093aaf8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffff80001093ac9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffff80001093b2e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffff80001093b3b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffff80001093b9c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffff80001093cbd4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (ffff80001093e4c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/twl4030-audio.c (ffff80001093eac4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093f14c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffff800010940f94)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffff800010941c50)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffff8000109421e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffff8000109438b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffff800010943ac8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffff800010943e00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffff80001094415c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffff800010944578)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffff800010944a8c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffff800010944d5c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (ffff800010945994)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (ffff800010945d90)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (ffff8000109460f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffff800010946538)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffff800010947400)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffff800010947dc0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffff800010948b68)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffff8000109497ac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a0fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffff80001094ac88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffff80001094b85c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffff80001094bca0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c384)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffff80001094cc70)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffff80001094d560)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffff80001094e1cc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffff80001094e5dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/vexpress-sysreg.c (ffff80001094ee08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
```
In drivers/mfd/as3711.c (ffff80001094f164)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (ffff80001094f408)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/mfd/altera-sysmgr.c (ffff80001094f930)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
```
```
In drivers/nvdimm/region_devs.c (ffff800010957038)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffff800010961454)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ahci_imx.c (ffff8000109b7ff0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/ata/libahci.c (ffff8000109bbc7c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_start
```
```
In drivers/spi/spi-mem.c (ffff8000109ca698)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-lib.c (ffff8000109cb740)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffff8000109d8498)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/net/phy/mdio-mux.c (ffff8000109d88f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d8d84)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
```
```
In drivers/net/ethernet/freescale/fman/mac.c (ffff8000109f3a70)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
```
```
In drivers/usb/core/phy.c (ffff800010a34db4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a38da8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e420)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffff800010a4f9c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/rtc/rtc-mv.c (ffff80001149de28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aad064)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aade88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba704)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb6dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abcdec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/power/reset/as3722-poweroff.c (ffff800010ac94dc)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/reset/gpio-restart.c (ffff800010ac98e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffff800010ac9de4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/reset/syscon-reboot.c (ffff800010aca5b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc008)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffff800010acd8dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffff800010ad03e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/hwmon/hwmon.c (ffff800010ad19e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/armada_thermal.c (ffff800010addf98)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1a2c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
```
In drivers/edac/altera_edac.c (ffff800010b16538)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffff800010b3dd48)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/mmc/host/mmci.c (ffff800010b4546c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (ffff800010b48258)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
```
```
In drivers/leds/leds-syscon.c (ffff800010b4add4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e8c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
```
In drivers/firmware/qcom_scm.c (ffff800010b4f194)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
```
```
In drivers/firmware/ti_sci.c (ffff800010b510dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b563b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
```
```
In drivers/firmware/arm_scmi/clock.c (ffff800010b57910)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58900)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
```
```
In drivers/firmware/arm_scmi/power.c (ffff800010b58fac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
```
```
In drivers/firmware/arm_scmi/reset.c (ffff800010b5927c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (ffff800010b59930)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In drivers/firmware/imx/imx-dsp.c (ffff800010b61cf0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
```
```
In drivers/firmware/imx/imx-scu.c (ffff800010b62270)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
```
```
In drivers/firmware/imx/imx-scu-irq.c (ffff800010b628ec)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/firmware/imx/scu-pd.c (ffff800010b62c30)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffff800010b79028)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b350)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7bfe0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7c804)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (ffff800010b7d808)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
```
```
In drivers/devfreq/devfreq.c (ffff800010b85fb8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8aeb8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
```
```
In drivers/memory/mtk-smi.c (ffff800010b8bdc8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
```
In drivers/perf/arm-cci.c (ffff800010b90788)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In drivers/perf/arm-ccn.c (ffff800010b93730)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96f34)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b9778c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97fc0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98f30)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a37c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9b768)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_add
```
```
In drivers/nvmem/zynqmp_nvmem.c (ffff800010ba091c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_probe
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
In kernel/irq/devres.c (c03d07f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (c06d2af4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (c07aa26c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/irqchip/irq-gic.c (c0815e1c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_of_init_child
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081effc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fb2c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820308)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c08221e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c08231c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/brcmstb_gisb.c (c154e9e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/omap_l3_noc.c (c08262b4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
```
```
In drivers/bus/ti-sysc.c (c0828eb4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/bus/uniphier-system-bus.c (c08297c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
```
```
In drivers/phy/marvell/phy-armada375-usb2.c (c082bbfc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082bee4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe
```
```
In drivers/phy/samsung/phy-exynos-dp-video.c (c082c044)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-mipi-video.c (c082c190)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c8c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082ca40)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
```
```
In drivers/phy/ti/phy-gmii-sel.c (c082cf98)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
```
```
In drivers/pinctrl/core.c (c082eb48)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c0831248)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinctrl-as3722.c (c083405c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c0835428)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (c083651c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (c0837400)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083a8c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rza1.c (c083bbcc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083cbb4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083da80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c08400e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c0841828)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c0842e80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c0843fa0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844ac0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c0846300)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/berlin/berlin.c (c0847cac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/berlin/berlin-bg4ct.c (c08480c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
```
```
In drivers/pinctrl/berlin/pinctrl-as370.c (c08481b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c084947c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a8c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084def4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084f264)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c0851430)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852c28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
```
```
In drivers/pinctrl/samsung/pinctrl-exynos-arm.c (c0852d94)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853064)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (c0854e34)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
```
```
In drivers/pinctrl/sh-pfc/gpio.c (c085555c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/gpio.c:sh_pfc_register_gpiochip
```
```
In drivers/pinctrl/ti/pinctrl-ti-iodelay.c (c08567a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857b88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085a308)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b31c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085bdf0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
```
```
In drivers/gpio/gpio-mmio.c (c0868190)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c08688a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-htc-egpio.c (c15507a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869920)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (c086a408)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (c086bf88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-omap.c (c086d4b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (c086e7ec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-pl061.c (c086f1f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_probe
```
```
In drivers/gpio/gpio-rc5t583.c (c086f6e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c0870a54)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tegra.c (c087171c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (c0871fc8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (c08722a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-twl4030.c (c0872a90)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
```
```
In drivers/gpio/gpio-vf610.c (c08737ec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (c0873ec0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/gpio/gpio-zevio.c (c08741e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (c1550ef4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/probe.c (c0878c44)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/of.c (c0891d68)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/pcie/aer.c (c089bb3c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (c089d8fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a7420)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ab674)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08ade84)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b2fd4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b438c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b5b54)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (c08b97e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c15520a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb324)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (c1552810)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bd0c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08be0ec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08be8f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf150)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/video/fbdev/amba-clcd.c (c08df0f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/video/fbdev/mx3fb.c (c08e3100)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/amba/tegra-ahb.c (c08e609c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
```
```
In drivers/clk/clk-gpio.c (c08f2614)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/clk-aspeed.c (c08f3414)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
```
```
In drivers/clk/clk-ast2600.c (c08f3d44)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
```
```
In drivers/clk/clk-hsdk-pll.c (c08f4a84)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
```
```
In drivers/clk/hisilicon/clk-hisi-phase.c (c08f8294)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hisi-phase.c:clk_register_hisi_phase
```
```
In drivers/clk/hisilicon/clk-hi6220-stub.c (c08f9324)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (c157fba8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904c08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c1581974)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090cd38)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
```
```
In drivers/clk/tegra/clk-tegra124-dfll-fcpu.c (c091459c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe
```
```
In drivers/clk/tegra/clk-bpmp.c (c0915410)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
```
```
In drivers/clk/ti/clk-dra7-atl.c (c091aa8c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
```
```
In drivers/clk/ti/adpll.c (c091b7b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_init_clkout
  - drivers/clk/ti/adpll.c:ti_adpll_init_clkout
  - drivers/clk/ti/adpll.c:ti_adpll_clk_get_name
```
```
In drivers/clk/uniphier/clk-uniphier-core.c (c091bf60)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_probe
```
```
In drivers/clk/uniphier/clk-uniphier-cpugear.c (c091c37c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/uniphier/clk-uniphier-cpugear.c:uniphier_clk_register_cpugear
```
```
In drivers/clk/uniphier/clk-uniphier-fixed-factor.c (c091c444)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/uniphier/clk-uniphier-fixed-factor.c:uniphier_clk_register_fixed_factor
```
```
In drivers/clk/uniphier/clk-uniphier-fixed-rate.c (c091c524)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/uniphier/clk-uniphier-fixed-rate.c:uniphier_clk_register_fixed_rate
```
```
In drivers/clk/uniphier/clk-uniphier-gate.c (c091c714)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/uniphier/clk-uniphier-gate.c:uniphier_clk_register_gate
```
```
In drivers/clk/uniphier/clk-uniphier-mux.c (c091c908)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/uniphier/clk-uniphier-mux.c:uniphier_clk_register_mux
```
```
In drivers/clk/versatile/clk-vexpress-osc.c (c091d5a4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
```
```
In drivers/dma/amba-pl08x.c (c0921980)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor.c (c0925d74)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
```
```
In drivers/dma/mxs-dma.c (c158e89c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/dma/tegra20-apb-dma.c (c092a530)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/dma/ti/edma.c (c092eab0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
```
```
In drivers/dma/ti/omap-dma.c (c09313c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
```
In drivers/dma/ti/dma-crossbar.c (c09336b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
```
```
In drivers/soc/actions/owl-sps.c (c09339ec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
```
```
In drivers/soc/fsl/guts.c (c0933f60)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/imx/soc-imx-scu.c (c093555c)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935f30)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
```
```
In drivers/soc/amlogic/meson-clk-measure.c (c0936744)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (c0937104)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (c093755c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/qcom/spm.c (c0938088)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/qcom/spm.c:spm_dev_probe
```
```
In drivers/soc/rockchip/pm_domains.c (c09399b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939d28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe
```
```
In drivers/soc/tegra/powergate-bpmp.c (c093e5e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
```
```
In drivers/virtio/virtio_mmio.c (c0944af8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/of_regulator.c (c0954db4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
  - drivers/regulator/of_regulator.c:of_get_regulation_constraints
```
```
In drivers/regulator/fixed.c (c0955590)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
```
```
In drivers/regulator/ti-abb-regulator.c (c0955f28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
```
```
In drivers/reset/reset-berlin.c (c09598ac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
```
```
In drivers/reset/reset-imx7.c (c0959b6c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-imx7.c:imx7_reset_probe
```
```
In drivers/reset/reset-meson.c (c0959ca8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_probe
```
```
In drivers/reset/reset-qcom-aoss.c (c0959f14)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe
```
```
In drivers/reset/reset-simple.c (c095a0d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/reset/reset-simple.c:reset_simple_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (c098a3e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098dee8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/amba-pl011.c (c0990718)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
```
```
In drivers/tty/serial/max310x.c (c0993894)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (c0996eac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/meson_uart.c (c0999178)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (c0999e0c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/omap-serial.c (c099ff3c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1e44)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/tty/serial/owl-uart.c (c09a3174)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
```
In drivers/tty/serial/rda-uart.c (c09a4180)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a43f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (c09bb09c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c2680)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/iommu/omap-iommu.c (c09c3848)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
```
```
In drivers/iommu/rockchip-iommu.c (c09c5820)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
```
```
In drivers/iommu/tegra-smmu.c (c09c8b00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_device_group
```
```
In drivers/iommu/exynos-iommu.c (c09ca238)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
```
```
In drivers/iommu/qcom_iommu.c (c09cba40)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/base/regmap/regmap.c (c09f88c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (c0a03f3c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (c0a09fb8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/misc/vexpress-syscfg.c (c0a0a74c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
```
```
In drivers/mfd/88pm860x-core.c (c0a0bbb8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/sm501.c (c0a0d898)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_init_dev
```
```
In drivers/mfd/asic3.c (c1599194)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0a0fc10)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/stmpe.c (c0a10d3c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (c0a11f48)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (c0a14408)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/wm8400-core.c (c0a1f4e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (c0a21798)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (c0a218e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (c0a22ce8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65217.c (c0a2327c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/tps65910.c (c0a23610)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (c0a23c9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (c0a23d4c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (c0a24290)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (c0a2565c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (c0a26eb0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/twl4030-audio.c (c0a2827c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (c0a28868)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (c0a2a954)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (c0a2ac9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (c0a2b1ec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (c0a2ca5c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (c0a2cbb0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (c0a2cf4c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (c0a2d264)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (c0a2d76c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (c0a2dce4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (c0a2df6c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (c0a2ec08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (c0a2eff4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (c0a2f300)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (c0a2f77c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (c0a30738)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (c0a30fa4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0a31c00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (c0a3267c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (c0a331b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (c0a33918)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (c0a3422c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/omap-usb-host.c (c0a34afc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a35d34)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/mfd/tps65090.c (c0a35f28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (c0a36434)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (c0a36de0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (c0a373a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0a3822c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (c0a389fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/vexpress-sysreg.c (c0a38cac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
```
In drivers/mfd/as3711.c (c0a391c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (c0a39494)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/ata/libahci.c (c0a862d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_start
```
```
In drivers/ata/sata_highbank.c (c0a890a4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
```
```
In drivers/ata/ahci_imx.c (c0a8a9e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ahci_imx.c:imx_ahci_probe
```
```
In drivers/mtd/nand/raw/omap2.c (c0aaadc0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aad0a4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi-mem.c (c0ab3c9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-lib.c (c0ab49f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
```
```
In drivers/net/phy/phy_led_triggers.c (c0abfbd0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfc68)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/net/ethernet/ti/cpts.c (c0ad1410)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpts.c:cpts_create
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad5420)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
```
In drivers/net/ethernet/ti/davinci_cpdma.c (c0ad7eb8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_create
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
```
```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad9c04)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
```
```
In drivers/net/ethernet/ti/cpsw_sl.c (c0ada24c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_get
```
```
In drivers/usb/core/phy.c (c0b08570)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
```
```
In drivers/usb/phy/phy-generic.c (c0b0b9ac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c350)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
```
In drivers/usb/dwc2/platform.c (c0b11060)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (c0b21a70)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/usb/dwc2/pci.c (c0b21c20)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
```
```
In drivers/usb/musb/musb_core.c (c0b66080)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_queue_resume_work
```
```
In drivers/rtc/rtc-mv.c (c15a0464)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-omap.c (c0b8c6c4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d248)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_probe
```
```
In drivers/rtc/rtc-pl031.c (c0b8dacc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_probe
```
```
In drivers/rtc/rtc-s3c.c (c0b8ed74)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/rtc/rtc-twl.c (c0b8fba0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99cc0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bb08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c9a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e250)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba9270)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
```
```
In drivers/power/reset/as3722-poweroff.c (c0baa0d8)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/reset/gpio-restart.c (c0baa5c0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c0baaac4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/reset/syscon-reboot.c (c0bab3e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
```
```
In drivers/power/supply/power_supply_core.c (c0bacfc4)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (c0bae200)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (c0bb0be0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/hwmon/hwmon.c (c0bb2774)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe3a4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/thermal/armada_thermal.c (c0bbfb5c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/watchdog/npcm_wdt.c (c0bc26e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_probe
```
```
In drivers/watchdog/aspeed_wdt.c (c0bc2b20)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
```
```
In drivers/cpufreq/tegra20-cpufreq.c (c0c00b1c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c0c00dc4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
```
```
In drivers/cpufreq/ti-cpufreq.c (c0c01138)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
```
```
In drivers/mmc/core/slot-gpio.c (c0c182cc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/mmc/host/mmci.c (c0c1f344)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
```
```
In drivers/mmc/host/mmci_stm32_sdmmc.c (c0c217b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2afe4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2ee48)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
```
In drivers/mmc/host/cqhci.c (c0c2f7cc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_pltfm_init
```
```
In drivers/leds/leds-asic3.c (c0c33f98)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/leds/leds-asic3.c:asic3_led_probe
```
```
In drivers/leds/leds-syscon.c (c0c34084)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/firmware/qcom_scm.c (c0c359fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37b74)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
```
```
In drivers/firmware/arm_scmi/clock.c (c0c38d58)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39eb4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
```
```
In drivers/firmware/arm_scmi/power.c (c0c3a258)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
```
```
In drivers/firmware/arm_scmi/reset.c (c0c3a504)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
```
```
In drivers/firmware/arm_scmi/sensors.c (c0c3ab4c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
```
```
In drivers/firmware/imx/imx-dsp.c (c0c4044c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
```
```
In drivers/firmware/imx/imx-scu.c (c0c409f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
```
```
In drivers/firmware/imx/imx-scu-irq.c (c0c41028)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/firmware/imx/scu-pd.c (c0c41348)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/firmware/tegra/bpmp.c (c0c422e0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_request_mrq
```
```
In drivers/clocksource/em_sti.c (c0c46e40)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_probe
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47558)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
```
```
In drivers/platform/chrome/cros_ec_proto.c (c0c5e950)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c607f0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/tegra-hsp.c (c0c6141c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
```
```
In drivers/devfreq/devfreq.c (c0c69058)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/devfreq/exynos-bus.c (c0c6aeac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
```
In drivers/devfreq/event/exynos-nocp.c (c0c6b834)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c32c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/memory/of_memory.c (c0c6e670)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/of_memory.c:of_get_min_tck
```
```
In drivers/memory/omap-gpmc.c (c0c711b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/memory/mvebu-devbus.c (c0c724a4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
```
```
In drivers/memory/mtk-smi.c (c0c72e90)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
```
In drivers/memory/samsung/exynos-srom.c (c0c73358)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
```
In drivers/memory/tegra/mc.c (c0c73f48)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In drivers/memory/tegra/tegra20-emc.c (c0c74b14)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c758dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
```
```
In drivers/perf/arm-cci.c (c0c7aa08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:cci_pmu_probe
```
```
In drivers/perf/arm-ccn.c (c0c7c878)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In sound/soc/soc-core.c (c0ca4330)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_register_component
```
```
In sound/soc/soc-ac97.c (c0cbbc0c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/soc-ac97.c:snd_soc_new_ac97_component
```
```
In sound/soc/soc-compress.c (c0cbd62c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/soc-compress.c:snd_soc_new_compress
```
```
In sound/soc/codecs/sgtl5000.c (c0cbe764)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc0538)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
```
In sound/soc/fsl/imx-audmux.c (c0cc1de0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
```
```
In sound/soc/fsl/imx-pcm-dma.c (c0cc2864)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/fsl/imx-pcm-dma.c:imx_pcm_dma_init
```
```
In sound/soc/fsl/imx-sgtl5000.c (c0cc2a9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
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
In kernel/irq/devres.c (c0000000001db624)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (c0000000006616e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (c000000000798f70)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/core.c (c000000000825d24)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinmux.c (c00000000082a830)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinctrl-as3722.c (c00000000082ed24)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f318)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (c0000000008322e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000834fe8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c000000000837204)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c000000000838870)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (c000000000849470)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c000000000849868)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (c00000000084aac4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (c00000000084b060)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c00000000084cd84)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (c00000000084d258)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (c00000000084d614)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (c00000000084df9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (c0000000013a19fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/probe.c (c0000000008552ec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/of.c (c000000000876f38)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f610)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/soc/fsl/guts.c (c0000000008ca010)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d21c8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/of_regulator.c (c0000000008e9624)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000935730)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (c00000000093c040)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dce4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e238)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (c000000000965204)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
```
In drivers/char/tpm/tpm_i2c_atmel.c (c000000000965854)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_probe
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (c000000000968180)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
```
```
In drivers/base/regmap/regmap.c (c0000000009b4010)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (c0000000009c3d44)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (c0000000009caac8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cc66c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cdb64)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/stmpe.c (c0000000009cf3f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (c0000000009d0ddc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (c0000000009d18a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/wm8400-core.c (c0000000009dd798)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (c0000000009e0418)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (c0000000009e0618)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (c0000000009e219c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (c0000000009e2390)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (c0000000009e2bb4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (c0000000009e2cc4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (c0000000009e31f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (c0000000009e4898)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (c0000000009e696c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/twl4030-audio.c (c0000000009e713c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (c0000000009e81dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea2f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (c0000000009ea774)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (c0000000009eaefc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (c0000000009ecf90)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (c0000000009ed140)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (c0000000009ed64c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (c0000000009edacc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (c0000000009ee194)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (c0000000009ee814)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (c0000000009eeb94)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (c0000000009efcbc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (c0000000009f01b4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (c0000000009f062c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (c0000000009f0c2c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f210c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (c0000000009f2d1c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0000000009f3ee4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (c0000000009f4d48)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (c0000000009f5b90)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (c0000000009f65d0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (c0000000009f7440)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (c0000000009f79a4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (c0000000009f809c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (c0000000009f8ed8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (c0000000009f9a58)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0000000009fa9d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (c0000000009faed4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (c0000000009fba04)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (c0000000009fbdc4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/nvdimm/region_devs.c (c000000000a04e50)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (c000000000a14af8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/spi/spi-mem.c (c000000000a8bf8c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-lib.c (c000000000a8d52c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
```
```
In drivers/net/phy/phy_led_triggers.c (c000000000a9a710)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (c000000000af2770)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
```
```
In drivers/usb/dwc2/platform.c (c000000000afe338)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (c000000000b1798c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dc80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-opal.c (c000000000b9e90c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
```
```
In drivers/power/reset/as3722-poweroff.c (c000000000bab2a8)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/reset/gpio-restart.c (c000000000bab754)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c000000000babaf4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/reset/syscon-reboot.c (c000000000bac0f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
```
```
In drivers/power/supply/power_supply_core.c (c000000000baeaf8)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (c000000000bb0420)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (c000000000bb41d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/hwmon/hwmon.c (c000000000bb6678)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/mmc/core/slot-gpio.c (c000000000c3b504)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/leds/leds-syscon.c (c000000000c3fde0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/devfreq/devfreq.c (c000000000c64c60)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffe000118980)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffe000381a80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffe00043a5e6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/core.c (ffffffe000498cea)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinmux.c (ffffffe00049b1c4)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049db52)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049efb8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049fabe)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0b50)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2c46)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3b3a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ae1ba)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae95c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffe0004aef30)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffe0004af2b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffffffe0004b0638)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffe0004b096a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffe0004b0bda)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b2ffe)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
```
```
In drivers/pwm/pwm-stmpe.c (ffffffe00002b582)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/probe.c (ffffffe0004b54e8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/of.c (ffffffe0004c9aea)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
```
```
In drivers/pci/pcie/aer.c (ffffffe0004d2a54)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffe0004d44e2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e542a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffffffe0004ea5a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/clk/clk-gpio.c (ffffffe000514414)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/clk-hsdk-pll.c (ffffffe000514e38)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
```
```
In drivers/clk/sifive/fu540-prci.c (ffffffe0005156be)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d0fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/regulator/of_regulator.c (ffffffe00052b268)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffe00055669c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000556cb4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffe00055af6a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d1be)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/sifive.c (ffffffe00055db34)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e132)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe000573af4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
```
In drivers/base/regmap/regmap.c (ffffffe000594340)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffe00059dcb4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffe0005a30d2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a4234)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4f6e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/stmpe.c (ffffffe0005a6062)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a7190)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (ffffffe0005a7724)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffe0005ac3a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffe0005ae04e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffe0005ae1aa)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffe0005af4b2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffe0005af61e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffe0005afbae)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffe0005afc66)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffe0005b003c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffe0005b0ebe)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (ffffffe0005b242e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
```
```
In drivers/mfd/twl4030-audio.c (ffffffe0005b28fc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffe0005b2e3a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4a02)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffe0005b4e46)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffe0005b52a6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffe0005b656c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffe0005b66aa)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffe0005b69b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffe0005b6c88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffe0005b6fca)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffe0005b7484)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffe0005b768e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (ffffffe0005b7ef2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (ffffffe0005b81d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffe0005b8498)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffe0005b87de)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffe0005b95ee)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffe0005b9e7a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffe0005baa9a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffe0005bb48e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffe0005bbe6e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffe0005bc528)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bcf0a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffe0005bd2e6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd748)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffe0005bde9c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffe0005be69e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffe0005bf0b4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffe0005bf43c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffe0005bfac2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (ffffffe0005bfca2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c6134)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffe0005ced00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/spi/spi-mem.c (ffffffe00061a04e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-lib.c (ffffffe00061ae28)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffe000624128)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (ffffffe000652674)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a318)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffe00066c2f2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf176)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/reset/as3722-poweroff.c (ffffffe0006c761e)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/reset/gpio-restart.c (ffffffe0006c7992)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffffffe0006c7c24)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/reset/syscon-reboot.c (ffffffe0006c7fca)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c9880)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffe0006ca912)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006ccc6c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
```
```
In drivers/hwmon/hwmon.c (ffffffe0006ce2d6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/edac/sifive_edac.c (ffffffe00003945c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/edac/sifive_edac.c:sifive_edac_init
```
```
In drivers/mmc/core/slot-gpio.c (ffffffe000714d40)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/leds/leds-syscon.c (ffffffe00071de84)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/devfreq/devfreq.c (ffffffe00072f4ac)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff811148f6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8142b3f7)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff814f5a68)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155d01b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155e85e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a8df)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8156af59)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pci/probe.c (ffffffff8156ec15)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff815903fd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff81591c10)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a63db)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff8161b834)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bd55)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81623b6d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff8167711d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8167753e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8167b68a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d552)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167da45)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8169d0f5)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169ddc6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff816e4a25)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff816eedb5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff816fa790)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81701bfb)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81701db5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81703150)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81703f0c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff817042f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/syscon.c (ffffffff81704466)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a433)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8171428b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff8176f55f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff8177b508)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817837bd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bf019)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff817ced69)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81829a29)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81886da5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff8189231f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff8189ac6a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff81105606)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8141be77)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff814e5f78)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154d99e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f8d1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155afad)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8155b659)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pci/probe.c (ffffffff8155d375)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff8157f2dd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff81580db9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff8159557b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/acpi/acpi_apd.c (ffffffff815c62f9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/nfit/core.c (ffffffff815f93e9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:__acpi_nfit_notify
  - drivers/acpi/nfit/core.c:acpi_nfit_add
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_query_poison
  - drivers/acpi/nfit/core.c:acpi_nfit_register_region
  - drivers/acpi/nfit/core.c:acpi_nfit_blk_region_enable
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:acpi_nfit_init_interleave_set
  - drivers/acpi/nfit/core.c:__nfit_mem_init
```
```
In drivers/clk/clk-gpio.c (ffffffff8160fd64)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81610285)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81610869)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816181bd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816561fd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165661e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a77a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c642)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cb35)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff8167aae5)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b7b6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff816bf065)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff816c93f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff816ce5a0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816d5a0b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff816d5bc5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d6f50)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff816d7d0c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d7ee6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff816ddeb3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816e7d0b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pmem.c (ffffffff816eaedf)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/nvdimm/btt.c (ffffffff816ee8c6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt
```
```
In drivers/ata/ata_piix.c (ffffffff8174f3af)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff8175b2b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff817f10b9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff8185813a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff811127e6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff81427597)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff814f1af8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558d5b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559a00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155b6be)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155d5f1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568ccd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81569210)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81569664)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff815698b0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81569b3d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81569ee9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8156c0ca)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8156c1d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/probe.c (ffffffff8156e445)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff8159065d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff81592169)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a696b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/acpi/acpi_apd.c (ffffffff815dfbb9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/fan.c (ffffffff816271e7)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff816390bd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81649614)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649b35)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8164a119)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651b0d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816a54ed)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a590e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff816a9a6a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab932)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816abe25)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816cb365)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cc036)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff81711bb5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff8171c495)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81727bc0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81728607)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729cb2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8172f795)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817315d2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8173174b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81732b58)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81732cba)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8173312f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff817331d5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817336f4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8173487d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81735fd1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817364b8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81738570)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff817389f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81738e53)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8173a35c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8173a53a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8173a77c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff8173aa63)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8173adf9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8173b2fe)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8173b55f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8173ba7a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8173beea)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173ce35)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8173d6cd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8173e24d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff8173eab5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff8173f340)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8173fc50)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff817405e1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81740aae)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff817411de)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff817416f6)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81741a79)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817425e3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff817429b6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81742c88)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81742fdb)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff817432b1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81749203)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175305b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff8179f8bf)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff817ab8a8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817b3b6d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fbab9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff8180b809)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81855fd5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff81868231)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868b3b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186ad45)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81876969)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff8187891f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818d8245)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff818e5e1f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff818ea35a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In kernel/irq/devres.c (ffffffff8111de06)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
```
In fs/debugfs/file.c (ffffffff8143e457)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
```
```
In block/badblocks.c (ffffffff8150ac08)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572beb)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573890)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815756de)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81577511)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582bed)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81583130)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81583584)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff815837d0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81583a5d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81583e09)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81584399)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815865ca)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815866d4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/pci/probe.c (ffffffff81588925)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
```
```
In drivers/pci/pcie/aer.c (ffffffff815aab0d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_probe
```
```
In drivers/pci/pcie/dpc.c (ffffffff815ac5e9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/acpi/acpi_apd.c (ffffffff815f9a79)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:st_misc_setup
```
```
In drivers/acpi/fan.c (ffffffff81641097)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/pmic/tps68470_pmic.c (ffffffff8165340d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
```
```
In drivers/clk/clk-gpio.c (ffffffff81663ba4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/clk-gpio.c:clk_register_gpio
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816640c5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816646a9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166c19d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/tty/serial/8250/8250_fintek.c (ffffffff816bf94d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816bfd6e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
```
```
In drivers/tty/serial/max310x.c (ffffffff816c3eca)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c5d92)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c6285)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff816e5835)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e6506)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/base/regmap/regmap.c (ffffffff8172cd15)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
```
```
In drivers/base/pinctrl.c (ffffffff817377f5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/pinctrl.c:pinctrl_bind_pins
```
```
In drivers/misc/sram.c (ffffffff81743000)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743a47)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817450f2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff8174abd5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8174ca12)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8174cb8b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8174df98)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8174e0fa)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8174e56f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8174e615)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8174eb34)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl-core.c (ffffffff8174fcbd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81751411)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817518f8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753b00)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81753e35)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81754293)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8175579c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8175597a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81755bbc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/lp8788-irq.c (ffffffff81755ea3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81756239)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8175673e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8175699f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81756eba)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8175732a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81758275)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81758b0d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8175968d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/abx500-core.c (ffffffff81759ef5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/abx500-core.c:abx500_register_ops
```
```
In drivers/mfd/ab3100-core.c (ffffffff8175a780)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8175b090)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8175ba21)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8175beee)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c61e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8175cb36)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8175ceb9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8175da23)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8175ddf6)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8175e0d8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8175e42b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8175e701)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff81764683)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8176e4cb)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/ata/ata_piix.c (ffffffff817b973f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/ata_piix.c:piix_init_one
```
```
In drivers/spi/spi-mem.c (ffffffff817c5838)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/phy/phy_led_triggers.c (ffffffff817cdb3d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
```
In drivers/usb/core/phy.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/usb/dwc2/platform.c (ffffffff81815bc9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/debugfs.c (ffffffff81825919)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81871105)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884cd5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_hwmon.c (ffffffff81892309)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
```
In drivers/power/supply/charger-manager.c (ffffffff818942bf)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818f4d65)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81902a9f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
```
```
In drivers/devfreq/devfreq.c (ffffffff8190b3da)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
</details>
</li>
</ul>

## Differences
