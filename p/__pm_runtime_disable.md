# Function: <code>__pm_runtime_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81557c00)
Location: drivers/base/power/runtime.c:1168
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_remove
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/base/power/main.c:__device_suspend
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81557c00-ffffffff81557d2a: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9cc0)
Location: drivers/base/power/runtime.c:1172
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815a9cc0-ffffffff815a9dd2: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d8090)
Location: drivers/base/power/runtime.c:1260
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815d8090-ffffffff815d81a2: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ecfd0)
Location: drivers/base/power/runtime.c:1260
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff815ecfd0-ffffffff815ed0c0: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654380)
Location: drivers/base/power/runtime.c:1245
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81654380-ffffffff81654470: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168f9d0)
Location: drivers/base/power/runtime.c:1245
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8168f9d0-ffffffff8168faac: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816afd60)
Location: drivers/base/power/runtime.c:1252
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816afd60-ffffffff816afe3c: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e9c40)
Location: drivers/base/power/runtime.c:1328
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816e9c40-ffffffff816e9d37: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170dca0)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8170dca0-ffffffff8170dd97: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c8f60)
Location: drivers/base/power/runtime.c:1351
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_free
```
**Symbols:**

```
ffffffff817c8f60-ffffffff817c9092: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817ddd30)
Location: drivers/base/power/runtime.c:1383
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff817ddd30-ffffffff817dde62: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c20b0)
Location: drivers/base/power/runtime.c:1383
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff817c20b0-ffffffff817c21e2: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184ba10)
Location: drivers/base/power/runtime.c:1402
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8184ba10-ffffffff8184bb42: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81991470)
Location: drivers/base/power/runtime.c:1431
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81991470-ffffffff819915db: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01820)
Location: drivers/base/power/runtime.c:1444
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81b01820-ffffffff81b0198b: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4f950)
Location: drivers/base/power/runtime.c:1444
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serial/serial_ctrl.c:serial_ctrl_remove
  - drivers/tty/serial/serial_port.c:serial_port_remove
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81b4f950-ffffffff81b4fabb: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7ed0)
Location: drivers/base/power/runtime.c:1445
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serial/serial_ctrl.c:serial_ctrl_remove
  - drivers/tty/serial/serial_port.c:serial_port_remove
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ehci-platform.c:ehci_platform_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_resume_common
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81ba7ed0-ffffffff81ba803b: __pm_runtime_disable (STB_GLOBAL)
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
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fd430)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_remove
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/memory/mtk-smi.c:mtk_smi_common_remove
  - drivers/memory/mtk-smi.c:mtk_smi_larb_remove
```
**Symbols:**

```
ffff8000108fd430-ffff8000108fd5bc: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e8814)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-omap.c:omap_gpio_remove
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/pwm/pwm-tipwmss.c:pwmss_remove
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_shutdown
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/tegra/clk-dfll.c:tegra_dfll_unregister
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_remove
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/omap-iommu.c:omap_iommu_remove
  - drivers/iommu/rockchip-iommu.c:rk_iommu_probe
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/mfd/omap-usb-host.c:usbhs_omap_remove
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_remove
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
  - drivers/mtd/nand/raw/omap_elm.c:elm_remove
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_remove
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_remove
  - drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_remove
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
  - drivers/memory/omap-gpmc.c:gpmc_remove
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/mtk-smi.c:mtk_smi_common_remove
  - drivers/memory/mtk-smi.c:mtk_smi_larb_remove
```
**Symbols:**

```
c09e8814-c09e8928: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999d40)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
c000000000999d40-c000000000999eec: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058c1ac)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/bus/simple-pm-bus.c:simple_pm_bus_remove
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/block.c:mmc_blk_remove
```
**Symbols:**

```
ffffffe00058c1ac-ffffffe00058c2be: __pm_runtime_disable (STB_GLOBAL)
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
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d33f0)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff816d33f0-ffffffff816d34e7: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816ae6c0)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff816ae6c0-ffffffff816ae7ad: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81701960)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff81701960-ffffffff81701a57: __pm_runtime_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __pm_runtime_disable(struct device *dev, bool check_resume);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171c5c0)
Location: drivers/base/power/runtime.c:1330
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_consume
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_remove
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_remove_platform
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/main.c:__device_suspend
  - drivers/base/power/main.c:__device_suspend_late
  - drivers/mfd/arizona-core.c:arizona_dev_exit
  - drivers/mfd/arizona-core.c:arizona_dev_init
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
  - drivers/ata/libata-core.c:ata_port_pm_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/driver.c:usb_resume
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/ohci-platform.c:ohci_platform_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
**Symbols:**

```
ffffffff8171c5c0-ffffffff8171c6c0: __pm_runtime_disable (STB_GLOBAL)
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
