# Function: <code>dev_set_drvdata</code>

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
In arch/x86/events/intel/uncore.c (ffffffff8101616d)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff8117e4ab)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814229b6)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81423583)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429e9b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a699)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8142ac9c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-sx150x.c (ffffffff8142b677)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:901
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8142ba89)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8142bd64)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142c31a)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8142da3b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff8146b606)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81471d91)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81476552)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8147750d)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81477bf7)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814787eb)
Location: include/linux/device.h:901
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81478e1c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff814ab944)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5c93)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff814c09bc)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c28a3)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff814dd547)
Location: include/linux/device.h:901
Inline: True
```
```
In drivers/regulator/tps65217-regulator.c (ffffffff814df18d)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe
```
```
In drivers/tty/tty_io.c (ffffffff814e0485)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff814ff16b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff815058d5)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c8b3)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8150e092)
Location: include/linux/device.h:901
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150f67d)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151fe32)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520fc5)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81523516)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8152571c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff8152cb53)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
```
```
In drivers/base/core.c (ffffffff81548bf1)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff8154b6ab)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/cpu.c (ffffffff8154ed0b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81578a17)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/bmp085.c (ffffffff8157945e)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:bmp085_probe
```
```
In drivers/misc/sram.c (ffffffff81579ce1)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8157afa8)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157b924)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff8157d38a)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8158223c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff8158280d)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81583fc5)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff815840e3)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81584657)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8158551c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65217.c (ffffffff81585613)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81585a5e)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-core.c (ffffffff815860fc)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps65912-core.c:tps65912_device_init
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81586aba)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81586ceb)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff815871b6)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81589719)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81589d79)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158ba9c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8158bdd9)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8158c29a)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8158d4e9)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8158d67f)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/axp20x.c (ffffffff8158d89f)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/axp20x.c:axp20x_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8158dbf6)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8158e1d3)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8158e727)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8158e95f)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8158ee68)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8158f308)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81590245)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81590b22)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81591702)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81592a6a)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81593299)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81593b93)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81594044)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8159482e)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81594d4c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81595152)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81595cf1)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff815962c8)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81596457)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81596797)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/dimm.c (ffffffff815994ce)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
```
In drivers/nvdimm/region.c (ffffffff8159ac66)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
  - drivers/nvdimm/region.c:nd_region_probe
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815a172f)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815a230c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
```
In drivers/nvdimm/e820.c (ffffffff815a249b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff815bcc34)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff815c0bac)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
  - drivers/scsi/sr.c:sr_remove
```
```
In drivers/scsi/sg.c (ffffffff815c4697)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff815c8e67)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_release
  - drivers/ata/libata-core.c:ata_host_alloc
```
```
In drivers/spi/spi.c (ffffffff815e9463)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_alloc_master
```
```
In drivers/net/xen-netfront.c (ffffffff815fa6b1)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff8160848b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/hcd.c (ffffffff8160dcdf)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81613a7b)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81619aa5)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8161f99d)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
```
```
In drivers/usb/phy/phy-generic.c (ffffffff816216a7)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81626708)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/pci.c (ffffffff8162f8a0)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/dwc2/pci.c:dwc2_pci_remove
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8163d4b3)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81644362)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8166f625)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (ffffffff81672296)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81676cae)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/power/power_supply_core.c (ffffffff8167f404)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/power/charger-manager.c (ffffffff81681e81)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81682d43)
Location: include/linux/device.h:901
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81688a5c)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816eb22e)
Location: include/linux/device.h:901
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff816edbc2)
Location: include/linux/device.h:901
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff816ef1c0)
Location: include/linux/device.h:901
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
In arch/x86/events/intel/uncore.c (ffffffff81015826)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff8118ea11)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146b0d5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146c9c5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff814707d0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814755c9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81475bbc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-sx150x.c (ffffffff81476713)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81476a4f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81476db3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-zx.c (ffffffff814773b3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81478dc7)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/host/pcie-designware-plat.c (ffffffff814a5c95)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/pci/host/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff814b994e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814c0241)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814c4a92)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814c5a52)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814c613b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814c6ce6)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814c729e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff814fac26)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81505636)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81510fcc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81512e13)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8152ec1a)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81531d85)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8154ff31)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155eb4e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff815604e9)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81561b93)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572c8a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81573e20)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81576456)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff815788fa)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157c4e2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff8157ff76)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
```
```
In drivers/base/core.c (ffffffff8159a821)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff8159d39b)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/cpu.c (ffffffff815a0afb)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff815ce671)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff815ced6d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815cfff8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0988)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff815d244a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff815d831d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff815d88fd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff815da089)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff815da1a5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff815da7d7)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff815db605)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff815db78a)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff815dbc02)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff815dbca9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff815dc1e1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff815de763)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff815deb1c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e0d14)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff815e1035)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff815e14f1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff815e26fe)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff815e2885)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff815e2adc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff815e30b3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff815e35da)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff815e3819)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff815e3d22)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff815e4182)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff815e50c2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff815e591c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff815e64dc)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff815e78b9)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff815e80e4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff815e8a2c)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff815e8ef4)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff815e96ca)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff815e9bf2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff815e9fe2)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff815eaaec)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff815eb0d1)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff815eb257)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff815eb577)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/bus.c (ffffffff815ed58c)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff815eefae)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
```
In drivers/nvdimm/region_devs.c (ffffffff815f0762)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff815f0cb3)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff815f9482)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff81615924)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff816197ab)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8161cea8)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff816286c5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_host_release
```
```
In drivers/spi/spi.c (0)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8165a629)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff8166ba80)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8166d8de)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81673a56)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81679cc5)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8168071f)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81684d71)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8169e0d0)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816a4e33)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816d1161)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (ffffffff816d32bf)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff816d788e)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/power/power_supply_core.c (ffffffff816e0284)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/power/charger-manager.c (ffffffff816e2dcd)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff816e3a5d)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff816e992d)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8174fd37)
Location: include/linux/device.h:917
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81752ad2)
Location: include/linux/device.h:917
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81753ec7)
Location: include/linux/device.h:917
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
In arch/x86/events/intel/uncore.c (ffffffff810159e6)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff8119d371)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8148a3ed)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148b053)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148d107)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148ed72)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff814928b0)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497b99)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8149818c)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814983ef)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81498753)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8149a1d7)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff814db94e)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814e2231)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814e6a82)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814e7aba)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814e819b)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814e8e60)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814e9445)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/fan.c (ffffffff8151d8bb)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529826)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815385a7)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8153d7e2)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153ef43)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8155b339)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8155e475)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8157c491)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (0)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158b0ad)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8158cc58)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e303)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f302)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff815a0490)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff815a2ae6)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff815a508a)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8992)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff815acb06)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_create
```
```
In drivers/base/core.c (ffffffff815c8d81)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff815cc437)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/cpu.c (ffffffff815cf16b)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff815fb211)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff815fb9c8)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff815fcc05)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd597)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff815ff11a)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8160500d)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff816055ed)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81606d79)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81606e95)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff816074c7)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816082d5)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8160845a)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816088d2)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81608979)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81608eb1)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8160b3f0)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8160b7ac)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160d9b4)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8160dcd5)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8160e191)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8160f5ae)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8160f735)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8160f98c)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8160ff63)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8161048a)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816106c9)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81610bd2)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81611032)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81611f72)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816127cc)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8161337c)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816146c9)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81614ef4)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8161583c)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81615d04)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff816164da)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81616a02)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81616df2)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816178fc)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff81617ee1)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81618067)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81618387)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8161a39c)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff8161c123)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff8161d696)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff8161e073)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81627702)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff8164535c)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8164a43b)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8164dab5)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81659335)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_host_release
```
```
In drivers/spi/spi.c (0)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81688397)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff816997b7)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8169b5bb)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
```
In drivers/usb/core/driver.c (ffffffff816a16e6)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff816a79a5)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816ae44f)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff816b1319)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816cc212)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816d2f36)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816ff041)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700f73)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81703009)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817077be)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817106f4)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8171323d)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81714135)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff8171a78d)
Location: include/linux/device.h:1026
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8177e8c2)
Location: include/linux/device.h:1026
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81780467)
Location: include/linux/device.h:1026
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
In arch/x86/events/intel/uncore.c (ffffffff81013ec7)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff811a4051)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493c6d)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81494983)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81496ae8)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81498804)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8149c29d)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1849)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814a1df6)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814a2049)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814a2340)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff814a3e27)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff814d3c4e)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff814e7557)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814edf41)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814f26e3)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814f36c2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff814f3d98)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff814f49e2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff814f5050)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/acpi/fan.c (ffffffff8152e8f2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c2d5)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8154b857)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bdb8)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81551492)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81552cc3)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8156f538)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815746b3)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815906f8)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (0)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159f32d)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
```
```
In drivers/tty/serial/max310x.c (ffffffff815a0ccf)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a234f)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b3190)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff815b3538)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff815b664c)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff815b910a)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815be582)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff815c2791)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff815ddaa1)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff815e0ff2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/cpu.c (ffffffff815e3be8)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff8160efab)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff8160f560)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8161099c)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81611330)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff81612f8a)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff81618edd)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff81619485)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8161aba8)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8161ad30)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8161b3d7)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8161c185)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8161c30a)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8161c742)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8161c7e9)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8161cd1e)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8161f4fc)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8161f8bc)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81621ab2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81621dd5)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81622281)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8162366e)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816237f5)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81623a4c)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81624013)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8162452a)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81624779)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81624c82)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816250d2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81625fe2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81626868)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816273d8)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816286b9)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81628ee4)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816297a6)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81629c4f)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8162a411)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8162a93f)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8162acf2)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8162b814)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8162bd9e)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8162bf5f)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8162c262)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8162e49c)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81630163)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81631b21)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff816325df)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff8163c8cf)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff81658b38)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8165e03b)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff816623a5)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff8166db15)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_host_release
```
```
In drivers/spi/spi.c (0)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8169d72b)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff816aeaad)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff816b0939)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff816b67d7)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff816bcb55)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c3144)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff816c645d)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff816e0946)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7620)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817149c1)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817167c3)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817173bf)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_allocate_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8171d3b6)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726f39)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8172741d)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817289ad)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b43e)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8172c5c1)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff817328ea)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8175ebe7)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff8175fdcb)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8179d3ae)
Location: include/linux/device.h:1030
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8179eff0)
Location: include/linux/device.h:1030
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8101435a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff811b8cb1)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In mm/hmm.c (ffffffff8126e214)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - mm/hmm.c:hmm_device_new
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cff52)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0c39)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d2e08)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d4a81)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d6656)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff814da658)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e0219)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff814e07dc)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (0)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff814e0a3f)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff814e0d4c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff814e10dc)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff814e2b97)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pci/dwc/pcie-designware-plat.c (ffffffff815140de)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/pci/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff8151c057)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81522ac1)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81532da3)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81533d82)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81534478)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8153520e)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815358d0)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/acpi/button.c (ffffffff8158ee4a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff8158f5cd)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159ee06)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815aede7)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af348)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815b4ccd)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b6633)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff815d37da)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815d7833)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff815f53d8)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (0)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160482d)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
```
```
In drivers/tty/serial/max310x.c (ffffffff816063ff)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81608146)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (0)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81619dd0)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8161a188)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8161d35c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8161fc4a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624c3d)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81628f71)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff81644aa1)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff81648105)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/cpu.c (ffffffff8164adf8)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff8167782b)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff81677de0)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8167921c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679bd0)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff8167b7fa)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8168157d)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff81681b35)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81683288)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81683410)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81683ab7)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81684875)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816849fa)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81684e32)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81684ed9)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff81684f87)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8168555e)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81687d3c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816880fc)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168a2e2)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8168a605)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff8168aad1)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8168bf4e)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8168c0e5)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8168c33c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8168c903)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8168ce1a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8168d069)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8168d572)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8168d9c2)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8168e8d4)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8168f138)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8168fca8)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81690fc9)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816917fa)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816920c6)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8169256f)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81692d41)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8169327f)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81693632)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81694154)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff816946fe)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff816948bf)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81694c03)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81694f11)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81696c5c)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81698983)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff8169a481)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff8169af4f)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff816a555f)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff816c217c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff816c82eb)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff816cb61a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff816d7145)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_host_release
```
```
In drivers/spi/spi.c (0)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff8170860c)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff8171a094)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8171bf3f)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81722067)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81728525)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172ef14)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8173279a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8174d1e8)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753e5f)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81785be0)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817879c8)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817890c4)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8178e636)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81798589)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817989db)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8179a13d)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179cbe7)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8179dd8b)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff817a3a5a)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff817d0c47)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff817d1e4b)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818144ee)
Location: include/linux/device.h:1028
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8181614d)
Location: include/linux/device.h:1028
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff81014ea9)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff811d8414)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In mm/hmm.c (ffffffff812930bc)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - mm/hmm.c:hmm_device_new
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815010d3)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501b1e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81503e4b)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505b1e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8150b30e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f5b7)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8150fb7c)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8150ffcd)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81510236)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8151055c)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff815108cc)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815123d2)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81512936)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff815129f6)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bedd)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff81551d04)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff81558741)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815687f4)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81569aeb)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81569f26)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8156ae6b)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8156b35a)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff815c6216)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff815c6997)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6b1e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7537)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff815e77fe)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ecf92)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815eeaa3)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8160b679)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81610590)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8162e9af)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81635b9f)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163da92)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8163f028)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816417f5)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff816433a3)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81653a45)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81653e3c)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8165700e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81659a59)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165ef3d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816601b2)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81663c8e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff8167ff05)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff81683623)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/cpu.c (ffffffff8168640b)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff816b0256)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff816b3985)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816b4cfe)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b5693)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816b748a)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff816bd5d6)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff816bdb8c)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff816bf304)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816bf4ae)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff816bfb77)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816c08ff)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816c0a9c)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816c0ecf)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff816c0f86)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff816c1037)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff816c160e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816c3eee)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816c424d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c63f2)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff816c66f9)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816c6b89)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff816c8021)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816c81af)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816c83f9)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff816c89de)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816c8f17)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816c9160)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff816c966b)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816c9abb)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816caaa2)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816cb244)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816cbdb1)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816cd0f1)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816cd90f)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816ce20f)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff816ce67f)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff816cee94)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff816cf36c)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff816cf75a)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816d0294)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d074e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff816d098d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816d0ccf)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816d0fe0)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff816d2dbc)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff816d4bf0)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff816d674d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff816d731f)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff816e174d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff816fe7d9)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8170454b)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81708002)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81712be8)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81732503)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff81733d9d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817472c1)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff81758e4a)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8175ac8d)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81760daa)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81767375)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e4b0)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81771ead)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8178da10)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817944a8)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c6cdb)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8a7e)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817c9d1d)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817d0c30)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db267)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db806)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcc16)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-platdrv.c (ffffffff817dd930)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e15d7)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e40b2)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff817e56c7)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818199ca)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff8181ab3b)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8185e3b6)
Location: include/linux/device.h:1073
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81860024)
Location: include/linux/device.h:1073
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff81015949)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff811e8554)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In mm/hmm.c (ffffffff812a88bc)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - mm/hmm.c:hmm_device_new
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81515ba3)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815165ee)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8151888a)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8151a66e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81520168)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524c67)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff8152522c)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8152567d)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff815258e6)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81525c0c)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81525f7c)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81527b22)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81528166)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81528246)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815533a8)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81560f01)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff81569594)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815700d1)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81580253)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8158154b)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81581986)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815828fc)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff81582eda)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff815df7d6)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff815dff57)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f03c9)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601977)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81601c5e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81607b23)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816091a3)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff81627c3e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff8162d390)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8164cbef)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81653e4f)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165bd02)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8165d228)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165f975)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff816616ca)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81671c45)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8167203c)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8167510e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81675a09)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d3f9)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e808)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff8168227e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff8169ec45)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff816a331e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff816a60ab)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff816d121d)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff816d4c45)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff816d5f2e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d68f3)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816d86ca)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff816de826)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff816deecc)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff816e06d4)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816e087e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff816e0f47)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff816e1d3f)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff816e1edc)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff816e230f)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff816e23c6)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff816e2477)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff816e2a4e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff816e52de)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff816e563d)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e77f2)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff816e7af9)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff816e7fa9)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff816e94df)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff816e96af)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff816e98f9)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff816e9f3e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff816ea45c)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff816ea6e0)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff816eabeb)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff816eb03b)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff816ebf62)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff816ec7e4)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816ed361)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff816ee6b1)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff816eeecf)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff816ef82f)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff816efc9f)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff816f0444)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff816f098c)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff816f0d7a)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816f18b4)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff816f1d7e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff816f202d)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff816f2372)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff816f2683)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff816f44ec)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff816f6930)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff816f852c)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff816f91ef)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81704b6d)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/scsi/sd.c (ffffffff817213a2)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff817269bb)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81729112)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81735098)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81754ef3)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8175695a)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff8176b3d1)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff8177d3ba)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8177f1bd)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff8178536a)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff8178b905)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81792b30)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81796fe3)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817b409e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba9fd)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ee29a)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f011e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff817f13dd)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817f7f60)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8180213e)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802baf)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff81803478)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180ccf7)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f938)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81811166)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8184521b)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff8184632b)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff828ee724)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff828ee781)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8187ddd6)
Location: include/linux/device.h:1126
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8187f9a7)
Location: include/linux/device.h:1126
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff81016c4c)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff811ff800)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543d23)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8154480e)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81546896)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815487e5)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8154e29e)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81553327)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff8155393b)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81553d69)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81553fc7)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff815542b9)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff8155460e)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81554b32)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81556d8f)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81557400)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff815574d3)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81583248)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815911f3)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff81599e29)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a0568)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815b08bf)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815b1beb)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815b2007)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815b2fb7)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815b35e6)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff81611351)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff81611a77)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff816221ac)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816342e1)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816345f3)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163b922)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163d014)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8165c3a3)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81660fce)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8168170d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81688929)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8169125d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8169315a)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694f70)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff816970fb)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a77da)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816a7adc)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816aac42)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816ab68a)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b3e9f)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b572c)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff816b99ce)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff816d71e0)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff816dc150)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff816df0d7)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff8170ccad)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff817104eb)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81710ecc)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81712559)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-core.c (ffffffff817138fa)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8171800d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff8171864c)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81719e40)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81719fc6)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8171a497)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8171b3fc)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8171b57b)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8171b9b2)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8171ba6a)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8171bb17)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8171bfbb)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8171e8fc)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8171ed6c)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81720fbe)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff817212cc)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81721789)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81722c69)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81722e11)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8172305d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff817236ec)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81723bbb)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81723e3c)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8172432a)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8172478e)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817256fc)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81725f64)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81726ae4)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81727c2d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8172855e)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81728fe7)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff817293cf)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81729b04)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8172a04d)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8172a3da)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8172af37)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8172b342)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8172b5bf)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8172b8e9)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8172bbe1)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8172dadd)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff8173023e)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81731bf0)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81732c7f)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff8173e981)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff8174045f)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8175ca62)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff817620f8)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8176445d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81770a18)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff8179079b)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff81792f27)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817a9171)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff817bb955)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817bc373)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff817c3901)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817c9f29)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d105d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff817d619a)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817f36a0)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa32d)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182ed39)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830580)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81832c7e)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81838c35)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843967)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843f93)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff81844d14)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e933)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851645)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8185319f)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81887fc8)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff818890db)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff82909bcb)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff82909c2b)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bcd00)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818c838c)
Location: include/linux/device.h:1149
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818c9fab)
Location: include/linux/device.h:1149
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff810175fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff8120c960)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564c37)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815656ee)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81567696)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81569795)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8156f4b6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815749c3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81574f8b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff815753b9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81575617)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81575909)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81575c5e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff81576172)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815783af)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81578a30)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81578b03)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a4c28)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff815bb229)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815c13e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815d183f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815d2b6b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815d2f87)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815d3f3e)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815d4826)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff81632801)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff81632f27)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643c8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81656011)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81656323)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165ddf2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f4f4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8167e281)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff8168361e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816a3dbd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff816aafb9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3d4d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff816b5cfa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7b10)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff816b9c9b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816ca51a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816ca81c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816cd982)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816ce3ca)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d6b7f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d840c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff816dc7be)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff816fb2e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff8170018c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff81703327)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff8171403d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81730fad)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff817347db)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817351bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81736859)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-core.c (ffffffff81737bfa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8173c31d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff8173c95c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8173e130)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8173e2b6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8173e787)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8173f6cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8173f84b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8173fc82)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8173fd3a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8173fde7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81740292)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81742bcc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8174303c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81745119)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8174556c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81745a29)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81746f09)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817470b1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff817472fd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8174798c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81747e5b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817480dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff817485ca)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81748a3e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817499ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8174a224)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8174ada4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff8174bedd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8174c7ae)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8174d224)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8174d60f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8174dd44)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8174e24d)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8174e5da)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8174f137)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8174f592)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8174f80f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8174fb39)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8174fe31)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81751d79)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff817542ce)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81755d60)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff8175689f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81762b61)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff8176465f)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81780932)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff817860e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8178844d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81794a78)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff817b437b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817b6a77)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817ccbe1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/vfio.c (ffffffff817d175d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/usb/core/hub.c (ffffffff817ec163)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817ecb95)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff817f4281)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817faa49)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81801f2d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8180704f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818244c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b169)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81860669)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81861eb0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff818645b8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8186a5a5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818752e7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875903)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff81876673)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8187dd07)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81880363)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81883125)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81884c36)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188e759)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818b9f88)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff818bb08b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff829135d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff82913630)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818ef820)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f48bf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818fa81c)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818fc3fb)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8101918c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff812352e0)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81607057)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff816078cf)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608aeb)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160ae7f)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81613b03)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81618a09)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-msic.c (ffffffff816193a8)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81619900)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81619be9)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8161a04c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff8161a3de)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff8161a733)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8161ac42)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8161d34f)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8161da30)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8161db13)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8164da87)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff816650e9)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166b758)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8167b3d0)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8167c2d6)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167ccc9)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff8167ddfd)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8167e466)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffffffff816995d4)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff816dedb5)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff816dfeb8)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f15d5)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8170612d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81706403)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170cdd6)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e5c4)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8172f57a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81734969)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817563ad)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8175dc2d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81766c7d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8176931a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176bb90)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff8176e1bb)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177f3b7)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8177f4ac)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81782850)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81782d6a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178aeaf)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178cafc)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff817915ce)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff817b4520)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff817b9024)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff817bd4c7)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/base/cpu.c:__cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817cfb1d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff817ec2bd)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff817f1d9d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817f277c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3e09)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4cba)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff817f9c23)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_init
```
```
In drivers/mfd/wm831x-core.c (ffffffff817fa2fc)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817fbac0)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff817fbc46)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff817fbee5)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff817fd16c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff817fd2eb)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff817fd722)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff817fd7da)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff817fd887)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817fdd39)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff818006ac)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff818013fc)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81802ea8)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff8180324c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff818036a8)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81804c09)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81804d31)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81804ffd)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8180568c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81805bcb)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81805f4c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
```
```
In drivers/mfd/max77693.c (ffffffff818063da)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8180685e)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff818078ec)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81807f84)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81808d14)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81809f6a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8180a7fe)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8180b5cb)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8180b80f)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8180bf84)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/intel_msic.c (ffffffff8180c5b7)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_probe
```
```
In drivers/mfd/palmas.c (ffffffff8180c79d)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8180cc4c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8180d807)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8180dcc2)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8180df5f)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8180e289)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8180e581)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff818106d2)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81812ece)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81815496)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81815e8f)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81822906)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff818241cf)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff81846a32)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8184a968)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8184e3ef)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81858c78)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff8187a65b)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8187d887)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff81897c3d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/vfio.c (ffffffff8189ca48)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_release
```
```
In drivers/usb/core/hub.c (ffffffff818bb77a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818bc68a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff818c3de1)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff818cace9)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2a5d)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818d7bb9)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f6120)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fd009)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81932d2c)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819356e6)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81936961)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8193e1d8)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819498d7)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a2ce)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff8194c10a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194e84b)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81951b23)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81953bbb)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d2ed)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198a730)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff8198b85b)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff82d2614a)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init
```
```
In drivers/eisa/virtual_root.c (ffffffff82d261f1)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3a40)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ca9f3)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d109d)
Location: include/linux/device.h:698
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2fe0)
Location: include/linux/device.h:698
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8101995e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff8123dd90)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b937)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162c07d)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d210)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162f59e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81631710)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81638a58)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff8163f249)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-msic.c (ffffffff8163fbd8)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-msic.c:platform_msic_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff816400e0)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81640319)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff8164077c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81640ade)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81640d33)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff816412f1)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81643caf)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81644270)
Location: include/linux/device.h:666
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81644333)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81671c47)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8167ceab)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:666
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff81685d79)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8168c0a8)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8169b440)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8169c2b6)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8169ca59)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81c00020)
Location: include/linux/device.h:666
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8169d246)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffffffff816b66f4)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff816fcde5)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff816fde48)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e975)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817233cd)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81723733)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729bf6)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172b394)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8174c1be)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff817507a9)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8177161d)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81778aad)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81781bbd)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8178413c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81786770)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff81788b8b)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81c09a88)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff817973cc)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81c0a260)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8179a3ba)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a1cef)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a309c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff817bd7fe)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff817cab40)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff817cddad)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff817d2237)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/base/cpu.c:__cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817e40dd)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81800f78)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff818063cd)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81806d3c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81807a69)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/arizona-core.c (ffffffff8180880a)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8180c713)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
  - drivers/mfd/wm8400-core.c:wm8400_init
```
```
In drivers/mfd/wm831x-core.c (ffffffff8180cc7c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8180dbd0)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8180dd16)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8180df75)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8180ebac)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8180ed0b)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8180f052)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8180f0ea)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8180f187)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8180f5b9)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff818116ac)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8181234c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813d38)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff818143f8)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81815589)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81815691)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8181591d)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81815f3c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8181636c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8181676c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max77836_init
```
```
In drivers/mfd/max77693.c (ffffffff818169fa)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81816b5e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8181792c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81817f44)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81818be4)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff81819baa)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8181a12e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81c1500e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8181abdf)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8181b2c4)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/intel_msic.c (ffffffff8181b817)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/intel_msic.c:intel_msic_probe
```
```
In drivers/mfd/palmas.c (ffffffff8181b91d)
Location: include/linux/device.h:666
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8181bd5c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8181c587)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8181c9f2)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8181cc6f)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8181ce99)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8181d141)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8181f612)
Location: include/linux/device.h:666
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff818220fe)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81824686)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff8182501f)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81831616)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff818340bf)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff81858566)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8185ae18)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8185e99f)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81868ed8)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff8188921b)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8188bda7)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff818a5ffd)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/vfio.c (ffffffff818ab678)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_release
```
```
In drivers/usb/core/hub.c (ffffffff81c1c2a3)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818c93ea)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff818cfcd1)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff818d5dd9)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dce6f)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818e1dbc)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fecd0)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81905939)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff8192b565)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81939f7c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8193c756)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff8193cd51)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81944fd8)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f497)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fe5e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff81951b1a)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819542e7)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81957097)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff819589db)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81963c9d)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198e370)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff8198f44b)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff83014729)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init
```
```
In drivers/eisa/virtual_root.c (ffffffff830147d0)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3dc0)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f4c)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819d0d5d)
Location: include/linux/device.h:666
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819d2b9e)
Location: include/linux/device.h:666
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8101ac20)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff81240fd0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f607)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8160fc9c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81610e5d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8161323b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8161519a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-crystalcove.c (ffffffff81622c99)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff816236b0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff816238e9)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81623d4c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff816240a9)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff816242e3)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff81626a78)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81626fd0)
Location: include/linux/device.h:672
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81627093)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81654157)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8165fd2a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:672
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff81668b79)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166ed88)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8167e2c2)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81bf103d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff8167f82a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81bf1b1e)
Location: include/linux/device.h:672
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff8167ffc6)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffffffff816987a4)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff816dea51)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff816dfac6)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff816eff95)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817045d5)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff81704983)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81709b5d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170e4ad)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f124)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8172f9ce)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81734629)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817550cd)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8175c4dd)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8176541d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff81767a37)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176a0d0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff8176c37b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81bfb4fd)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8177a0ac)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81bfbce7)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8177ce9a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817849ef)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785dac)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff817a0a3e)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff817ae4b0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff817b17b2)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff817b5c97)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff817c851d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff817e5b48)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff817eb00d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff817eb96c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec63b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed36a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff817f0f9d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff817f144c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817f23b4)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff817f24fa)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff817f2755)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff817f33df)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff817f353b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff817f3882)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff817f391a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff817f39b7)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff817f3df8)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817f5ebb)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817f6a8c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f8448)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff817f8ad8)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff817f9c69)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817f9d6f)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff817f9fea)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff817fa5f0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff817fa98d)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817fabd1)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff817fae5a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff817fafbe)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817fbd9c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff817fc384)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff817fd004)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff817fd84e)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81c06c98)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff817fe31f)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff817fea22)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff817fed0d)
Location: include/linux/device.h:672
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff817ff0be)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817ff94c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff817ffdc2)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8180000e)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81800229)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff818004d1)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81802922)
Location: include/linux/device.h:672
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81805409)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff818078b0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff818083af)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81814846)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff818172af)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff8183b4e6)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8183de08)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8184111f)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff8184b908)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff8186b7ab)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8186e6f7)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff8188843c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
```
```
In drivers/net/xen-netfront.c (ffffffff818893bf)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897349)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c0e189)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818ac94a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff818b3301)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff818b9319)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c01df)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff818c50cb)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e2420)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e912b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff8190eaa5)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191d6b7)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8191fffa)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81920971)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819287c8)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933914)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933d15)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff8193599a)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819380db)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193afd3)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8193c441)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819480bd)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81972a00)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81973a5b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff8321f800)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff8321f860)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a86a0)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819aef5c)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff819b600c)
Location: include/linux/device.h:672
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff819b7e4b)
Location: include/linux/device.h:672
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8101d610)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff8127b9f0)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e5f8)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167ed2c)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8167ff8d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8168237b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684432)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81692e60)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81693099)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff816968a0)
Location: include/linux/device.h:689
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81696953)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff816c5f87)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff816d294a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:689
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff816dbe99)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff816e2f58)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff816f3262)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81ced76d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff816f482a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81cee544)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff8170e524)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff81756bf1)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff81757ce6)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176a085)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177fc06)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81780093)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8178551b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178ad3d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178ba54)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff817af7ca)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff817b4f89)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff817d87fd)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff817e0101)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e9b5d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec483)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817ee740)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff817f1acb)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81cfc177)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81800130)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81cfc971)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8180306a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180b4a2)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180cc3c)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81829a3e)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff818376d0)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff8183aa51)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff8183f197)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81852a1d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81871ee6)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/sram.c (ffffffff8187798b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff818784ec)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8187921b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff8187962d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff81879aec)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8187b004)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8187b14a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8187b3a5)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8187c32f)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8187c45b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8187c802)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8187c89a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8187ccba)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8187f14b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8187fd9c)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81881898)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81881f32)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81883119)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8188321f)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8188349a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81883ae0)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81883e7d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff818840c1)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8188434a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff818844ae)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8188534c)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81885939)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81886ae4)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff818875ee)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81d0a29d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff818881cf)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81888929)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81888cad)
Location: include/linux/device.h:689
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81888ebe)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff8188a1c2)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8188a3fe)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8188a619)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8188a8d1)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff8188ce62)
Location: include/linux/device.h:689
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff8188fa99)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff818921a0)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81892b7f)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff8189f006)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff818a18ff)
Location: include/linux/device.h:689
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff818c7c96)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff818ca8c8)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff818cddb8)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff818d8dcf)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff818fb454)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff818fe797)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81919890)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
```
```
In drivers/net/xen-netfront.c (ffffffff8191bf6f)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81930a0b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81d15263)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff8194199a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81948751)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff8194edf9)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8195692f)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff8195cd85)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e5a0)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819855db)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff819af8a5)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c0284)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff819c2c9a)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff819c36d1)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff819cb168)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6ce4)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7115)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff819d8ebd)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff819db834)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dc52b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff819df7c3)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff819e0cb5)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed05d)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81a1b701)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c75b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff83308faf)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff8330900f)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55890)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5d4f0)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81a64b4c)
Location: include/linux/device.h:689
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81a66d4b)
Location: include/linux/device.h:689
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8101fbd4)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff812cf74f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8179a1d0)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179a82c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179bdad)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179e458)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a0a33)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff817b2a54)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff817b39b0)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff817b3c19)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff817b77a0)
Location: include/linux/device.h:764
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff817b7873)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff817ebe62)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff817fbde0)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:764
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff81805bc4)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180d418)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8181fa53)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81eb4e1e)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81820ecd)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81eb5c5f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff8183cf04)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff81889d34)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan_core.c (ffffffff8188a99d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189ec07)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b637f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff818b6893)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bc0cd)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c26d0)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c3605)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff818eab82)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff818f0e85)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8191646f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8191edd3)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192953d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8192b02e)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192e7a3)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff81932207)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81ec49a6)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8193f517)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81ec51ac)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8194288a)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194b8e3)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194d2b0)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81969cae)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff81979792)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff8197cc08)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/base/cpu.c (ffffffff819823be)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff8199897a)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff819b9f84)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/sram.c (ffffffff819bfc6a)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff819c089d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c17bb)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_register_chip_i2c
```
```
In drivers/mfd/wm8400-core.c (ffffffff819c1c3c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff819c221c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff819c3844)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff819c399d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff819c3c84)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff819c4ccf)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff819c4e26)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff819c5202)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff819c52a9)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff819c75ed)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff819c839c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819ca0f2)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff819ca7c3)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff819cbb16)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff819cbcaf)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff819cbf1a)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff819cc63d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff819cca2d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff819ccd24)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff819ccfc1)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff819cd155)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff819ce0cd)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff819ce719)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff819cf9c4)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff819d05af)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81ed26f4)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff819d12bf)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff819d1a99)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff819d1e3c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff819d215e)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff819d34a2)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff819d373c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff819d394c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff819d3c3a)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff819d6382)
Location: include/linux/device.h:764
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff819d94d8)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff819dc43c)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff819dce2f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff819e8b06)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff819eb02d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff81a13dd0)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81a17dad)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81a1bf7b)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81a29f32)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81a4cee3)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff81a5007b)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81a6ea50)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81a710de)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81a8754f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
```
```
In drivers/usb/core/hub.c (ffffffff81edfe01)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81a9a387)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81aa1251)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81aa7eb9)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0519)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ab6be9)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad9cc1)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae1297)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff81b0e075)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20fd5)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81b230e8)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81b2415d)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81b2ce08)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b3983a)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39d99)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff81b3c436)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81b3f2e5)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b405b2)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b43ff3)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81b45969)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53949)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81b84611)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81b8581f)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff834c25bd)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff834c262b)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc5080)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcd620)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81bd5836)
Location: include/linux/device.h:764
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81bd81fa)
Location: include/linux/device.h:764
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff81024424)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff81337ea9)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b0851)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b10fc)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2689)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b5167)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b7bdc)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff818cc9d4)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff818cdadc)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff818cde19)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff818d1f24)
Location: include/linux/device.h:761
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff818d203d)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81912552)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff81929067)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:761
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff819345c4)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193bfa8)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8194f02f)
Location: include/linux/device.h:761
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819501db)
Location: include/linux/device.h:761
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81950909)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff81951f31)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff81972994)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff819d0730)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan_core.c (ffffffff819d1476)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e8935)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a030f3)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a0383f)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0ab23)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a12820)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13c55)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff81a41602)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81a48fc5)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81a71cdf)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81a7b18c)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a85f2d)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81a881b9)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81a89795)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8ca70)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff81a90ca8)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa0b7b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81aa0fe6)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81aa4a35)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81aa503a)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaf45c)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab1564)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81ad3cce)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff81ae6282)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff81ae9e18)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/base/cpu.c (ffffffff81af01fe)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b09afa)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f464)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/sram.c (ffffffff81b354fa)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b36bcd)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81b37550)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff81b37d0e)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81b39d5c)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81b39f09)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b3a864)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81b3bafb)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81b3be3b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81b3c1e2)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81b3c2e9)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b3e4ba)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b3efbc)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b41582)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b41cce)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81b43746)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81b43904)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81b43bfa)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81b44489)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b449a3)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81b44f1f)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81b454ca)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b4597b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b46d2d)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b47410)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b4890b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b497e6)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a7d8)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81b4abee)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b4b549)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81b4b993)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81b4c26e)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff81b4d91e)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81b4dc1b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81b4df1c)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81b4e329)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81b50ff2)
Location: include/linux/device.h:761
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81b545a8)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81b57a02)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81b5852f)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81b64fa2)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff81b67b8d)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff81b941ab)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81b98cc5)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81b9d147)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81bacb52)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81bd5153)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff81bd91ab)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c01a10)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81c04f6e)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c1cc4b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e907)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81c268d1)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81c2eea5)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c386a9)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81c3f5c1)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64e36)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6cb97)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff81c9e195)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb3275)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb597b)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81cb75ad)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81cc0f6f)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cceebf)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf719)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff81cd2386)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81cd56e5)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd6bd2)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cdac44)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81cdcb45)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec7ef)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81d23441)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d24aaf)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff83f02062)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff83f0210f)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6d500)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_remove
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81d7c183)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81d81e56)
Location: include/linux/device.h:761
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81d84bf7)
Location: include/linux/device.h:761
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff81024148)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff81368e69)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f3847)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f4180)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f56f9)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f8207)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fac55)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8190fa44)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff81910b3c)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81910e79)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81914f24)
Location: include/linux/device.h:887
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8191503d)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81955be2)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff8196d2a7)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:887
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff81978a84)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197ff88)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff819953f1)
Location: include/linux/device.h:887
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819966cb)
Location: include/linux/device.h:887
Inline: True
```
```
In drivers/video/fbdev/vesafb.c (ffffffff81996de9)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff819983f4)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/evged.c (ffffffff819b9064)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffffffff81a17d28)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan_core.c (ffffffff81a18a66)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a31286)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a4bf43)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c68f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a539aa)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5b855)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5ccb5)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff81a8b6dd)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81a93202)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81abc5a8)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81ac69fc)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad167d)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81ad38a9)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad4f66)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad7ab4)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff81adc4b8)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aec45a)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81aec8c6)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81af0355)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81af0971)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb319)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afd6f9)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81b2249e)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff81b34622)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff81b38198)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/base/cpu.c (ffffffff81b3e35e)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81b57b0a)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81b828b4)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/sram.c (ffffffff81b88998)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81b8a04d)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81b8a9c0)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff81b8b17e)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81b8d1bc)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81b8d369)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81b8dcc4)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81b8ef1b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81b8f25b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81b8f632)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81b8f709)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81b9194d)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81b9243c)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b948f2)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81b95048)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81b96ab6)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81b96ca4)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81b96faa)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81b97889)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81b97d53)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81b982cf)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81b9889a)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81b98d4b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81b9a0fd)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b9a7e0)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b9bd6b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81b9cc33)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9dc1b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81b9e02f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81b9e999)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81b9ede3)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81b9f6be)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff81ba0d8e)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81ba108b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81ba13dc)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81ba1789)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81ba4492)
Location: include/linux/device.h:887
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81ba7af8)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81baaf82)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81baba9f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81bb85a2)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff81bbad11)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff81bea6fb)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81bef265)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81bf373b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81c03d02)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81c2bfc3)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fbab)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/wwan/wwan_core.c (ffffffff81c66f53)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/net/wwan/wwan_core.c:wwan_remove_port
  - drivers/net/wwan/wwan_core.c:wwan_create_port
```
```
In drivers/net/xen-netfront.c (ffffffff81c6a67e)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff81c83b4f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c85807)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81c8d891)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81c96105)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9fa29)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81ca6b63)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccc266)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd41a7)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff81d054f5)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/serio/libps2.c (ffffffff81d0be0b)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_init
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d1a8a2)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1cfee)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81d1eb8d)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81d2892f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36fd6)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37805)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff81d39e06)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81d3d375)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3ed56)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42f04)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81d45014)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d5550f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81d8c641)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81d8dccf)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff83727ee6)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff83727f9f)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddbe34)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_clean_structure
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81dea343)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81df0216)
Location: include/linux/device.h:887
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81df31eb)
Location: include/linux/device.h:887
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff8102a278)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff813921ea)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193b077)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193b9a6)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193cd69)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193f237)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81941fd5)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
```
In drivers/gpio/gpio-mmio.c (ffffffff819578c3)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8195ce94)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8195cfad)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199f104)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffff819b629f)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff819c2ba3)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff819cc68e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_device_create
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff819dfa4d)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819e0d43)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/acpi/evged.c (ffffffff81a036a4)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/ac.c (ffffffff81a62713)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/acpi/ac.c:acpi_ac_probe
```
```
In drivers/acpi/button.c (ffffffff81a62f89)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan_core.c (ffffffff81a63d36)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7c6f6)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-lpss-atom.c (ffffffff81a97b93)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpss-atom.c:lpss_atom_clk_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a982df)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9f75a)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aaccf8)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaeac4)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff81addcd5)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81ae5c81)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81b0f337)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81b19a2c)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81b22f85)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b254dd)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff81b2842c)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2ada8)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f79b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f99a)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81b3fe06)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81b43895)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81b43ed1)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4e9a9)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b50d04)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81b7903e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff81b8c051)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff81b8fc38)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/base/dd.c:device_unbind_cleanup
```
```
In drivers/base/cpu.c (ffffffff81b95fed)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81bb0129)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd67a3)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/sram.c (ffffffff81bdc898)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81bddf4d)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/wm8400-core.c (ffffffff81bde8c0)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff81bdf07e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff81be10e2)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81be1295)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81be1be4)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
  - drivers/mfd/wm8350-core.c:wm8350_client_dev_register
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81be2e3b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81be317b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81be3552)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81be3629)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff81be58ed)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff81be63dc)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be88c2)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da903x.c (ffffffff81be9018)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81beaa86)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff81beac74)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81beaf7a)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff81beb859)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff81bebd23)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff81bec290)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81bec84a)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff81beccfb)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff81bee0ad)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81bee782)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81befd1c)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/adp5520.c (ffffffff81bf0c23)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1c0b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81bf215f)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81bf2af9)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff81bf2f43)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffff81bf381e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/syscon.c (ffffffff81bf4eee)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81bf521b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_crc.c (ffffffff81bf556c)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_crc.c:crystal_cove_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff81bf5919)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81bf86b2)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81bfbe58)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81bff2c2)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81bffddf)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81c0cbf2)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff81c0f51f)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffff81c3fd47)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81c44a04)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81c4905b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff81c594e2)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8b6d7)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_minor_unregister
```
```
In drivers/gpu/drm/drm_sysfs.c (ffffffff81cb3351)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_minor_alloc
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add
```
```
In drivers/gpu/drm/tiny/simpledrm.c (ffffffff81cd6d4d)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81cde8e3)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2a6b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff81d1f05e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff81d3852e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a4d4)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81d423c1)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81d4abe5)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d54679)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81d5b7b3)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d8116e)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d8918f)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/usb/roles/class.c (ffffffff81dbb0b5)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:usb_role_switch_set_drvdata
```
```
In drivers/input/serio/libps2.c (ffffffff81dc1a9b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_init
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dd06cf)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd2d3b)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81dd488d)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
```
In drivers/rtc/rtc-cmos.c (ffffffff81dde74f)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded1e6)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81deda85)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/ptp/ptp_clock.c (ffffffff81df030a)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/tps65086-restart.c (ffffffff81df3cc5)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/power/reset/tps65086-restart.c:tps65086_restart_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df56e4)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df98b0)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfba6a)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c411)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff81e43ef1)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81e455af)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff8395bea6)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff8395bf5f)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea05af)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81ea6805)
Location: include/linux/device.h:919
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff81ea9841)
Location: include/linux/device.h:919
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In kernel/events/core.c (ffff800010291a10)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/irqchip/irq-mbigen.c (ffff8000106764e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-mbigen.c:mbigen_device_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676790)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-mvebu-gicp.c (ffff800010678d60)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-gicp.c:mvebu_gicp_probe
```
```
In drivers/irqchip/irq-mvebu-icu.c (ffff80001067971c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-icu.c:mvebu_icu_probe
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a1b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_probe
```
```
In drivers/irqchip/irq-ls-scfg-msi.c (ffff80001067b014)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_remove
  - drivers/irqchip/irq-ls-scfg-msi.c:ls_scfg_msi_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (ffff80001067d88c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/hisi_lpc.c (ffff80001067f7e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_probe
```
```
In drivers/bus/brcmstb_gisb.c (ffff800011476a7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff800010680d20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/fsl-mc/fsl-mc-bus.c:fsl_mc_bus_probe
```
```
In drivers/bus/vexpress-config.c (ffff800010686030)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
```
```
In drivers/phy/phy-xgene.c (ffff800010688114)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/phy-xgene.c:xgene_phy_probe
  - drivers/phy/phy-xgene.c:xgene_phy_probe
```
```
In drivers/phy/broadcom/phy-bcm-ns2-pcie.c (ffff80001068a2b0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-bcm-ns2-pcie.c:ns2_pci_phy_probe
```
```
In drivers/phy/broadcom/phy-brcm-sata.c (ffff80001068a520)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
  - drivers/phy/broadcom/phy-brcm-sata.c:brcm_sata_phy_probe
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffff800010692680)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010692cb8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694e8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffff8000106971a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff800010699cb0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069cbc4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069ef78)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffff80001069ffb4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a21d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3950)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a49f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a65cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pinmux_probe
```
```
In drivers/pinctrl/berlin/berlin.c (ffff8000106a7c8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (ffff8000106a95c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (ffff8000106aaafc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-armada-37xx.c (ffff800011477988)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ad384)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afa84)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b39ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_core_probe
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b64e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b96cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba984)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bcd20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_paris_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffff8000106c567c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-mmio.c (ffff8000106cd160)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-davinci.c (ffff8000106ce278)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-davinci.c:davinci_gpio_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106ce9a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (ffff8000106cf280)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (ffff8000106d040c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2164)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffff8000106d3034)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d32d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffff8000106d42ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (ffff8000106d4f24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffff8000106d5930)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffff8000106d5c30)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffff8000106d5fa0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffff8000106d647c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d65f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffff8000106d6c28)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (ffff800011478568)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d9a0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d9a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e2ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721b38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffff8000107230b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pci-xgene-msi.c (ffff800010725888)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene-msi.c:xgene_msi_probe
```
```
In drivers/pci/controller/pcie-altera.c (ffff800010727398)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (ffff800010727fc8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff8000107295b8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072ad34)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffff800010730278)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffff800010730734)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731860)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800011479c1c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001147a564)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (ffff80001147a6a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff80001073456c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (ffff800010735c94)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-kirin.c (ffff80001073673c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (ffff800010736b90)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-al.c (ffff8000107376a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-hisi.c (ffff8000107381f4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-hisi.c:hisi_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffff800010741900)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffff80001074a2d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075b0f4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075c274)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075da1c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e5e8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (ffff800010760730)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (ffff800010761100)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/evged.c (ffff800010778f30)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/evged.c:ged_probe
```
```
In drivers/acpi/button.c (ffff8000107a0e40)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffff8000107a1550)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffff8000107aef50)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/clk-fixed-factor.c (ffff8000107c4f4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_probe
```
```
In drivers/clk/clk-fixed-rate.c (ffff8000107c53cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
```
```
In drivers/clk/clk-fixed-mmio.c (ffff8000107c7f94)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cd5e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clk_probe
```
```
In drivers/clk/mvebu/armada-37xx-xtal.c (ffff8000107e8854)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-xtal.c:armada_3700_xtal_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-tbg.c (ffff8000107e8a38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-tbg.c:armada_3700_tbg_clock_probe
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e9314)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/mvebu/cp110-system-controller.c (ffff8000107ea36c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/mvebu/cp110-system-controller.c:cp110_syscon_common_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb6d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (ffff800011488a38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
```
```
In drivers/clk/sunxi/clk-sun9i-mmc.c (ffff8000107f3600)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-mmc.c:sun9i_a80_mmc_config_clk_probe
```
```
In drivers/clk/sunxi/clk-sun6i-ar100.c (ffff8000107f4804)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun6i-ar100.c:sun6i_a31_ar100_clk_probe
```
```
In drivers/dma/amba-pl08x.c (ffff800010802a7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/bcm2835-dma.c (ffff800010804810)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mv_xor.c (ffff800010807fb8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808f78)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001148f390)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080e0e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/bcm/bcm2835-power.c:bcm2835_power_probe
```
```
In drivers/soc/bcm/raspberrypi-power.c (ffff80001080f14c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/bcm/raspberrypi-power.c:rpi_power_probe
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (ffff80001081a4a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (ffff80001081a8dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/qcom/rpmh-rsc.c (ffff80001081b548)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh-rsc.c:rpmh_rsc_probe
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826a38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108280a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffff800010847e78)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/reset/reset-meson.c (ffff80001084d948)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_probe
```
```
In drivers/reset/reset-zynqmp.c (ffff80001084e178)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/reset/reset-zynqmp.c:zynqmp_reset_probe
```
```
In drivers/tty/tty_io.c (ffff80001084f754)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffff80001087c0bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffff800010885828)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088f8cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891b5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892bfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/8250/8250_of.c (ffff800010893508)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010894708)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
```
```
In drivers/tty/serial/max310x.c (ffff800010899630)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (ffff80001089c07c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089e718)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (ffff8000108a00c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a1ee8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a4c4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/tty/serial/owl-uart.c (ffff8000108a681c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
```
In drivers/tty/serdev/core.c (ffff8000108a9ee4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/tpm/tpm-chip.c (ffff8000108b81e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1870)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3acc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffff8000108c88d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d25dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d759c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d7da8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108d9f5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/base/core.c (ffff8000108e58ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffff8000108eb4bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffff8000108eeb1c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffff800010905a64)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffff800010926b60)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffff80001092b8a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffff80001092d1a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/bcm2835-pm.c (ffff80001092d950)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/bcm2835-pm.c:bcm2835_pm_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e1f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (ffff80001092f974)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (ffff800010930cc4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (ffff800010931344)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/arizona-core.c (ffff800010932ce0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffff800010937324)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffff800010937b74)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffff800010939424)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffff8000109395a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffff800010939bac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffff80001093ab2c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffff80001093ace4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffff80001093b300)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffff80001093b3d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffff80001093b490)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffff80001093ba24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffff80001093ebb0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffff80001093f18c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffff800010940ff8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffff800010941c8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffff800010942260)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffff800010943904)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffff800010943b10)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffff800010943e3c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffff8000109445c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffff800010944aa4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffff800010944d8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (ffff8000109459ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (ffff800010945da8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (ffff800010946108)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffff800010946550)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffff80001094741c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffff800010947dcc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffff800010948bb0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffff80001094a14c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffff80001094aca0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffff80001094b938)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffff80001094bcd4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffff80001094c3ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffff80001094cc88)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffff80001094d588)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffff80001094e1d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffff80001094e65c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffff80001094f19c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (ffff80001094f434)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/mfd/altera-sysmgr.c (ffff80001094f9dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/altera-sysmgr.c:sysmgr_probe
```
```
In drivers/nvdimm/bus.c (ffff8000109524f8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffff800010954e48)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffff800010957050)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffff800010957d68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/dax/bus.c (ffff800010964034)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffff800010987080)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffff80001098cf04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffff8000109917e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffff80001099f284)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffff8000109c3fc0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffff8000109ca6cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-spi.c (ffff8000109cbbe4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd6c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/phy/mdio-mux-bcm-iproc.c (ffff8000109d8ea4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/phy/mdio-mux-bcm-iproc.c:mdio_mux_iproc_probe
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e42a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
```
```
In drivers/net/ethernet/broadcom/bgmac-platform.c (ffff8000109e4ff8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e981c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109ed6a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
```
```
In drivers/net/ethernet/freescale/fman/fman.c (ffff8000109f092c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman.c:fman_probe
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (ffff8000109f1d20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/fman_port.c:fman_port_probe
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc324)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_drv_probe
```
```
In drivers/net/xen-netfront.c (ffff800010a066e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffff800010a1a2a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffff800010a1bde8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffff800010a24d0c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffff800010a2cd2c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a372e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a38f18)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e84c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa2ab0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (ffff800010aa5c28)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/rtc/rtc-efi.c (ffff80001149dda4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-efi.c:efi_rtc_probe
```
```
In drivers/rtc/rtc-mv.c (ffff80001149df3c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-rtd119x.c (ffff800010aad07c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-rtd119x.c:rtd119x_rtc_probe
```
```
In drivers/rtc/rtc-sun6i.c (ffff800010aad2d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-sun6i.c:sun6i_rtc_probe
```
```
In drivers/rtc/rtc-xgene.c (ffff800010aadea0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba050)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba768)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abb7a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abce30)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/media/cec/cec-core.c (ffff800010abdf14)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffff800010ac7288)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/gpio-restart.c (ffff800010ac99dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffff800010ac9e24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/reset/vexpress-poweroff.c (ffff800010aca4d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_probe
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acbe68)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffff800010ad04dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffff800010ad18f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/armada_thermal.c (ffff800010ade040)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010ae0b50)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/watchdog/rtd119x_wdt.c (ffff800010ae1b28)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/rtd119x_wdt.c:rtd119x_wdt_probe
```
```
In drivers/edac/edac_mc_sysfs.c (ffff800010b122d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffff800010b1374c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/altera_edac.c (ffff800010b16564)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_edac_a10_probe
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_sdram_remove
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/mmc/core/block.c (ffff800010b4177c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/mmc/host/mmci.c (ffff800010b456b8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/leds/leds-syscon.c (ffff800010b4afd0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/firmware/raspberrypi.c (ffff800010b4e930)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/raspberrypi.c:rpi_firmware_probe
```
```
In drivers/firmware/ti_sci.c (ffff800010b51348)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b564c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/imx/imx-dsp.c (ffff800010b61e58)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64600)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65840)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/mailbox/rockchip-mailbox.c (ffff800010b7b3ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/bcm2835-mailbox.c (ffff800010b7c0dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mailbox/bcm2835-mailbox.c:bcm2835_mbox_probe
```
```
In drivers/mailbox/ti-msgmgr.c (ffff800010b7c9ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mailbox/ti-msgmgr.c:ti_msgmgr_probe
```
```
In drivers/mailbox/zynqmp-ipi-mailbox.c (ffff800010b7d8e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_probe
  - drivers/mailbox/zynqmp-ipi-mailbox.c:zynqmp_ipi_mbox_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80a34)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffff800010b871dc)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (ffff800010b89040)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/memory/brcmstb_dpfe.c (ffff800010b8aee8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/brcmstb_dpfe.c:brcmstb_dpfe_probe
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b578)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_remove
```
```
In drivers/memory/mtk-smi.c (ffff800010b8bee4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
```
In drivers/perf/arm-ccn.c (ffff800010b9375c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c (ffff800010b96f4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_hha_pmu.c (ffff800010b977a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
```
In drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c (ffff800010b97fd8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98f68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9ba14)
Location: include/linux/device.h:1391
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
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:imx_mmdc_probe
```
```
In kernel/events/core.c (c04c29bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f05c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fb4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/irqchip/irq-renesas-rza1.c (c0820314)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-rza1.c:rza1_irqc_probe
```
```
In drivers/irqchip/irq-uniphier-aidet.c (c0822258)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-uniphier-aidet.c:uniphier_aidet_probe
```
```
In drivers/irqchip/irq-imx-irqsteer.c (c08233a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/irqchip/irq-imx-irqsteer.c:imx_irqsteer_probe
```
```
In drivers/bus/brcmstb_gisb.c (c154ebd4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
```
In drivers/bus/omap_l3_smx.c (c0825bdc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/omap_l3_smx.c:omap3_l3_probe
```
```
In drivers/bus/omap_l3_noc.c (c0826334)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/omap_l3_noc.c:omap_l3_probe
```
```
In drivers/bus/ti-sysc.c (c0828ec8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/bus/uniphier-system-bus.c (c0829a34)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/uniphier-system-bus.c:uniphier_system_bus_probe
```
```
In drivers/bus/vexpress-config.c (c0829ee4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/bus/vexpress-config.c:vexpress_config_bridge_register
```
```
In drivers/phy/marvell/phy-armada375-usb2.c (c082bc6c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
  - drivers/phy/marvell/phy-armada375-usb2.c:armada375_usb_phy_probe
```
```
In drivers/phy/marvell/phy-mvebu-sata.c (c082bf64)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/marvell/phy-mvebu-sata.c:phy_mvebu_sata_probe
```
```
In drivers/phy/samsung/phy-exynos-dp-video.c (c082c0a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-dp-video.c:exynos_dp_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-mipi-video.c (c082c250)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_probe
  - drivers/phy/samsung/phy-exynos-mipi-video.c:exynos_mipi_video_phy_probe
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c94c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos_pcie_phy_probe
```
```
In drivers/phy/samsung/phy-exynos5250-sata.c (c082cad0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
  - drivers/phy/samsung/phy-exynos5250-sata.c:exynos_sata_phy_probe
```
```
In drivers/phy/ti/phy-gmii-sel.c (c082d128)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
  - drivers/phy/ti/phy-gmii-sel.c:phy_gmii_sel_probe
```
```
In drivers/pinctrl/pinctrl-as3722.c (c08340bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c0835658)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (c083746c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c083af40)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rza1.c (c083bc20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rza2.c (c083cbf0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza2.c:rza2_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-rzn1.c (c083de7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rzn1.c:rzn1_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c08402d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c0841840)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra.c (c08431c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (c0843fbc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c0844b5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c084661c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
```
```
In drivers/pinctrl/aspeed/pinctrl-aspeed.c (c084707c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pinctrl_probe
```
```
In drivers/pinctrl/berlin/berlin.c (c0847cd0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (c0849628)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (c084a930)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084df18)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084f5f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
```
```
In drivers/pinctrl/samsung/pinctrl-samsung.c (c0851aac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
```
```
In drivers/pinctrl/sh-pfc/core.c (c08533fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe
```
```
In drivers/pinctrl/ti/pinctrl-ti-iodelay.c (c0856b0c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_probe
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857e20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c085a314)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b648)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (c0863784)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-mmio.c (c0868340)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868b04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-htc-egpio.c (c15508e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
```
```
In drivers/gpio/gpio-mpc8xxx.c (c0869934)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
```
```
In drivers/gpio/gpio-mvebu.c (c086a414)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mvebu.c:mvebu_gpio_probe
```
```
In drivers/gpio/gpio-mxc.c (c086c2b8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/gpio/gpio-omap.c (c086d664)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (c086e8a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-pl061.c (c086f39c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_probe
```
```
In drivers/gpio/gpio-rc5t583.c (c086f780)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (c08702e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c0870bc0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tegra.c (c0871850)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (c0872068)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (c08723c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-twl4030.c (c0872d8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
```
```
In drivers/gpio/gpio-xilinx.c (c0873ecc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/gpio/gpio-zevio.c (c0874204)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-zevio.c:zevio_gpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (c1550f80)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a69d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a74f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a97a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac5a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08aef50)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (c08afd84)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b2698)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-altera-msi.c (c08b3124)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_probe
  - drivers/pci/controller/pcie-altera-msi.c:altera_msi_remove
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (c08b43cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b6200)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (c08b9470)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (c08b984c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c1552324)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bb608)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-layerscape-ep.c (c15528b0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape-ep.c:ls_pcie_ep_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bd23c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-armada8k.c (c08be2d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-armada8k.c:armada8k_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-histb.c (c08beb24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf230)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/video/backlight/backlight.c (c08c63ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (c08ccc74)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (c08ddf50)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/amba-clcd.c (c08df278)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (c08e0388)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/efifb.c (c08e13b4)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/fbdev/mx3fb.c (c08e3170)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/mx3fb.c:mx3fb_probe
```
```
In drivers/video/fbdev/simplefb.c (c08e38b8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/amba/tegra-ahb.c (c08e60f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/amba/tegra-ahb.c:tegra_ahb_probe
```
```
In drivers/clk/clk-fixed-factor.c (c08f071c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_probe
```
```
In drivers/clk/clk-fixed-rate.c (c08f0ae4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
```
```
In drivers/clk/clk-fixed-mmio.c (c08f2f04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904ca8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (c15818ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_probe
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c15854a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_clk_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090cd58)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_register
```
```
In drivers/clk/ti/adpll.c (c091b7d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/ti/adpll.c:ti_adpll_probe
```
```
In drivers/dma/amba-pl08x.c (c09217e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_probe
```
```
In drivers/dma/mv_xor.c (c0925e18)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (c158ed90)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:ipu_probe
```
```
In drivers/dma/tegra20-apb-dma.c (c092a558)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/dma/ti/edma.c (c092eb14)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/dma/ti/omap-dma.c (c0931790)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_probe
```
```
In drivers/dma/ti/dma-crossbar.c (c0933794)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dma/ti/dma-crossbar.c:ti_dma_xbar_probe
  - drivers/dma/ti/dma-crossbar.c:ti_dra7_xbar_probe
```
```
In drivers/soc/amlogic/meson-gx-pwrc-vpu.c (c09371d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-gx-pwrc-vpu.c:meson_gx_pwrc_vpu_probe
```
```
In drivers/soc/amlogic/meson-ee-pwrc.c (c0937624)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-ee-pwrc.c:meson_ee_pwrc_probe
```
```
In drivers/soc/samsung/exynos-pmu.c (c0939d7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/samsung/exynos-pmu.c:exynos_pmu_probe
```
```
In drivers/soc/tegra/fuse/fuse-tegra.c (c093a448)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/soc/tegra/fuse/fuse-tegra.c:tegra_fuse_probe
```
```
In drivers/soc/tegra/pmc.c (c093cf68)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (c0944c20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (c09460f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (c095176c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/regulator/fixed.c (c0955758)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/fixed.c:reg_fixed_voltage_probe
```
```
In drivers/regulator/ti-abb-regulator.c (c095629c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/ti-abb-regulator.c:ti_abb_probe
```
```
In drivers/regulator/tps65217-regulator.c (c0956d90)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/tps65217-regulator.c:tps65217_regulator_probe
```
```
In drivers/regulator/twl-regulator.c (c09575c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/twl-regulator.c:twlreg_probe
```
```
In drivers/regulator/twl6030-regulator.c (c09581c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/twl6030-regulator.c:twlreg_probe
```
```
In drivers/reset/reset-meson.c (c0959cec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/reset/reset-meson.c:meson_reset_probe
```
```
In drivers/tty/tty_io.c (c095b0d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/serial/8250/8250_pci.c (c098cab8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098e014)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c098e85c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/amba-pl011.c (c0990800)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_probe
  - drivers/tty/serial/amba-pl011.c:pl011_probe
```
```
In drivers/tty/serial/max310x.c (c0993970)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/imx.c (c09972dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
```
In drivers/tty/serial/meson_uart.c (c0999384)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
```
```
In drivers/tty/serial/sccnxp.c (c0999e24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/msm_serial.c (c099b4b8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
```
```
In drivers/tty/serial/omap-serial.c (c09a0160)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1e78)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
```
```
In drivers/tty/serial/owl-uart.c (c09a321c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
```
In drivers/tty/serial/rda-uart.c (c09a4224)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
```
```
In drivers/tty/serdev/core.c (c09a63ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/tpm/tpm-chip.c (c09b1a68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (c09ba600)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/iommu/iommu-sysfs.c (c09bf84c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c27e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
```
```
In drivers/iommu/omap-iommu.c (c09c39cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
```
```
In drivers/iommu/rockchip-iommu.c (c09c583c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/iommu/exynos-iommu.c (c09ca420)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
```
```
In drivers/iommu/qcom_iommu.c (c09cb488)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_remove
  - drivers/iommu/qcom_iommu.c:qcom_iommu_ctx_probe
```
```
In drivers/base/core.c (c09d4060)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (c09d95b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (c09dc52c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (c09ef260)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/misc/sram.c (c0a0a0ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (c0a0bc24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/sm501.c (c0a0de8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_pci_probe
  - drivers/mfd/sm501.c:sm501_plat_probe
```
```
In drivers/mfd/asic3.c (c15991c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0a0fc7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (c0a11014)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (c0a11f9c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/t7l66xb.c (c0a126c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
```
```
In drivers/mfd/tc6387xb.c (c0a12d24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tc6387xb.c:tc6387xb_probe
```
```
In drivers/mfd/tc6393xb.c (c0a13918)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
```
```
In drivers/mfd/lochnagar-i2c.c (c0a1444c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/arizona-core.c (c0a15c04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (c0a1f518)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (c0a1ffd8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (c0a217b0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (c0a2191c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (c0a21e44)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (c0a22d28)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65217.c (c0a23290)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65217.c:tps65217_probe
```
```
In drivers/mfd/tps65910.c (c0a23658)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (c0a23cb8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (c0a23d64)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (c0a242ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (c0a28370)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (c0a288a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (c0a2a9bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (c0a2accc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (c0a2b278)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (c0a2caa4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (c0a2cbe0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (c0a2cf98)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (c0a2d7c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (c0a2dd04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (c0a2dfa0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (c0a2ec14)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (c0a2f000)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (c0a2f30c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (c0a2f788)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (c0a3076c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (c0a30fb0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0a31c4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (c0a3320c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (c0a33930)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (c0a3431c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/omap-usb-host.c (c0a34ca8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a35d5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/mfd/tps65090.c (c0a35f58)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (c0a36468)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (c0a36df8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (c0a373d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0a38238)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (c0a38a90)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (c0a391f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (c0a394b8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/dax/bus.c (c0a3b284)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/scsi/sd.c (c0a59380)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (c0a5e798)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c0a61c20)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (c0a6f954)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/mtd/mtdcore.c (c0a90994)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mtd/mtdcore.c:add_mtd_device
```
```
In drivers/mtd/nand/raw/omap2.c (c0aab014)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_nand_probe
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aad198)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi.c (c0ab16c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (c0ab3cfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-spi.c (c0ab5338)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7b64)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acaae8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf72c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_probe
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfd80)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad543c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
```
In drivers/auxdisplay/arm-charlcd.c (c159d238)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
```
```
In drivers/usb/core/hub.c (c0af24fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (c0af4dbc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (c0afb364)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (c0b01b00)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (c0b09a88)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/phy/phy-generic.c (c0b0ba68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/phy/phy-generic.c:usb_phy_generic_probe
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0c4e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_probe
```
```
In drivers/usb/dwc2/platform.c (c0b114d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/dwc2/pci.c (c0b21c4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_remove
```
```
In drivers/usb/host/ehci-exynos.c (c0b30658)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ehci-exynos.c:exynos_ehci_probe
```
```
In drivers/usb/host/ohci-exynos.c (c0b3869c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ohci-exynos.c:exynos_ohci_probe
```
```
In drivers/usb/musb/musb_core.c (c0b66138)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_init_controller
```
```
In drivers/input/keyboard/atkbd.c (c0b829a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (c0b84980)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/rtc/rtc-efi.c (c15a03f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-efi.c:efi_rtc_probe
```
```
In drivers/rtc/rtc-mv.c (c15a0574)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
```
```
In drivers/rtc/rtc-omap.c (c0b8c7a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/rtc/rtc-pcf8523.c (c0b8d330)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-pcf8523.c:pcf8523_probe
```
```
In drivers/rtc/rtc-pl031.c (c0b8db2c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-pl031.c:pl031_probe
```
```
In drivers/rtc/rtc-s3c.c (c0b8edc8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-s3c.c:s3c_rtc_probe
```
```
In drivers/rtc/rtc-twl.c (c0b8fd00)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-twl.c:twl_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99764)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99d14)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bbe8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9ca6c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e4d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
```
```
In drivers/media/cec/cec-core.c (c0b9fba8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (c0ba6cfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/avs/smartreflex.c (c0ba9298)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
```
```
In drivers/power/reset/gpio-restart.c (c0baa6bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c0baaaf4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/reset/vexpress-poweroff.c (c0bab284)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/vexpress-poweroff.c:vexpress_reset_probe
```
```
In drivers/power/supply/power_supply_core.c (c0bacdf4)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c0bb0d0c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (c0bb267c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbe3b0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
```
In drivers/thermal/armada_thermal.c (c0bbfc04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
```
In drivers/watchdog/watchdog_dev.c (c0bc0ddc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/watchdog/aspeed_wdt.c (c0bc2d48)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/aspeed_wdt.c:aspeed_wdt_probe
```
```
In drivers/edac/edac_mc_sysfs.c (c0bf0508)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (c0bf16e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/armada_xp_edac.c (c0bf21c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/armada_xp_edac.c:aurora_l2_remove
  - drivers/edac/armada_xp_edac.c:aurora_l2_probe
  - drivers/edac/armada_xp_edac.c:axp_mc_remove
  - drivers/edac/armada_xp_edac.c:axp_mc_probe
```
```
In drivers/opp/ti-opp-supply.c (c0bf7bf0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/opp/ti-opp-supply.c:ti_opp_supply_probe
```
```
In drivers/cpufreq/tegra20-cpufreq.c (c0c00c38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/cpufreq/tegra20-cpufreq.c:tegra20_cpufreq_probe
```
```
In drivers/cpufreq/tegra124-cpufreq.c (c0c00f78)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/cpufreq/tegra124-cpufreq.c:tegra124_cpufreq_probe
```
```
In drivers/mmc/core/block.c (c0c1c584)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/mmc/host/mmci.c (c0c1f578)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2b190)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/mmc/host/sdhci-pltfm.c (c0c2cf04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-pltfm.c:sdhci_pltfm_init
```
```
In drivers/leds/leds-syscon.c (c0c3429c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37c7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_probe
```
```
In drivers/firmware/imx/imx-dsp.c (c0c405d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-dsp.c:imx_dsp_probe
```
```
In drivers/firmware/tegra/bpmp.c (c0c424c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
```
```
In drivers/clocksource/sh_cmt.c (c0c45084)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_mtu2.c (c0c456c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_setup
```
```
In drivers/clocksource/sh_tmu.c (c0c467d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
```
In drivers/clocksource/em_sti.c (c0c46e68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_probe
```
```
In drivers/staging/emxx_udc/emxx_udc.c (c0c5bd34)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
```
```
In drivers/mailbox/rockchip-mailbox.c (c0c6084c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mailbox/rockchip-mailbox.c:rockchip_mbox_probe
```
```
In drivers/mailbox/tegra-hsp.c (c0c616b0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_probe
```
```
In drivers/remoteproc/remoteproc_core.c (c0c6403c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (c0c6a0e0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/devfreq/exynos-bus.c (c0c6aeec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/devfreq/exynos-bus.c:exynos_bus_probe
```
```
In drivers/devfreq/event/exynos-nocp.c (c0c6b920)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-nocp.c:exynos_nocp_probe
```
```
In drivers/devfreq/event/exynos-ppmu.c (c0c6c5a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/devfreq/event/exynos-ppmu.c:exynos_ppmu_probe
```
```
In drivers/extcon/extcon.c (c0c6dc68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
```
In drivers/memory/omap-gpmc.c (c0c711e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/memory/mtk-smi.c (c0c72fb4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
```
In drivers/memory/samsung/exynos-srom.c (c0c73394)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/samsung/exynos-srom.c:exynos_srom_probe
```
```
In drivers/memory/tegra/mc.c (c0c73f54)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/tegra/mc.c:tegra_mc_probe
```
```
In drivers/memory/tegra/tegra124-emc.c (c0c75ba4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/memory/tegra/tegra124-emc.c:tegra_emc_probe
```
```
In drivers/perf/arm-ccn.c (c0c7c8a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_probe
```
```
In sound/soc/soc-core.c (c0ca3e3c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_register_card
  - sound/soc/soc-core.c:snd_soc_instantiate_card
```
```
In sound/soc/codecs/sgtl5000.c (c0cbe770)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - sound/soc/codecs/sgtl5000.c:sgtl5000_i2c_probe
```
```
In sound/soc/fsl/fsl_ssi.c (c0cc07a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe
```
```
In sound/soc/fsl/imx-sgtl5000.c (c0cc2c58)
Location: include/linux/device.h:1391
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
In arch/powerpc/sysdev/fsl_lbc.c (c0000000000b88d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
```
```
In arch/powerpc/platforms/powernv/vas.c (c0000000000e14cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/vas.c:vas_probe
```
```
In kernel/events/core.c (c000000000346220)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-as3722.c (c00000000082ed9c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082f578)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (c00000000083236c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (c00000000083520c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c00000000083722c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (c000000000838920)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (c0000000008422f4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-mmio.c (c00000000084964c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (c000000000849b38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (c00000000084ab9c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (c00000000084b100)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (c00000000084c234)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (c00000000084cf14)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (c00000000084d308)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (c00000000084d758)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (c00000000084dfb0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-stmpe.c (c0000000013a1ac0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088e96c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f6fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-host-common.c (c0000000008917a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/video/backlight/backlight.c (c0000000008a24c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (c0000000008ab8c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (c0000000008c1110)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (c0000000008c24f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/gxt4500.c (c0000000008c3b74)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
```
```
In drivers/video/fbdev/simplefb.c (c0000000008c4bfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d2360)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d47f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (c0000000008e4a18)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (c0000000008f1da8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_vio.c (c00000000091c910)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_vio.c:hvc_vio_probe
```
```
In drivers/tty/hvc/hvc_opal.c (c00000000091e0c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_opal.c:hvc_opal_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000937e2c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093b510)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (c00000000093dd04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (c0000000009411e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/tpm/tpm-chip.c (c0000000009592dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (c0000000009644bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_i2c_atmel.c (c000000000965890)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_atmel.c:i2c_atmel_probe
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (c000000000968230)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_probe
```
```
In drivers/char/tpm/tpm_ibmvtpm.c (c0000000009691f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_probe
  - drivers/char/tpm/tpm_ibmvtpm.c:tpm_ibmvtpm_remove
```
```
In drivers/iommu/iommu-sysfs.c (c00000000097002c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (c00000000097b3ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (c000000000982b04)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (c000000000987eac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (c0000000009a4448)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/misc/sram.c (c0000000009cac10)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (c0000000009cc6f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cdbe0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (c0000000009cf754)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (c0000000009d0e44)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (c0000000009d190c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/arizona-core.c (c0000000009d3884)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (c0000000009dd7e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (c0000000009de418)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (c0000000009e0434)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (c0000000009e065c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (c0000000009e0e24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (c0000000009e21e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (c0000000009e23e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (c0000000009e2bcc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (c0000000009e2ce0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (c0000000009e3288)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (c0000000009e7248)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (c0000000009e8228)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea384)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (c0000000009ea7b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (c0000000009eafa8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (c0000000009ecfdc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (c0000000009ed180)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (c0000000009ed6a8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (c0000000009ee1ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (c0000000009ee834)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (c0000000009eebd4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (c0000000009efcd0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (c0000000009f01d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (c0000000009f0644)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (c0000000009f0c48)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (c0000000009f2140)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (c0000000009f2d3c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0000000009f3f54)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (c0000000009f5bfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (c0000000009f65ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (c0000000009f7578)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (c0000000009f79d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (c0000000009f80c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (c0000000009f8ef4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (c0000000009f9a94)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0000000009fa9f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (c0000000009faf80)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (c0000000009fba48)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (c0000000009fbdf4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/nvdimm/bus.c (c0000000009ff3d4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_bus_probe
```
```
In drivers/nvdimm/dimm.c (c000000000a02a7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (c000000000a04e6c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (c000000000a06084)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/dax/bus.c (c000000000a1ad68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (c000000000a468c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (c000000000a4d450)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (c000000000a52ea4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (c000000000a638c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (c000000000a88ee4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (c000000000a8bfe4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-spi.c (c000000000a8e238)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/vfio/vfio.c (c000000000ab0fe8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/usb/core/hub.c (c000000000ad3a24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (c000000000ad572c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (c000000000adfb5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (c000000000ae9410)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (c000000000af4e0c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (c000000000afe85c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/input/keyboard/atkbd.c (c000000000b83954)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (c000000000b86150)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/rtc/rtc-generic.c (c0000000013b4294)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-generic.c:generic_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d044)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dcf8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-opal.c (c000000000b9e994)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-opal.c:i2c_opal_probe
```
```
In drivers/media/cec/cec-core.c (c000000000b9eee4)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (c000000000ba8df0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/gpio-restart.c (c000000000bab870)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (c000000000babb38)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/supply/power_supply_core.c (c000000000bae8f8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c000000000bb435c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (c000000000bb6540)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc71ec)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (c000000000c06714)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (c000000000c082d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/leds/leds-syscon.c (c000000000c401a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5d2e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (c000000000c65fcc)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (c000000000c68f10)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In kernel/events/core.c (ffffffe0001c7248)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049db8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049f158)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049fb14)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a0d18)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2c60)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3bdc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a9acc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ae316)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004aebbe)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffe0004aefcc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffe0004af34a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-stmpe.c (ffffffe0004afed4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
```
```
In drivers/gpio/gpio-tc3589x.c (ffffffe0004b0776)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffe0004b09fa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffe0004b0ce2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b30d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_probe
```
```
In drivers/pwm/pwm-stmpe.c (ffffffe00002b62a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-stmpe.c:stmpe_pwm_probe
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004da06c)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e46e2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e54e0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e68f6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (ffffffe0004ea200)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (ffffffe0004ea626)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-plat.c:dw_plat_pcie_probe
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f855a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffe000506c0e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffe0005078ba)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000507efe)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/clk/clk-fixed-factor.c (ffffffe00051245c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-factor.c:of_fixed_factor_clk_probe
```
```
In drivers/clk/clk-fixed-rate.c (ffffffe000512838)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:of_fixed_clk_probe
```
```
In drivers/clk/clk-fixed-mmio.c (ffffffe000514c4a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-mmio.c:of_fixed_mmio_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051d208)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e8ce)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffe000528398)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffe00052e218)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000559518)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559f4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serial/max310x.c (ffffffe00055b01a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055d1d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serial/sifive.c (ffffffe00055dbe2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sifive.c:sifive_serial_probe
```
```
In drivers/tty/serdev/core.c (ffffffe00055f0ae)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/tpm/tpm-chip.c (ffffffe000568e94)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000573120)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/base/core.c (ffffffe00057a5d0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffe00057f100)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffe000581994)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/misc/sram.c (ffffffe0005a31d2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffe0005a4294)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4fd0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/stmpe.c (ffffffe0005a6308)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/tc3589x.c (ffffffe0005a71e2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tc3589x.c:tc3589x_probe
```
```
In drivers/mfd/lochnagar-i2c.c (ffffffe0005a777a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_i2c_probe
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a8bf8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffe0005ac3da)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffe0005aca86)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffe0005ae066)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffe0005ae1c2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffe0005ae736)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffe0005af4f2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffe0005af65a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffe0005afbc6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffe0005afc7e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps80031.c (ffffffe0005b0088)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffe0005b29c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffe0005b2e72)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4a56)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffe0005b4e7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffe0005b533c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffe0005b65a2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffe0005b66ca)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffe0005b69fa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffe0005b7004)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffe0005b74a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffe0005b76c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77620.c (ffffffe0005b7f0e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77620.c:max77620_probe
```
```
In drivers/mfd/max77686.c (ffffffe0005b81f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77686.c:max77686_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffe0005b84b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffe0005b87fa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffe0005b961e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffe0005b9e98)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffe0005baaf8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffe0005bbec2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffe0005bc542)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffe0005bcfee)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffe0005bd2fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffe0005bd772)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffe0005bdeb6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/palmas.c:palmas_i2c_probe
```
```
In drivers/mfd/rc5t583.c (ffffffe0005be6b6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffe0005bf0d2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffe0005bf4c0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffe0005bfaf8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/as3722.c (ffffffe0005bfcca)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/nvdimm/bus.c (ffffffe0005c2018)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffe0005c4428)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c614e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffe0005c6c30)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/dax/bus.c (ffffffe0005d1818)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/dax/bus.c:alloc_dax_region
```
```
In drivers/scsi/sd.c (ffffffe0005eb5a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffe0005f0e02)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffe0005f3966)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffe0005ff10c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffe000618806)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffe00061a088)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061bd92)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c2e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
```
```
In drivers/usb/core/hub.c (ffffffe00063ecfe)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffe00064057a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffe000647034)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffe00064d4a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffe000653d56)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a6b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006b0668)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (ffffffe0006b1bf6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be958)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf1b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffe0006bf832)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffe0006c5f5a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/reset/gpio-restart.c (ffffffe0006c7a84)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/gpio-restart.c:gpio_restart_probe
```
```
In drivers/power/reset/ltc2952-poweroff.c (ffffffe0006c7c52)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/reset/ltc2952-poweroff.c:ltc2952_poweroff_probe
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c96e2)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006ccd5a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffe0006ce28c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7e74)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffe0006fef64)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffe000700152)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/edac/sifive_edac.c (ffffffe00003947e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/sifive_edac.c:sifive_edac_init
```
```
In drivers/mmc/core/block.c (ffffffe000718676)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071ba82)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/leds/leds-syscon.c (ffffffe00071e004)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/leds/leds-syscon.c:syscon_led_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffe0007300ac)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffe000731dc8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff810175fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff81204f80)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155d227)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155eb66)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81564c76)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-mmio.c (ffffffff8156a96f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8156af82)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598438)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a66e3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff815af379)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b5538)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815c584f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c6b7b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c6f97)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c7f4a)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815c8576)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff81602c71)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161c071)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81623c92)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81625364)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff81643ce1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff8164909e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff8166981d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff81670a29)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816797ad)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8167b75a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d570)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff8167f6fb)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168ff6a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8169026c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816933d2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81693e1a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c5cf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169de5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff816a220e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff816c0ad0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff816c597c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff816c8a77)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816da36d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff816f6f1d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff816fa86b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816fb95a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm831x-core.c (ffffffff8170043c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81701c26)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff81701dda)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817031b9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81703f79)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/syscon.c (ffffffff81704502)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81706469)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff817089be)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff8170a450)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff8170af8f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81717251)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff81718d4f)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff81735022)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8173a7d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8173cb3d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/nvme/host/core.c (ffffffff817424e8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_ctrl
```
```
In drivers/nvme/host/pci.c (ffffffff817501ee)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/ata/libata-core.c (ffffffff81759b88)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81778e5b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8177b557)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817918e5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/usb/core/hub.c (ffffffff817a4543)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817a4f75)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff817ac661)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817b2e29)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ba30d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff817bf42f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff817dc8a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e3549)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81815679)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (ffffffff81817268)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8181d255)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff8181ebe3)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff81826277)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818288d3)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff8182aab6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff818345d9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8185fe08)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff81860f0b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff828f93e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff828f9444)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81890b50)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81895bef)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8189bb4c)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8189d72b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff81016a2c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff811f7d10)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154dca6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154fda5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff81555ac6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155afd3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff8155b682)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815875c8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff81595883)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff8159e509)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a4318)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/acpi/button.c (ffffffff815ee121)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/nfit/core.c (ffffffff815f44c5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_desc_init
  - drivers/acpi/nfit/core.c:shutdown_dimm_notify
  - drivers/acpi/nfit/core.c:acpi_nfit_add_dimm
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816105a1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816108b3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816182e2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816199e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff81624161)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff816294fe)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8164fb29)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165889d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a84a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c660)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d95a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8166dc5c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81670dc2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff8167180a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679fbf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b84c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff8167fbfe)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff8169bd80)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff816a0bfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff816a3da7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff816b49ed)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/misc/sram.c (ffffffff816ce67b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/arizona-core.c (ffffffff816cf76a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm831x-core.c (ffffffff816d424c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-spi.c (ffffffff816d5a36)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff816d5bea)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d6fb9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff816d7d79)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/syscon.c (ffffffff816d7f82)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/nvdimm/bus.c (ffffffff816d9ee9)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff816dc43e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff816dded0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff816dea0f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/pmem.c (ffffffff816eaf1d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
```
In drivers/nvdimm/blk.c (ffffffff816eee72)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/blk.c:nd_blk_probe
```
```
In drivers/nvdimm/e820.c (ffffffff816ef781)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff816f127f)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713b2a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_probe
  - drivers/scsi/storvsc_drv.c:storvsc_dev_remove
```
```
In drivers/scsi/sd.c (ffffffff81716cc2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8171c478)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8171e7dd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/nvme/host/core.c (ffffffff81724178)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_init_ctrl
```
```
In drivers/nvme/host/pci.c (ffffffff8173008e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In drivers/ata/libata-core.c (ffffffff81739a28)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff81758c0b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff8175b307)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/vfio/vfio.c (ffffffff8177b80d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/usb/core/hub.c (ffffffff817960b4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81796a85)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff8179e061)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817a4859)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817abd31)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dcda9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/misc/uinput.c (ffffffff817de958)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff817e4945)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff817e6283)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff817ed907)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817eff63)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/hwmon/hwmon.c (ffffffff817f2146)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fbc69)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818273d8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff818284db)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff828f0ecd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff828f0f2d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81849ed0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8185901c)
Location: include/linux/device.h:1391
Inline: True
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
In arch/x86/events/intel/uncore.c (ffffffff810175bc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff81202d50)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558f67)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81559a1e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155b9c6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155dac5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff815637e6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568cf3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff815692bb)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff815696e9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81569947)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81569c39)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81569f8e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff8156c0ff)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8156c780)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8156c853)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598978)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pci-meson.c (ffffffff815a6c73)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_probe
```
```
In drivers/video/backlight/backlight.c (ffffffff815af909)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b5ac8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815c5ddf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c710b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815c7527)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c84da)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815c8b06)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff81626ae1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff81627207)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637acc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649e51)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff8164a163)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81651c32)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653334)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff816720c1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff8167745e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff81697bfd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff8169edf9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a7b8d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff816a9b3a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab950)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff816adadb)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816be1da)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816be4dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816c1642)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816c208a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816ca83f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cc0cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff816d047e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff816eefa0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff816f3e4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff816f6fe7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81707cfd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff8172446d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff81727c9b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff8172867c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81729d19)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-core.c (ffffffff8172b0ba)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8172f7dd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff8172fe1c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff817315f0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff81731776)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff81731c47)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff81732b8c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff81732d0b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff81733142)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff817331fa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff817332a7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff81733752)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff8173608c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff817364fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817385d9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81738a2c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81738ee9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff8173a3c9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff8173a571)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff8173a7bd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8173ae4c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8173b31b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff8173b59c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff8173ba8a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8173befe)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff8173ce6c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff8173d6e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8173e264)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff8173f39d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8173fc6e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff817406e4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff81740acf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff81741204)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8174170d)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff81741a9a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817425f7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff81742a52)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff81742ccf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff81742ff9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff817432f1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81745239)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff8174778e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff81749220)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff81749d5f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81756021)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff81757b1f)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff817757b2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff8177af68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff8177d2cd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff817898f8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff817a91fb)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817ab8f7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817c1a61)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/vfio.c (ffffffff817c65dd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/usb/core/hub.c (ffffffff817e0fe3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817e1a15)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff817e9101)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817ef8c9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f6dad)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff817fbecf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81819340)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181ffe9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818547f9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81856040)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81858748)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8185e735)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff81868252)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868b68)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a797)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186adb3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff8186bb23)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff818731b7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875813)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff818785d5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff8187a0e6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883c09)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818af438)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff818b053b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff8290dc1c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff8290dc7c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e4650)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/devfreq/devfreq-event.c (ffffffff818eb23c)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff818ece1b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
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
In arch/x86/events/intel/uncore.c (ffffffff810177fc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In kernel/events/core.c (ffffffff81212920)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - kernel/events/core.c:pmu_dev_alloc
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572df7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815738ae)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815759e6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815779e5)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
```
In drivers/gpio/gpiolib.c (ffffffff8157d706)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582c13)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
```
In drivers/gpio/gpio-palmas.c (ffffffff815831db)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-palmas.c:palmas_gpio_probe
```
```
In drivers/gpio/gpio-rc5t583.c (ffffffff81583609)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-rc5t583.c:rc5t583_gpio_probe
```
```
In drivers/gpio/gpio-tps6586x.c (ffffffff81583867)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps6586x.c:tps6586x_gpio_probe
```
```
In drivers/gpio/gpio-tps65910.c (ffffffff81583b59)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps65910.c:tps65910_gpio_probe
```
```
In drivers/gpio/gpio-tps68470.c (ffffffff81583eae)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-tps68470.c:tps68470_gpio_probe
```
```
In drivers/gpio/gpio-xilinx.c (ffffffff815843c2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/gpio/gpio-xilinx.c:xgpio_probe
```
```
In drivers/pwm/pwm-crc.c (ffffffff815865ff)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-crc.c:crystalcove_pwm_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81586c80)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81586d53)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b2db8)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-plat.c (0)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/backlight/backlight.c (ffffffff815c9379)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815cf538)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:fb_init_device
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815df97f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815e0cab)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/vesafb.c (ffffffff815e10c7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
```
In drivers/video/fbdev/efifb.c (ffffffff815e207e)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (ffffffff815e2966)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/video/fbdev/simplefb.c:simplefb_probe
```
```
In drivers/acpi/button.c (ffffffff81640991)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/fan.c (ffffffff816410b7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/fan.c:acpi_fan_probe
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651dfc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816643e1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
```
In drivers/clk/x86/clk-lpt.c (ffffffff816646f3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/clk/x86/clk-lpt.c:lpt_clk_probe
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166c2c2)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166d9c4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/regulator/core.c (ffffffff8168c721)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/tty/tty_io.c (ffffffff81691c9e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff816b1a9d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
```
```
In drivers/tty/serial/8250/8250_pnp.c (ffffffff816b92b9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pnp.c:serial_pnp_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1fed)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/max310x.c (ffffffff816c3f9a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c5db0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
```
In drivers/tty/serdev/core.c (ffffffff816c7f3b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_alloc
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d87aa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816d8aac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816dbc12)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff816dc65a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpmm_chip_alloc
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4d0f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e659c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff816eaa0e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_remove
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/base/core.c (ffffffff81709600)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
```
```
In drivers/base/dd.c (ffffffff8170e67c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
```
In drivers/base/cpu.c (ffffffff81711887)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff8172272d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/block/xen-blkfront.c (ffffffff8173fa4d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
```
In drivers/misc/sram.c (ffffffff817430db)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
```
```
In drivers/mfd/88pm860x-core.c (ffffffff81743abc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/88pm860x-core.c:pm860x_probe
  - drivers/mfd/88pm860x-core.c:pm860x_probe
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81745159)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_core_probe
  - drivers/mfd/htc-i2cpld.c:htcpld_setup_chips
```
```
In drivers/mfd/arizona-core.c (ffffffff817464fa)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/wm8400-core.c (ffffffff8174ac1d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8400-core.c:wm8400_i2c_probe
```
```
In drivers/mfd/wm831x-core.c (ffffffff8174b25c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-core.c:wm831x_device_init
```
```
In drivers/mfd/wm831x-i2c.c (ffffffff8174ca30)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-i2c.c:wm831x_i2c_probe
```
```
In drivers/mfd/wm831x-spi.c (ffffffff8174cbb6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_probe
```
```
In drivers/mfd/wm8350-core.c (ffffffff8174d087)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-core.c:wm8350_device_init
```
```
In drivers/mfd/wm8350-i2c.c (ffffffff8174dfcc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/wm8350-i2c.c:wm8350_i2c_probe
```
```
In drivers/mfd/tps65910.c (ffffffff8174e14b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65910.c:tps65910_i2c_probe
```
```
In drivers/mfd/tps65912-i2c.c (ffffffff8174e582)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-i2c.c:tps65912_i2c_probe
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8174e63a)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_probe
```
```
In drivers/mfd/tps68470.c (ffffffff8174e6e7)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps68470.c:tps68470_probe
```
```
In drivers/mfd/tps80031.c (ffffffff8174eb92)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps80031.c:tps80031_probe
  - drivers/mfd/tps80031.c:tps80031_probe
```
```
In drivers/mfd/twl4030-audio.c (ffffffff817514cc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl4030-audio.c:twl4030_audio_probe
```
```
In drivers/mfd/twl6040.c (ffffffff8175193c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/twl6040.c:twl6040_probe
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753b69)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
```
In drivers/mfd/smsc-ece1099.c (ffffffff81753e6c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/smsc-ece1099.c:smsc_i2c_probe
```
```
In drivers/mfd/da903x.c (ffffffff81754329)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_probe
```
```
In drivers/mfd/da9052-spi.c (ffffffff81755809)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_probe
```
```
In drivers/mfd/da9052-i2c.c (ffffffff817559b1)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9052-i2c.c:da9052_i2c_probe
```
```
In drivers/mfd/lp8788.c (ffffffff81755bfd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/lp8788.c:lp8788_probe
```
```
In drivers/mfd/da9055-i2c.c (ffffffff8175628c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9055-i2c.c:da9055_i2c_probe
```
```
In drivers/mfd/da9063-i2c.c (ffffffff8175675b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/da9063-i2c.c:da9063_i2c_probe
```
```
In drivers/mfd/max14577.c (ffffffff817569dc)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max14577.c:max14577_i2c_probe
  - drivers/mfd/max14577.c:max14577_i2c_probe
```
```
In drivers/mfd/max77693.c (ffffffff81756eca)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max77843.c (ffffffff8175733e)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max77843.c:max77843_probe
  - drivers/mfd/max77843.c:max77843_probe
```
```
In drivers/mfd/max8925-i2c.c (ffffffff817582ac)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
  - drivers/mfd/max8925-i2c.c:max8925_probe
```
```
In drivers/mfd/max8997.c (ffffffff81758b24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff817596a4)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/ab3100-core.c (ffffffff8175a7dd)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/ab3100-core.c:ab3100_probe
```
```
In drivers/mfd/adp5520.c (ffffffff8175b0ae)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/adp5520.c:adp5520_probe
```
```
In drivers/mfd/tps6586x.c (ffffffff8175bb24)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
```
In drivers/mfd/tps65090.c (ffffffff8175bf0f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/tps65090.c:tps65090_i2c_probe
```
```
In drivers/mfd/aat2870-core.c (ffffffff8175c644)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_i2c_probe
```
```
In drivers/mfd/palmas.c (ffffffff8175cb4d)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/mfd/rc5t583.c (ffffffff8175ceda)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8175da37)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/mfd/syscon.c (ffffffff8175de92)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:syscon_probe
```
```
In drivers/mfd/as3711.c (ffffffff8175e11f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/as3711.c:as3711_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_core.c (ffffffff8175e449)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
```
```
In drivers/mfd/intel_soc_pmic_chtwc.c (ffffffff8175e741)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
```
```
In drivers/nvdimm/bus.c (ffffffff81760679)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/nvdimm/dimm.c (ffffffff81762bce)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/dimm.c:nvdimm_remove
```
```
In drivers/nvdimm/region_devs.c (ffffffff817646a0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_activate
```
```
In drivers/nvdimm/region.c (ffffffff817651df)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/region.c:nd_region_remove
```
```
In drivers/nvdimm/e820.c (ffffffff81771491)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/nvdimm/e820.c:e820_pmem_probe
```
```
In drivers/dax/bus.c (ffffffff81772fbf)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/scsi/sd.c (ffffffff8178f592)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_remove
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sr.c (ffffffff81795308)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sg.c (ffffffff81797112)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_add_device
```
```
In drivers/ata/libata-core.c (ffffffff817a3748)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/spi/spi.c (ffffffff817c308b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_alloc_controller
```
```
In drivers/spi/spi-mem.c (ffffffff817c5887)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_probe
```
```
In drivers/net/xen-netfront.c (ffffffff817dbd1c)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:netfront_probe
```
```
In drivers/vfio/vfio.c (ffffffff817e087d)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_add_group_dev
  - drivers/vfio/vfio.c:vfio_device_put
```
```
In drivers/usb/core/hub.c (ffffffff817fb2d3)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817fbe05)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/driver.c (ffffffff81803631)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81809b09)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81810fed)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_remove
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/dwc2/platform.c (ffffffff81815fdf)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81833330)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
  - drivers/usb/host/ehci-platform.c:ehci_platform_probe
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839f59)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186fd39)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_set_device_attrs
  - drivers/input/keyboard/atkbd.c:atkbd_disconnect
```
```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81871170)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
```
```
In drivers/input/misc/uinput.c (ffffffff81873828)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/rtc/rtc-cmos.c (ffffffff8187a575)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81884727)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884d43)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/media/cec/cec-core.c (ffffffff81885ab3)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/ptp/ptp_clock.c (ffffffff8188eb67)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818911b3)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893f75)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
```
```
In drivers/hwmon/hwmon.c (ffffffff81895ae6)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189f6c9)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff818cb6c8)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
```
In drivers/edac/edac_pci.c (ffffffff818cc7cb)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_create_generic_ctl
```
```
In drivers/eisa/pci_eisa.c (ffffffff82914632)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
```
In drivers/eisa/virtual_root.c (ffffffff82914692)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/eisa/virtual_root.c:virtual_eisa_root_init
```
```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819012b0)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_remove
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8190634f)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev
```
```
In drivers/devfreq/devfreq-event.c (ffffffff8190c2bc)
Location: include/linux/device.h:1391
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffff8190de9b)
Location: include/linux/device.h:1391
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_register
```
</details>
</li>
</ul>

## Differences
