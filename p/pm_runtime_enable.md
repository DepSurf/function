# Function: <code>pm_runtime_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81555f20)
Location: drivers/base/power/runtime.c:1207
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81555f20-ffffffff81555f99: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a7f60)
Location: drivers/base/power/runtime.c:1211
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815a7f60-ffffffff815a7fd5: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d6730)
Location: drivers/base/power/runtime.c:1299
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815d6730-ffffffff815d67a5: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815eb130)
Location: drivers/base/power/runtime.c:1299
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815eb130-ffffffff815eb1a9: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816524e0)
Location: drivers/base/power/runtime.c:1284
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816524e0-ffffffff8165258e: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168ddc0)
Location: drivers/base/power/runtime.c:1284
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8168ddc0-ffffffff8168de6c: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae060)
Location: drivers/base/power/runtime.c:1291
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816ae060-ffffffff816ae10c: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1370
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816ea64b-ffffffff816ea666: pm_runtime_enable.cold (STB_LOCAL)
ffffffff816e7f40-ffffffff816e7fe6: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8170e6ab-ffffffff8170e6c6: pm_runtime_enable.cold (STB_LOCAL)
ffffffff8170bfa0-ffffffff8170c046: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1393
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff817ca08b-ffffffff817ca0a6: pm_runtime_enable.cold (STB_LOCAL)
ffffffff817c7270-ffffffff817c7316: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1425
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81c0ec38-ffffffff81c0ec53: pm_runtime_enable.cold (STB_LOCAL)
ffffffff817dbcf0-ffffffff817dbd96: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1425
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81c00dbe-ffffffff81c00dd9: pm_runtime_enable.cold (STB_LOCAL)
ffffffff817c00b0-ffffffff817c0159: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1444
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81d03848-ffffffff81d03863: pm_runtime_enable.cold (STB_LOCAL)
ffffffff8184a420-ffffffff8184a4c9: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1475
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81ecbff8-ffffffff81ecc027: pm_runtime_enable.cold (STB_LOCAL)
ffffffff8198f620-ffffffff8198f6c2: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81aff740)
Location: drivers/base/power/runtime.c:1488
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81aff740-ffffffff81aff801: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4daf0)
Location: drivers/base/power/runtime.c:1488
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serial/serial_ctrl.c:serial_ctrl_probe
  - drivers/tty/serial/serial_port.c:serial_port_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81b4daf0-ffffffff81b4dbb1: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba6070)
Location: drivers/base/power/runtime.c:1489
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serial/serial_ctrl.c:serial_ctrl_probe
  - drivers/tty/serial/serial_port.c:serial_port_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/base/power/main.c:device_resume_early
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81ba6070-ffffffff81ba6131: pm_runtime_enable (STB_GLOBAL)
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
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fb1f0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/amba/bus.c:amba_probe
  - drivers/clk/mediatek/clk-mt8183-mfgcfg.c:clk_mt8183_mfg_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/arm-smmu.c:arm_smmu_device_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/clocksource/sh_cmt.c:sh_cmt_probe
  - drivers/clocksource/sh_tmu.c:sh_tmu_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
**Symbols:**

```
ffff8000108fb1f0-ffff8000108fb318: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e6388)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/phy/phy-core.c:phy_create
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/pwm/pwm-tipwmss.c:pwmss_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/amba/bus.c:amba_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/ti/edma.c:edma_tptc_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/omap-iommu.c:omap_iommu_probe
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/iommu/exynos-iommu.c:exynos_sysmmu_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_probe
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
  - drivers/clocksource/sh_cmt.c:sh_cmt_probe
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_probe
  - drivers/clocksource/sh_tmu.c:sh_tmu_probe
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_probe
```
**Symbols:**

```
c09e6388-c09e646c: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000997820)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c000000000997820-c00000000099795c: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058a29c)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_probe
  - drivers/phy/phy-core.c:phy_create
  - drivers/pci/pci.c:pci_pm_init
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_probe
```
**Symbols:**

```
ffffffe00058a29c-ffffffe00058a366: pm_runtime_enable (STB_GLOBAL)
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
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816d3dfb-ffffffff816d3e16: pm_runtime_enable.cold (STB_LOCAL)
ffffffff816d16f0-ffffffff816d1796: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pci/pci.c:pci_pm_init
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
**Symbols:**

```
ffffffff816af095-ffffffff816af0b0: pm_runtime_enable.cold (STB_LOCAL)
ffffffff816aca10-ffffffff816acab6: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8170236b-ffffffff81702386: pm_runtime_enable.cold (STB_LOCAL)
ffffffff816ffc60-ffffffff816ffd06: pm_runtime_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pm_runtime_enable(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/runtime.c (0)
Location: drivers/base/power/runtime.c:1372
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:phy_create
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/pci/pci.c:pci_pm_init
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:device_resume
  - drivers/base/power/main.c:device_resume_early
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libata-transport.c:ata_tport_add
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/mmc.c:mmc_resume
  - drivers/mmc/core/sd.c:mmc_sd_resume
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8171cb82-ffffffff8171cb9d: pm_runtime_enable.cold (STB_LOCAL)
ffffffff8171a6f0-ffffffff8171a796: pm_runtime_enable (STB_GLOBAL)
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
