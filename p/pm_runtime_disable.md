# Function: <code>pm_runtime_disable</code>

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
In drivers/phy/phy-core.c (ffffffff8141c1e6)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81422eba)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_remove
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a51a)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/base/power/runtime.c (ffffffff81557d36)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff815597d7)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff8157d2b6)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
```
```
In drivers/scsi/scsi_pm.c (ffffffff815b8f86)
Location: include/linux/pm_runtime.h:267
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff815c8d6e)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81608846)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81614eb7)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff816c4c77)
Location: include/linux/pm_runtime.h:267
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff816c6a92)
Location: include/linux/pm_runtime.h:267
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9a43)
Location: include/linux/pm_runtime.h:267
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
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
In drivers/phy/phy-core.c (ffffffff814647fd)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8147531a)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/base/power/runtime.c (ffffffff815a9de6)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff815ab98d)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff815d2376)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/scsi_pm.c (ffffffff816118a3)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8162134e)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81668513)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81675004)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core.c (ffffffff816dc999)
Location: include/linux/pm_runtime.h:273
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81727c37)
Location: include/linux/pm_runtime.h:273
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81729a62)
Location: include/linux/pm_runtime.h:273
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8172c9f5)
Location: include/linux/pm_runtime.h:273
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff81483afd)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814978ea)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/base/power/runtime.c (ffffffff815d84d6)
Location: include/linux/pm_runtime.h:276
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815da6e9)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff815ff048)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff8162f5c0)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff81641133)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff81651ece)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81696233)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816a2c94)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core.c (ffffffff8170ccd9)
Location: include/linux/pm_runtime.h:276
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff8175aca7)
Location: include/linux/pm_runtime.h:276
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff8175cb62)
Location: include/linux/pm_runtime.h:276
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8175fc13)
Location: include/linux/pm_runtime.h:276
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8148cfdd)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a15aa)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/base/power/runtime.c (ffffffff815ed0c6)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815ef13b)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff81612ec8)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff8164468b)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff8165598c)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8166650e)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff816ab62d)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816b7e44)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e74be)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81720135)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727215)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff81777057)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff8177b382)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e41b)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff814c90ad)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814dff6a)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/base/power/runtime.c (ffffffff81654476)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816564f2)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff8167b738)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff816ad61e)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff816bef3c)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff816cfb6e)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81716a8d)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81723714)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753ceb)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8179146a)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81799066)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff817ed467)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff817f1dc2)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff817f49b3)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
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
In block/blk-core.c (ffffffff8148035a)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/phy/phy-core.c (ffffffff814fa04d)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f305)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8151298a)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/base/power/runtime.c (ffffffff8168fab5)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81692186)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff816b6748)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff816e9f5e)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff816fb558)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8170c59e)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff8175598a)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817623a4)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8179432d)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817d3eca)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db565)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81836576)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff8183b071)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8183dee1)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8150ecbd)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524975)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff815281da)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff816614bf)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff816afe45)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b2803)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff816d7988)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff8170d9ce)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff8171dfb1)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8172ea1e)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81779eb0)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817869b4)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba8fd)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff817fb00a)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81802915)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81862566)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81867001)
Location: include/linux/pm_runtime.h:264
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81869e91)
Location: include/linux/pm_runtime.h:264
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8153d3de)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81553055)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81557468)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff81696ef2)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff816e9d45)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816ec61e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff81712d88)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff81749224)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff817596e1)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8176a20f)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff817b7b06)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817c4ea7)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa230)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183bc6a)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81844526)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff818a66b8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818aae53)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818adca1)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8155e1ee)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815746f5)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81578a98)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff816b9a82)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff8170dda5)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8171068e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff81737088)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff8176d374)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d601)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8178e26f)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff817e82d6)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817f5847)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b070)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186d5fa)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875e76)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff818d8b18)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818dd2a3)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0148)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff81600c3e)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8161daa8)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff8176de6a)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff817c96b5)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff817cbc67)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4bd8)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff8182f93e)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840a71)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff81853e3f)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff818b77f5)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818c5be7)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f5dbc)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fcce8)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8194157a)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a135)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/mmc.c (ffffffff819ab7e8)
Location: include/linux/pm_runtime.h:275
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819b0393)
Location: include/linux/pm_runtime.h:275
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff819b31c8)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9657)
Location: include/linux/pm_runtime.h:275
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_free
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
In drivers/phy/phy-core.c (ffffffff81625b2e)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff816442c8)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff8178882a)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff817de1c3)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff817e06d7)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff81808728)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff81c16450)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff81850fb1)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff8186410f)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff818c6105)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818d1ab7)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818fe96c)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81905618)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8194794a)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fcc5)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/mmc.c (ffffffff819ae398)
Location: include/linux/pm_runtime.h:524
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819b2903)
Location: include/linux/pm_runtime.h:524
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff819b571e)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff816095ee)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81627028)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff8176c17a)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff817c25c3)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/base/power/main.c (ffffffff817c5280)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed288)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff81c0815a)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff81834041)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff81846d6f)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff818a9441)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818b50d7)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e20bc)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e8e08)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192b25a)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933b85)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/mmc.c (ffffffff819929c8)
Location: include/linux/pm_runtime.h:524
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819970e3)
Location: include/linux/pm_runtime.h:524
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81999c9a)
Location: include/linux/pm_runtime.h:524
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8167826e)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff816968e5)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff817f1946)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff8184c373)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/main.c (ffffffff8184f664)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/scsi/hosts.c (ffffffff81d0bfde)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c0041)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
```
In drivers/ata/libata-core.c (ffffffff818d318f)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff8193e34e)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8194a657)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e2bf)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819851f8)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce42c)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d6fa5)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3e4c8)
Location: include/linux/pm_runtime.h:534
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81a434b3)
Location: include/linux/pm_runtime.h:534
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81a4643a)
Location: include/linux/pm_runtime.h:534
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8179352d)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff817b77f5)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff8193206c)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff81991d34)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/main.c (ffffffff8199469b)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/scsi/hosts.c (ffffffff81ed4f16)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/ata/libata-core.c (ffffffff81a238be)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81a9635d)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81aa3317)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ad99cc)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae0e47)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2fed0)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39bd5)
Location: include/linux/pm_runtime.h:563
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81bab7ee)
Location: include/linux/pm_runtime.h:563
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81bb0ed9)
Location: include/linux/pm_runtime.h:563
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb419e)
Location: include/linux/pm_runtime.h:563
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff818a815d)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff818d1fb5)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff81a90ac4)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff81b021d4)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/main.c (ffffffff81b050bb)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/scsi/hosts.c (ffffffff81b76eea)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/ata/libata-core.c (ffffffff81ba575e)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81c18d67)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c28e67)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c64aec)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c69e)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4470)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf535)
Location: include/linux/pm_runtime.h:567
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81d4ebce)
Location: include/linux/pm_runtime.h:567
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81d54d59)
Location: include/linux/pm_runtime.h:567
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81d587f7)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff818eaf9d)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81914fb5)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serial/serial_ctrl.c (ffffffff81ac44b5)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/tty/serial/serial_ctrl.c:serial_ctrl_remove
```
```
In drivers/tty/serial/serial_port.c (ffffffff81ac4644)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_remove
```
```
In drivers/tty/serdev/core.c (ffffffff81adc2d4)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff81b502c4)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/main.c (ffffffff81b52994)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/scsi/hosts.c (ffffffff81bcab7a)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/ata/libata-core.c (ffffffff81bfbdae)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81c7fd3e)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c8fe37)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccbefc)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3c8e)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c0e0)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d37605)
Location: include/linux/pm_runtime.h:567
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81db94de)
Location: include/linux/pm_runtime.h:567
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81dbf6d9)
Location: include/linux/pm_runtime.h:567
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3187)
Location: include/linux/pm_runtime.h:567
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff819324dd)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8195cf25)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serial/serial_ctrl.c (ffffffff81b173b5)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/tty/serial/serial_ctrl.c:serial_ctrl_remove
```
```
In drivers/tty/serial/serial_port.c (ffffffff81b17544)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/tty/serial/serial_port.c:serial_port_remove
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f5ba)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff81ba8844)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
```
In drivers/base/power/main.c (ffffffff81bab044)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7aa)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81d3475f)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81d449e7)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d80ddc)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88c4e)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de1fa0)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded885)
Location: include/linux/pm_runtime.h:565
Inline: True
```
```
In drivers/mmc/core/mmc.c (ffffffff81e71ade)
Location: include/linux/pm_runtime.h:565
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81e77de9)
Location: include/linux/pm_runtime.h:565
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7ba64)
Location: include/linux/pm_runtime.h:565
Inline: True
Inline callers:
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
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676714)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/bus/simple-pm-bus.c (ffff800010685b58)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
```
```
In drivers/phy/phy-core.c (ffff800010686cc8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d688)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071df30)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721d8c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072af08)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff8000114b9208)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_remove
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff800010734590)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/amba/bus.c (ffff8000107b9578)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb544)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108915e0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d68)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serial/8250/8250_of.c (ffff800010892ef4)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serdev/core.c (ffff8000108a9bc8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d8034)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd5d8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffff800010900dd8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffff800010931e30)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffff80001096fa28)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffff8000109837c8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffff800010999344)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libahci_platform.c (ffff8000109bcf8c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ccc1c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e67f4)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hub.c (ffff800010a17668)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffff800010a2677c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffff800010ab09a8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010abad18)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abaf3c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca88)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/mmc/core/mmc.c (ffff800010b331f4)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffff800010b37568)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a310)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/block.c (ffff800010b41734)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/memory/mtk-smi.c (ffff800010b8bbe8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_remove
  - drivers/memory/mtk-smi.c:mtk_smi_larb_remove
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
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ee18)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fa6c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/bus/simple-pm-bus.c (c0826a14)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
```
```
In drivers/bus/ti-sysc.c (c08293e8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/phy/phy-core.c (c082a9e8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-omap.c (c086cb20)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_remove
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/pwm/pwm-tipwmss.c (c0876bc0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pwm/pwm-tipwmss.c:pwmss_remove
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6714)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a6e40)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08aac30)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-rcar.c (c08af0dc)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b647c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c08ba46c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_shutdown
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bd260)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/amba/bus.c (c08e5ef8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904a40)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
```
```
In drivers/clk/tegra/clk-dfll.c (c090c8a8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister
```
```
In drivers/dma/tegra20-apb-dma.c (c0929ec0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_remove
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098dd48)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serial/8250/8250_of.c (c098e26c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/tty/serial/omap-serial.c (c099ed54)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/tty/serdev/core.c (c09a61b8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/iommu/omap-iommu.c (c09c342c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_remove
```
```
In drivers/iommu/rockchip-iommu.c (c09c5ac8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
```
```
In drivers/base/power/runtime.c (c09e893c)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (c09eafec)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (c0a15a24)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/mfd/omap-usb-host.c (c0a34974)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_remove
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a35c24)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_remove
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/scsi/hosts.c (c0a44ca8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (c0a56080)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (c0a67948)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/ata/libahci_platform.c (c0a87cc4)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aad01c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_remove
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab5e28)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac94c0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfc10)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_remove
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4354)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
```
```
In drivers/usb/core/hub.c (c0aef728)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c0afc894)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/musb/musb_core.c (c0b65554)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
```
```
In drivers/rtc/rtc-omap.c (c0b8c434)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/i2c/i2c-core-base.c (c0b91ee4)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b9a10c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c3d8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c848)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/i2c/busses/i2c-s3c2410.c (c0b9e204)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_remove
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba91b8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/mmc.c (c0c0dc3c)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (c0c11ed8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (c0c14d10)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/block.c (c0c1c534)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a99c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e3b8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47484)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_remove
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
```
```
In drivers/memory/omap-gpmc.c (c0c6f6d0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_remove
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/memory/mtk-smi.c (c0c72ce8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_common_remove
  - drivers/memory/mtk-smi.c:mtk_smi_larb_remove
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
In drivers/bus/simple-pm-bus.c (c0000000008209d8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
```
```
In drivers/phy/phy-core.c (c0000000008217f8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088e514)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f034)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093ae04)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serdev/core.c (c000000000941574)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (c000000000999f14)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (c00000000099e7e0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (c0000000009d3140)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (c000000000a290e0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (c000000000a40324)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (c000000000a5a1dc)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (c000000000ad036c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c000000000ae1f30)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (c000000000b93bc8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9e170)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (c000000000c2d6c0)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (c000000000c32cf0)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (c000000000c36c10)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
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
In drivers/bus/simple-pm-bus.c (ffffffe000495d48)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
```
```
In drivers/phy/phy-core.c (ffffffe000496696)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e43f4)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e4fde)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559a22)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/tty/serdev/core.c (ffffffe00055f34c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffe00058c2d6)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a85b2)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffe0005d9a02)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/ata/libata-core.c (ffffffe0005f86e2)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffe00063c4d6)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffe000648664)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b8ae0)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf508)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffe00070b90c)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffe00070f4e0)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffe000711eba)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/block.c (ffffffe000718642)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
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
In drivers/phy/phy-core.c (ffffffff815567de)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/tty/serdev/core.c (ffffffff8167f4e2)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff816d34f5)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816d6935)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff816fade8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff81721a64)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff81731cf1)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff817533ff)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff817a06b6)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817adc27)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e3450)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff8187c4d8)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81880c63)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81883b08)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff81546c9e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155ad05)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/base/power/runtime.c (ffffffff816ae7b5)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b1072)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff816cebf8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff816fae94)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b111)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8173329f)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff81792483)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8179f627)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/phy/phy-core.c (ffffffff8155251e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568a25)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff8156c7e8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff816ad8c2)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff81701a65)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8170434e)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff8172a548)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff81760834)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770ac1)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff817830ef)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff817dd156)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817ea6c7)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181fef0)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186178a)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b326)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff818cd978)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818d2103)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818d4fa8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
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
In drivers/phy/phy-core.c (ffffffff8156c3ae)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_consume
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582945)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
```
```
In drivers/pwm/pwm-lpss-platform.c (ffffffff81586ce8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
```
```
In drivers/tty/serdev/core.c (ffffffff816c7d22)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_controller_add
```
```
In drivers/base/power/runtime.c (ffffffff8171c6c5)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8171e43c)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/base/power/main.c:__device_suspend
```
```
In drivers/mfd/arizona-core.c (ffffffff81745988)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
```
In drivers/scsi/hosts.c (ffffffff8177be94)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c261)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8179cfaf)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_port_pm_resume
```
```
In drivers/usb/core/hub.c (ffffffff817f7426)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81804907)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839e60)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187c99a)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818852b6)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
```
In drivers/mmc/core/mmc.c (ffffffff818ea498)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818eec23)
Location: include/linux/pm_runtime.h:265
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1ac8)
Location: include/linux/pm_runtime.h:265
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
</details>
</li>
</ul>

## Differences
