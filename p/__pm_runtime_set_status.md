# Function: <code>__pm_runtime_set_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815574f0)
Location: drivers/base/power/runtime.c:1009
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff815574f0-ffffffff81557729: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9540)
Location: drivers/base/power/runtime.c:1009
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815a9540-ffffffff815a97c0: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8210)
Location: drivers/base/power/runtime.c:1087
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815d8210-ffffffff815d84c1: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ec870)
Location: drivers/base/power/runtime.c:1087
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815ec870-ffffffff815ecb2a: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81653c70)
Location: drivers/base/power/runtime.c:1088
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/device_pm.c:acpi_subsys_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81653c70-ffffffff81653edd: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168eaf0)
Location: drivers/base/power/runtime.c:1088
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8168eaf0-ffffffff8168ed5c: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816aee20)
Location: drivers/base/power/runtime.c:1095
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816aee20-ffffffff816af08c: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1131
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816ea666-ffffffff816ea6b0: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff816e97a0-ffffffff816e9a2d: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8170e6c6-ffffffff8170e710: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff8170d800-ffffffff8170da8d: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1154
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff817ca0a6-ffffffff817ca0f1: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff817c9370-ffffffff817c96a7: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1186
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81c0ec53-ffffffff81c0ec9e: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff817dde70-ffffffff817de1ac: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1186
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81c00dd9-ffffffff81c00e20: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff817c21f0-ffffffff817c25a7: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1205
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81d03863-ffffffff81d038aa: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff8184bec0-ffffffff8184c279: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1233
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81ecc027-ffffffff81ecc079: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff81991920-ffffffff81991c4a: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01d40)
Location: drivers/base/power/runtime.c:1246
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81b01d40-ffffffff81b020ad: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4fe40)
Location: drivers/base/power/runtime.c:1246
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81b4fe40-ffffffff81b50196: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba83c0)
Location: drivers/base/power/runtime.c:1247
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81ba83c0-ffffffff81ba8716: __pm_runtime_set_status (STB_GLOBAL)
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
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fcd10)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/amba/bus.c:amba_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/clocksource/sh_cmt.c:sh_cmt_probe
  - drivers/clocksource/sh_tmu.c:sh_tmu_probe
```
**Symbols:**

```
ffff8000108fcd10-ffff8000108fd0ac: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e84b8)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - arch/arm/mach-omap2/omap_device.c:_omap_device_notifier_call
  - arch/arm/mach-omap2/omap_device.c:omap_device_build_from_dt
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/amba/bus.c:amba_probe
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/clocksource/sh_cmt.c:sh_cmt_probe
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_probe
  - drivers/clocksource/sh_tmu.c:sh_tmu_probe
```
**Symbols:**

```
c09e84b8-c09e8750: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999510)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c000000000999510-c000000000999904: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058bc58)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe00058bc58-ffffffe00058bf14: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816d3e16-ffffffff816d3e60: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff816d2f50-ffffffff816d31dd: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816af0b0-ffffffff816af0fa: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff816ae240-ffffffff816ae4c1: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81702386-ffffffff817023d0: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff817014c0-ffffffff8170174d: __pm_runtime_set_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __pm_runtime_set_status(struct device *dev, unsigned int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1133
Inline: False
Direct callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/base/power/main.c:device_resume_noirq
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/max77693.c:max77693_i2c_probe
  - drivers/mfd/max8997.c:max8997_i2c_probe
  - drivers/mfd/max8998.c:max8998_i2c_probe
  - drivers/mfd/sec-core.c:sec_pmic_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8171cb9d-ffffffff8171cbe4: __pm_runtime_set_status.cold (STB_LOCAL)
ffffffff8171c2d0-ffffffff8171c50c: __pm_runtime_set_status (STB_GLOBAL)
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
