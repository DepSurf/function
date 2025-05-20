# Function: <code>devm_kmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f8d0)
Location: drivers/base/devres.c:775
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/base/component.c:component_match_realloc
  - drivers/base/component.c:component_match_realloc
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/nvdimm/region.c:nd_region_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff8154f8d0-ffffffff8154f928: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a16a0)
Location: drivers/base/devres.c:775
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/8250/8250_pci.c:byt_serial_setup
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff815a16a0-ffffffff815a16f8: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cfd50)
Location: drivers/base/devres.c:776
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff815cfd50-ffffffff815cfda8: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e48b0)
Location: drivers/base/devres.c:776
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff815e48b0-ffffffff815e490b: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164bb80)
Location: drivers/base/devres.c:776
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/pcie-dpc.c:dpc_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/nvmem.c:rtc_nvmem_register
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff8164bb80-ffffffff8164bbdb: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687190)
Location: drivers/base/devres.c:780
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff81687190-ffffffff816871f3: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a6d50)
Location: drivers/base/devres.c:788
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - mm/hmm.c:hmm_devmem_add
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff816a6d50-ffffffff816a6db3: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816dfe20)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_slave_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/soundwire/mipi_disco.c:sdw_master_read_prop
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff816dfe20-ffffffff816dfe83: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704060)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff81704060-ffffffff817040c3: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be490)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_soc_data
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_msic.c:intel_msic_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:set_freq_table
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817be490-ffffffff817be4f6: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d31e0)
Location: drivers/base/devres.c:826
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_set_soc_data
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_pm_init
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/intel_msic.c:intel_msic_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:set_freq_table
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817d31e0-ffffffff817d325a: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b6bf0)
Location: drivers/base/devres.c:826
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817b6bf0-ffffffff817b6c67: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff818404e0)
Location: drivers/base/devres.c:815
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_get_fps
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff818404e0-ffffffff81840565: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff819835f0)
Location: drivers/base/devres.c:815
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819835f0-ffffffff81983693: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af1600)
Location: drivers/base/devres.c:820
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/doe.c:pcim_doe_create_mb
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81af1600-ffffffff81af16c7: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b3f770)
Location: drivers/base/devres.c:821
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff81b3f770-ffffffff81b3f85d: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b975f0)
Location: drivers/base/devres.c:821
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/video/aperture.c:devm_aperture_acquire_for_platform_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/pmic/intel_pmic.c:intel_pmic_install_opregion_handler
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/regulator/devres.c:devm_regulator_bulk_get_enable
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl
  - drivers/char/tpm/eventlog/acpi.c:tpm_read_log_acpi
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_bulk_alloc
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/gpu/drm/bridge/panel.c:drmm_panel_bridge_add
  - drivers/gpu/drm/bridge/panel.c:devm_drm_panel_bridge_add_typed
  - drivers/gpu/drm/bridge/panel.c:drm_panel_bridge_add
  - drivers/spi/spi.c:spi_get_gpio_descs
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/mt6323-poweroff.c:mt6323_pwrc_probe
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/nvmem/core.c:nvmem_populate_sysfs_cells
  - drivers/nvmem/core.c:nvmem_populate_sysfs_cells
```
**Symbols:**

```
ffffffff81b975f0-ffffffff81b976dd: devm_kmalloc (STB_GLOBAL)
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
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108efb20)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/irqchip/irq-gic.c:gic_of_init_child
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_subset_probe
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-ti-sci-intr.c:ti_sci_intr_irq_domain_probe
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_irq_domain_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
  - drivers/bus/fsl-mc/mc-io.c:fsl_create_mc_io
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_allocate_irqs
  - drivers/bus/fsl-mc/fsl-mc-allocator.c:fsl_mc_populate_irq_pool
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/phy/phy-xgene.c:xgene_phy_probe
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_functions
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_bits_in_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-cp110.c:armada_cp110_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xgene.c:xgene_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-iproc-msi.c:iproc_msi_init
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_init
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_init
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_init
  - drivers/pci/controller/pci-thunder-pem.c:thunder_pem_acpi_init
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/actions/owl-s700.c:s700_clk_probe
  - drivers/clk/actions/owl-s900.c:s900_clk_probe
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_clock
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_register_pll_divider
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_divider_debug_init
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_debug_init
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_debugfs_regset
  - drivers/clk/bcm/clk-bcm2835-aux.c:bcm2835_aux_clk_probe
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
  - drivers/clk/hisilicon/clk-hisi-phase.c:clk_register_hisi_phase
  - drivers/clk/hisilicon/reset.c:hisi_reset_init
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/imx/clk-imx8qxp.c:imx8qxp_clk_probe
  - drivers/clk/imx/clk-imx8qxp-lpcg.c:imx8qxp_lpcg_clk_probe
  - drivers/clk/meson/meson-aoclk.c:meson_aoclkc_probe
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init
  - drivers/clk/socfpga/clk-s10.c:s10_clkmgr_init
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/clk/sunxi/clk-sun6i-apb0-gates.c:sun6i_a31_apb0_gates_clk_probe
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
  - drivers/soc/fsl/qbman/bman_portal.c:bman_portal_probe
  - drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
  - drivers/soc/fsl/qbman/dpaa_sys.c:qbman_init_private_mem
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
  - drivers/soc/qcom/rpmhpd.c:rpmhpd_probe
  - drivers/soc/qcom/rpmhpd.c:rpmhpd_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
  - drivers/soc/xilinx/zynqmp_pm_domains.c:zynqmp_gpd_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
  - drivers/reset/reset-imx7.c:imx7_reset_probe
  - drivers/reset/reset-meson.c:meson_reset_probe
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/reset/reset-zynqmp.c:zynqmp_reset_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe
  - drivers/iommu/arm-smmu-impl.c:arm_smmu_impl_init
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/phy/mdio-mux.c:mdio_mux_init
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
  - drivers/firmware/ti_sci.c:devm_ti_sci_get_of_resource
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_probe
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
  - drivers/perf/xgene_pmu.c:xgene_pmu_dev_add
  - drivers/nvmem/zynqmp_nvmem.c:zynqmp_nvmem_probe
```
**Symbols:**

```
ffff8000108efb20-ffff8000108efbd0: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dd424)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - arch/arm/plat-omap/dma.c:omap_system_dma_probe
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/irqchip/irq-gic.c:gic_of_init_child
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/bus/ti-sysc.c:sysc_get_clocks
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_probe
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_probe
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_parse_dt
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_register
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza1.c:rza1_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/pinctrl-rza2.c:rza2_dt_node_to_map
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_parse_groups
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_parse_groups
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/berlin/berlin-bg4ct.c:berlin4ct_pinctrl_probe
  - drivers/pinctrl/berlin/pinctrl-as370.c:as370_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_parse_functions
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_regmap_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_simple_mmio_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-dove.c:dove_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-xp.c:armada_xp_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_create_functions
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_wkup_init
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_eint_gpio_init
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_register_pinctrl
  - drivers/pinctrl/sh-pfc/gpio.c:sh_pfc_register_gpiochip
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_setup
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_setup
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_dt_node_to_map
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_do_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_build_eint
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-pl061.c:pl061_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-vf610.c:vf610_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/gpio/gpio-zevio.c:zevio_gpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_regulators
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_get_resources
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_parse_port
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
  - drivers/video/fbdev/omap2/omapfb/vrfb.c:vrfb_probe
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-aspeed.c:aspeed_clk_probe
  - drivers/clk/clk-ast2600.c:aspeed_g6_clk_probe
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
  - drivers/clk/hisilicon/clk.c:hisi_clk_alloc
  - drivers/clk/hisilicon/clk-hisi-phase.c:clk_register_hisi_phase
  - drivers/clk/hisilicon/reset.c:hisi_reset_init
  - drivers/clk/hisilicon/clk-hi6220-stub.c:hi6220_stub_clk_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
  - drivers/clk/tegra/clk-tegra124-dfll-fcpu.c:tegra124_dfll_fcpu_probe
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/tegra/clk-bpmp.c:tegra_bpmp_init_clocks
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_probe
  - drivers/clk/ti/adpll.c:ti_adpll_init_clkout
  - drivers/clk/ti/adpll.c:ti_adpll_init_clkout
  - drivers/clk/ti/adpll.c:ti_adpll_clk_get_name
  - drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_probe
  - drivers/clk/uniphier/clk-uniphier-core.c:uniphier_clk_probe
  - drivers/clk/uniphier/clk-uniphier-cpugear.c:uniphier_clk_register_cpugear
  - drivers/clk/uniphier/clk-uniphier-fixed-factor.c:uniphier_clk_register_fixed_factor
  - drivers/clk/uniphier/clk-uniphier-fixed-rate.c:uniphier_clk_register_fixed_rate
  - drivers/clk/uniphier/clk-uniphier-gate.c:uniphier_clk_register_gate
  - drivers/clk/uniphier/clk-uniphier-mux.c:uniphier_clk_register_mux
  - drivers/clk/versatile/clk-vexpress-osc.c:vexpress_osc_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/amba-pl08x.c:pl08x_probe
  - drivers/dma/mv_xor.c:mv_xor_probe
  - drivers/dma/mv_xor.c:mv_xor_channel_add
  - drivers/dma/mxs-dma.c:mxs_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_setup_info_from_dt
  - drivers/dma/ti/edma.c:edma_xbar_event_map
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/actions/owl-sps.c:owl_sps_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
  - drivers/soc/qcom/spm.c:spm_dev_probe
  - drivers/soc/qcom/spm.c:qcom_cpuidle_init
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_domain_probe
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/rockchip/pm_domains.c:rockchip_pm_add_one_domain
  - drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe
  - drivers/soc/tegra/powergate-bpmp.c:tegra_bpmp_init_powergates
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
  - drivers/regulator/of_regulator.c:of_get_regulation_constraints
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/ti-abb-regulator.c:ti_abb_init_table
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe
  - drivers/reset/reset-berlin.c:berlin2_reset_probe
  - drivers/reset/reset-imx7.c:imx7_reset_probe
  - drivers/reset/reset-meson.c:meson_reset_probe
  - drivers/reset/reset-qcom-aoss.c:qcom_aoss_reset_probe
  - drivers/reset/reset-simple.c:reset_simple_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_of_xlate
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_probe
  - drivers/iommu/tegra-smmu.c:tegra_smmu_device_group
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/misc/vexpress-syscfg.c:vexpress_syscfg_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/sm501.c:sm501_init_dev
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65217.c:tps65217_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci.c:ahci_port_start
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/ata/sata_highbank.c:ahci_highbank_probe
  - drivers/ata/ahci_imx.c:imx_ahci_probe
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpts.c:cpts_create
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_chan_create
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
  - drivers/net/ethernet/ti/davinci_cpdma.c:cpdma_ctlr_create
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_get
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
  - drivers/usb/phy/phy-generic.c:usb_phy_gen_create_phy
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_queue_resume_work
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-pcf8523.c:pcf8523_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
  - drivers/rtc/rtc-twl.c:twl_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_probe
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
  - drivers/cpufreq/ti-cpufreq.c:ti_cpufreq_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/mmc/host/mmci.c:mmci_probe
  - drivers/mmc/host/mmci.c:mmci_dmae_setup
  - drivers/mmc/host/mmci_stm32_sdmmc.c:sdmmc_idma_setup
  - drivers/mmc/host/sdhci.c:sdhci_setup_host
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/mmc/host/cqhci.c:cqhci_init
  - drivers/mmc/host/cqhci.c:cqhci_pltfm_init
  - drivers/leds/leds-asic3.c:asic3_led_probe
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/firmware/qcom_scm.c:qcom_scm_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
  - drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup
  - drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
  - drivers/firmware/imx/imx-scu.c:imx_scu_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_request_mrq
  - drivers/clocksource/em_sti.c:em_sti_probe
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
  - drivers/extcon/extcon.c:extcon_dev_register
  - drivers/memory/of_memory.c:of_get_ddr_timings
  - drivers/memory/of_memory.c:of_get_min_tck
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/mvebu-devbus.c:mvebu_devbus_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/mc.c:tegra_mc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-cci.c:cci_pmu_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - drivers/perf/arm-ccn.c:arm_ccn_probe
  - sound/soc/soc-core.c:snd_soc_of_parse_audio_routing
  - sound/soc/soc-core.c:snd_soc_of_parse_audio_simple_widgets
  - sound/soc/soc-core.c:snd_soc_register_component
  - sound/soc/soc-dapm.c:snd_soc_dapm_new_dai
  - sound/soc/soc-ac97.c:snd_soc_new_ac97_component
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/soc-compress.c:snd_soc_new_compress
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
  - sound/soc/fsl/imx-audmux.c:imx_audmux_probe
  - sound/soc/fsl/imx-pcm-dma.c:imx_pcm_dma_init
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
  - sound/soc/fsl/imx-sgtl5000.c:imx_sgtl5000_probe
```
**Symbols:**

```
c09dd424-c09dd4a4: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000988fc0)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_probe
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
c000000000988fc0-c000000000989080: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe0005824b2)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/pinctrl/pinctrl-single.c:pinctrl_single_suspend
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/of.c:devm_of_pci_get_host_bridge_resources
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_init_phy
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
  - drivers/video/fbdev/simplefb.c:simplefb_probe
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_clk_probe
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/regulator/of_regulator.c:of_get_regulator_init_data
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/misc/sram.c:sram_reserve_regions
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl6030-irq.c:twl6030_init_irq
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77620.c:max77620_probe
  - drivers/mfd/max77686.c:max77686_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/spi/spi-fsl-lib.c:of_mpc8xxx_spi_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/core/phy.c:usb_phy_roothub_alloc
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
  - drivers/power/reset/syscon-reboot.c:syscon_reboot_probe
  - drivers/power/supply/power_supply_core.c:power_supply_get_battery_info
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/power/supply/charger-manager.c:of_cm_parse_desc
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/edac/sifive_edac.c:sifive_edac_init
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/leds/leds-syscon.c:syscon_led_probe
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffe0005824b2-ffffffe00058252c: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c97b0)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff816c97b0-ffffffff816c9813: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4ae0)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
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
  - drivers/acpi/nfit/core.c:__nfit_mem_init
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/btt.c:nvdimm_namespace_attach_btt
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff816a4ae0-ffffffff816a4b43: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7d20)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff816f7d20-ffffffff816f7d83: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devm_kmalloc(struct device *dev, size_t size, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817125c0)
Location: drivers/base/devres.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
  - fs/debugfs/file.c:debugfs_create_devm_seqfile
  - block/badblocks.c:devm_init_badblocks
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pci/probe.c:devm_pci_alloc_host_bridge
  - drivers/pci/pcie/aer.c:aer_probe
  - drivers/pci/pcie/dpc.c:dpc_probe
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/pmic/tps68470_pmic.c:tps68470_pmic_opregion_probe
  - drivers/clk/clk-gpio.c:clk_register_gpio
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_probe
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_f815xxa_setup
  - drivers/tty/serial/8250/8250_pci.c:pci_fintek_setup
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_init_noauto
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/base/devres.c:devm_kmemdup
  - drivers/base/devres.c:devm_kvasprintf
  - drivers/base/devres.c:devm_kstrdup
  - drivers/base/regmap/regmap.c:devm_regmap_field_alloc
  - drivers/base/pinctrl.c:pinctrl_bind_pins
  - drivers/misc/sram.c:sram_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl-core.c:twl_probe
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
  - drivers/mfd/twl6040.c:twl6040_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
  - drivers/mfd/da903x.c:da903x_probe
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
  - drivers/mfd/lp8788.c:lp8788_probe
  - drivers/mfd/lp8788-irq.c:lp8788_irq_init
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/abx500-core.c:abx500_register_ops
  - drivers/mfd/ab3100-core.c:ab3100_probe
  - drivers/mfd/adp5520.c:adp5520_probe
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/mfd/syscon.c:syscon_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/as3711.c:as3711_i2c_probe
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/region_devs.c:nd_region_activate
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_probe
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi-mem.c:spi_mem_probe
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/usb/dwc2/debugfs.c:dwc2_debugfs_init
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/rtc/sysfs.c:rtc_add_groups
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_alloc
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/devfreq/devfreq.c:devfreq_add_device
  - drivers/extcon/extcon.c:extcon_dev_register
```
**Symbols:**

```
ffffffff817125c0-ffffffff81712623: devm_kmalloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
