# Function: <code>pm_runtime_set_active</code>

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
In drivers/pci/pci.c (ffffffff81437393)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/runtime.c (ffffffff8155775a)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff8157db21)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8158f119)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81590bdd)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81591794)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81595d74)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff815a809e)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b5a81)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff815b8f97)
Location: include/linux/pm_runtime.h:257
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff815c8d7b)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff815db0a7)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81608571)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81613aca)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff8161f50c)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/mmc.c (ffffffff816c479a)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_resume
```
```
In drivers/mmc/core/sd.c (ffffffff816c7e1a)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_resume
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9a58)
Location: include/linux/pm_runtime.h:257
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In drivers/pci/pci.c (ffffffff81482f93)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/runtime.c (ffffffff815a97fe)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff815d2c96)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff815e3fce)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff815e59ce)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff815e6564)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff815eab62)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff815fff25)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160e196)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff816118b0)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8162135b)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81634c87)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81668241)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81675011)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff8167febc)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/sdio.c (ffffffff8172cf3e)
Location: include/linux/pm_runtime.h:263
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pci/pci.c (ffffffff814a46f3)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/runtime.c (ffffffff815d85dc)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff815ff9da)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff81610e7e)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff8161287e)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816133fe)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff81617972)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff8162f57d)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163da4a)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff81641140)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff81651edb)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81665dd7)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81695f61)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816a2ca1)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff816adbf9)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/mmc/core/sdio.c (ffffffff8175ff55)
Location: include/linux/pm_runtime.h:266
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pci/pci.c (ffffffff814ae7b3)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/runtime.c (ffffffff815ecba6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff816138e3)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff81624f55)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff8162691a)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8162745a)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8162b884)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff81644643)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81652565)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff81655999)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8166651b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff8167a576)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff816ab371)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816b7e51)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff816c2da9)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e77ee)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817278bd)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e854)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pci/pci.c (ffffffff814edb83)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff814f0460)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff8153bbb6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
```
```
In drivers/base/power/runtime.c (ffffffff81653f56)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/mfd/arizona-core.c (ffffffff8167bdf4)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8168d845)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff8168f1ea)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8168fd2a)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816941c7)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff816ad5d6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816bb97d)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff816bef49)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff816cfb7b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff816e3bd6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817167d1)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81723721)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff8172eb79)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8175403f)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798c33)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4df8)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff815129fd)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff8151d7b3)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff8151fdc6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff815720e8)
Location: include/linux/pm_runtime.h:254
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81691876)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff816b78b2)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff816c983b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff816cb2f6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816cbe3a)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816d031b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff816e9ec6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f7d92)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff816fb565)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8170c5ab)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81720449)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817555f1)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817623b1)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff8176dc98)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81794524)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817dba3b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8183e204)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8152825c)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff81532ef3)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff81535bf6)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff81589ec8)
Location: include/linux/pm_runtime.h:254
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b1e66)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff816d8af2)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff816eadbb)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff816ec896)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff816ed3ea)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff816f193b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff8170d98a)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8171a692)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff8171dfbe)
Location: include/linux/pm_runtime.h:254
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8172ea2b)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81742d39)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81779b21)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817869c1)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81792318)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817baa79)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802de4)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8186a1b4)
Location: include/linux/pm_runtime.h:254
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff815574e9)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff81562663)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff81565c8d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff815ba949)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c973f)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
```
In drivers/base/power/main.c (ffffffff816ebd00)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff81714616)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8172466d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81726019)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81726b6a)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8172afbb)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff817491d3)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81755d88)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff817596ee)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8176a21c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff8177e9f5)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817b7981)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817c4eb4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff817d0c5d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa3ab)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818441eb)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818ae083)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff81578b19)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff81583803)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff81586fe9)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff815dbbe9)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815ea95f)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
```
In drivers/base/power/main.c (ffffffff8170fdc9)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff8173891e)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8174890f)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff8174a2e2)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8174ae2d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8174f1bb)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff8176d323)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177a008)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d60e)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8178e27c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff817a26b5)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817e8151)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817f5854)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81801b5d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b1e4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875b61)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0533)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8161db29)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff8162a363)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff817cbd60)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff817f5f4c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8180671f)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81808042)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81808d9d)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8180d88b)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff8182f8ed)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183d05e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840a7e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff81853e4c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff818664e5)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff818b76a1)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818c5bf4)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff818d23e2)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f5dc9)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fccf5)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a4aa)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff819b3508)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff81644341)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff816507c3)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff817e07d0)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff81c11194)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff81c1422e)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81818002)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81818c6d)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8181c60b)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff81c163ff)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184d85e)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff81850fbe)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8186411c)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff818752f5)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff818c5fb1)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818d1ac4)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff818dc7c2)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fe979)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81905625)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8195003a)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff819b5a58)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff816270a1)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff816333d3)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff817c43d0)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff81c03331)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff81c06581)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff817fc442)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff817fd08d)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff817ff9cb)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff81c08109)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81830d14)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff8183404e)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff81846d7c)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81857af5)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff818a9291)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818b50e4)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff818bfa51)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e20c9)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e8e15)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933eec)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8199a265)
Location: include/linux/pm_runtime.h:495
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8169696f)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff816a3573)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff8184e7b0)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/max77693.c (ffffffff81d09a4b)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff818859ff)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81886b89)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/scsi/hosts.c (ffffffff81d0bf8d)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bcd48)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c004e)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff818d319c)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff818e6515)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff8193e1a1)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8194a664)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff819560c1)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e2cc)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81985205)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d72ec)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81a46b1c)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff817b788f)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff817c57df)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff81994875)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/max77693.c (ffffffff81ed1e98)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff819ce7df)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff819cfa69)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/scsi/hosts.c (ffffffff81ed4ecd)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a08f18)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-core.c (ffffffff81a238cb)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81a37995)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81a961d1)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81aa3324)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81aafc59)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad99d9)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae0e54)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b3a06e)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb48fa)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff818d205a)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff818e28ff)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff81b05335)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/max77693.c (ffffffff81b4569c)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b474d6)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b489b0)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/scsi/hosts.c (ffffffff81b76ea2)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b882ec)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-core.c (ffffffff81ba576b)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81bbc8c2)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81c18929)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c28e74)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81c37c79)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64af9)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c6ab)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf9ee)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58fac)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8191505a)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff81925d3f)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff81b52d25)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/max77693.c (ffffffff81b98a6c)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81b9a8a6)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81b9be10)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/scsi/hosts.c (ffffffff81bcab32)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdc1c8)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-core.c (ffffffff81bfbdbb)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81c14132)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81c7f909)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c8fe44)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81c9f009)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccbf09)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3c9b)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37ae7)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3959)
Location: include/linux/pm_runtime.h:538
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8195cfca)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff8196e4bf)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/base/power/main.c (ffffffff81babada)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/max77693.c (ffffffff81beca1c)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81bee841)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff81befdbb)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/scsi/hosts.c (ffffffff81c1f762)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c30ef8)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-transport.c (ffffffff81c69304)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff81d342f9)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81d449f4)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81d53c57)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d80de9)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88c5b)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81dedd67)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7c239)
Location: include/linux/pm_runtime.h:536
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pci/pci.c (ffff8000106e7800)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffff8000106eaff0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffff800010767d14)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/amba/bus.c (ffff8000107b9458)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891b60)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892c20)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d25f8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
```
```
In drivers/base/power/main.c (ffff800010900408)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffff8000109334ec)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffff800010946424)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffff800010947ea0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffff800010948c34)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffff80001094e254)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffff80001096f9e4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f6e8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffff8000109837d4)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffff800010999350)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffff8000109ae684)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd30c)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9c30)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hub.c (ffff800010a1743c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffff800010a26788)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffff800010a35fb8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba99c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abcf9c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a75c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/block.c (ffff800010b409fc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64884)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_probe
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65a14)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_probe
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
In arch/arm/mach-omap2/omap_device.c (c033b230)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - arch/arm/mach-omap2/omap_device.c:_omap_device_notifier_call
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
```
```
In drivers/pci/pci.c (c08828e0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (c08866b0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/amba/bus.c (c08e575c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098e064)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
```
```
In drivers/base/power/main.c (c09ea68c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (c0a16494)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (c0a2f648)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (c0a310a0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0a31cd4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0a382bc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (c0a44c58)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (c0a52508)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (c0a5608c)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (c0a67954)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (c0a7daec)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/ata/libahci_platform.c (c0a88130)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0acae74)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hub.c (c0aef4b8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c0afc8a0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (c0b094cc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99ef4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9bc08)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/mmc/core/sdio.c (c0c1515c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/block.c (c0c1b0e8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2edf0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
```
In drivers/clocksource/sh_cmt.c (c0c45314)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_probe
```
```
In drivers/clocksource/sh_mtu2.c (c0c457f8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_probe
```
```
In drivers/clocksource/sh_tmu.c (c0c469b4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_probe
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
In drivers/pci/pci.c (c000000000861ff8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (c000000000866560)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/base/power/main.c (c00000000099dbb8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (c0000000009d417c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (c0000000009f0a84)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (c0000000009f2e38)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (c0000000009f3ff4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (c0000000009fab5c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (c000000000a29080)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a3b1b0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (c000000000a40334)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (c000000000a5a1ec)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (c000000000a7586c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (c000000000ad00bc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c000000000ae1f40)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (c000000000af4044)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9de78)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (c000000000c37058)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pci/pci.c (ffffffe0004bdec8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a925c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffe0005b8786)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffe0005b9f60)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffe0005bab72)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffe0005bf136)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffe0005d99b0)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e596a)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/ata/libata-core.c (ffffffe0005f86ee)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffe00060b5bc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffe00063c2b6)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffe000648670)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffe0006534f2)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf320)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffe000712196)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/block.c (ffffffe000717c7e)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
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
In drivers/pci/pci.c (ffffffff81577d23)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/acpi/device_pm.c (ffffffff815ce2b9)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816d5dbc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff816fc67e)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff81721a13)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172e6f8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff81731cfe)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8175340c)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81767775)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817a0531)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817adc34)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff817b9f3d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e35c4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81883ef3)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pci/pci.c (ffffffff81566463)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff81569c49)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff815b7e79)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815c53cf)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
```
In drivers/base/power/main.c (ffffffff816b07b9)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff816d048e)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff816fae43)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81707b18)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b11e)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff817332ac)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff817475d5)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817921a1)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8179f634)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff817ab96d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff8156c869)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff81577553)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff8157ad39)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff815cfec9)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815dec3f)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
```
In drivers/base/power/main.c (ffffffff81703a89)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff8172bdde)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8173bdcf)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff8173d7a2)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8173e2ed)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8174267b)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff817607e3)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176d4c8)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770ace)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff817830fc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff81797535)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817dcfd1)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817ea6d4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff817f69dd)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81820064)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b011)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818d5393)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/pwm/pwm-lpss-platform.c (ffffffff81586d69)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
```
```
In drivers/pci/pci.c (ffffffff81591a13)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pm_init
```
```
In drivers/pci/pci-driver.c (ffffffff81595349)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
```
In drivers/acpi/device_pm.c (ffffffff815e9d89)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/acpi/acpi_lpss.c (ffffffff815f8aff)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
```
In drivers/base/power/main.c (ffffffff8171e7d9)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/mfd/arizona-core.c (ffffffff8174721e)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/max77693.c (ffffffff8175720f)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max77693.c:max77693_i2c_probe
```
```
In drivers/mfd/max8997.c (ffffffff81758be2)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8997.c:max8997_i2c_probe
```
```
In drivers/mfd/max8998.c (ffffffff8175972d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/max8998.c:max8998_i2c_probe
```
```
In drivers/mfd/sec-core.c (ffffffff8175dabb)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mfd/sec-core.c:sec_pmic_probe
```
```
In drivers/scsi/hosts.c (ffffffff8177be43)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81788c68)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c26e)
Location: include/linux/pm_runtime.h:255
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8179cfbc)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libata-transport.c (ffffffff817b13a5)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_tport_add
```
```
In drivers/usb/core/hub.c (ffffffff817f72a1)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81804914)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/port.c (ffffffff81810c1d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839fd4)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884fa1)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1eb3)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
</details>
</li>
</ul>

## Differences
