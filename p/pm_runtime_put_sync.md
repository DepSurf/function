# Function: <code>pm_runtime_put_sync</code>

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
In drivers/phy/phy-core.c (ffffffff8141be47)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff81437343)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff81439494)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/dd.c (ffffffff8154b662)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
```
```
In drivers/mfd/arizona-core.c (ffffffff8157c9ae)
Location: include/linux/pm_runtime.h:242
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff815b8d70)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
```
```
In drivers/usb/core/hub.c (ffffffff81608d65)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_event
```
```
In drivers/usb/core/driver.c (ffffffff816140c2)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9c94)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816ca795)
Location: include/linux/pm_runtime.h:242
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff814644a7)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff81482f03)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff8148666d)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/base/dd.c (ffffffff8159d352)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
```
```
In drivers/mfd/arizona-core.c (ffffffff815d1a56)
Location: include/linux/pm_runtime.h:248
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81611cad)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff8166a355)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff8167400c)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/mmc/core/sdio.c (ffffffff8172cc64)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172d745)
Location: include/linux/pm_runtime.h:248
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff814837a7)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff814a4493)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff814a7e2d)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815a3058)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/base/dd.c (ffffffff815cc3e6)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff815fdea7)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff8164153d)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81698085)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff816a1c9c)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/mmc/core/sdio.c (ffffffff8175ec32)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760705)
Location: include/linux/pm_runtime.h:251
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff8148cd91)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff814ae553)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff814b1dd7)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6be5)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/base/dd.c (ffffffff815e0f99)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff81611cd2)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff81655e0d)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff816ad9bc)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff816b6c5c)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e74b1)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817271d6)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e52c)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f2fa)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff814c8e61)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff814ed923)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff814f14bc)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff815abd48)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d956)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/base/dd.c (ffffffff816480a9)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff8167a542)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff816bf3bd)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81718a1e)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff817224ec)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753cde)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772c3f)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81799059)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4ad0)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f58af)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff814f9e43)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff8151d583)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff815216b4)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff815e3ccf)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff816835ba)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff816b5f9d)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff816fb9d5)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81757c0b)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff8176114c)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81794320)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b32e2)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db609)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cfc6)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ed93)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff8150ea13)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff81532c83)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff815374e4)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff815fe0af)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff816a32bd)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff816d71fd)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff8171e3b5)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff8177c17b)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff8178574c)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba8f0)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d98e4)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818029b9)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81868f56)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186ad43)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff8153d0b3)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff815623d5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff81566e32)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff8162f660)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff816dc0f4)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff817129f1)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff81759aa5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff817b9abe)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff817c3c52)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa223)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a255)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81844519)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818add93)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aec50)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff8155dec3)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff81583575)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff81588192)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff81651a1e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff81700124)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff81736cf1)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d9b5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff817ea30e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff817f4712)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b063)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184b5f5)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875e69)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0243)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e10fc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/keyslot-manager.c (ffffffff8158172f)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff815fff83)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
```
```
In drivers/pci/pci.c (ffffffff8162a135)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff8162eed2)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff81700dbc)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81763581)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff817b8fbc)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4321)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840f25)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff818b9743)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff818c42e2)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fcf03)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191df65)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819417d8)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a1c9)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff819b332d)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b41fc)
Location: include/linux/pm_runtime.h:250
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/keyslot-manager.c (ffffffff8159e75f)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff81624e73)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
```
```
In drivers/pci/pci.c (ffffffff81650595)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff81654592)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff8171e2dc)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177e5e1)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff817cdd36)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
```
```
In drivers/mfd/arizona-core.c (ffffffff818086d1)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff81851445)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff818c8023)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff818d01d2)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81905833)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925e77)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81947c23)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fd59)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff819b587d)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b684c)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/keyslot-manager.c (ffffffff815a54d0)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff81608823)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
```
```
In drivers/pci/pci.c (ffffffff81633145)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff81636f42)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff816ff27b)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761f31)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff817b1746)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed231)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff818344d5)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff818ab690)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff818b37ff)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e9023)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909567)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192b58a)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933c19)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81999f0b)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199affc)
Location: include/linux/pm_runtime.h:448
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/keyslot-manager.c (ffffffff8160dfa0)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff81677463)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
```
```
In drivers/pci/pci.c (ffffffff816a32b5)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff816a7182)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff81779846)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5f91)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff8183a9cc)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c04d5)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81940610)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81948c8f)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819854ac)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9de7)
Location: include/linux/pm_runtime.h:458
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce767)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d7049)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81a4674c)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a4793a)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/blk-crypto-profile.c (ffffffff816c2ac0)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff81793a09)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
```
```
In drivers/pci/pci.c (ffffffff817c54c4)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff817c9c08)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff818afbd8)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff819254b1)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff8197e59d)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/scsi/scsi_pm.c (ffffffff81a0cb35)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81a9873c)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81aa17f7)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae114c)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07d67)
Location: include/linux/pm_runtime.h:487
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b30456)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39c9f)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb430b)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb58be)
Location: include/linux/pm_runtime.h:487
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/blk-crypto-profile.c (ffffffff81783e50)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff818a86e5)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pci/pci.c (ffffffff818e2594)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff818e7638)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff819fbebc)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81df1)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff81aebb0d)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/scsi/scsi_pm.c (ffffffff81b8c8c5)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81c1b5fd)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81c270d7)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6ca3c)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c976ab)
Location: include/linux/pm_runtime.h:491
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4bed)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf60f)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81d5896b)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a125)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/blk-crypto-profile.c (ffffffff817c4130)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff818eb5d5)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pci/pci.c (ffffffff819259d4)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac58)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff81a44a4e)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acd3f1)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff81b39d66)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/scsi/scsi_pm.c (ffffffff81be08d5)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81c82522)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81c8e097)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd402d)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe9d4)
Location: include/linux/pm_runtime.h:491
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c52c)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d376df)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc32fb)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4ac5)
Location: include/linux/pm_runtime.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In block/blk-crypto-profile.c (ffffffff81808dc0)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff81932b15)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pci/pci.c (ffffffff8196e154)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff819734e8)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff81a9055e)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_hw_is_prepared
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b204c1)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_exit
```
```
In drivers/base/dd.c (ffffffff81b91826)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/scsi/scsi_pm.c (ffffffff81c35905)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81d36e62)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81d42bb7)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88fed)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db49f4)
Location: include/linux/pm_runtime.h:489
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de23fc)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded95f)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bbdb)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d3a5)
Location: include/linux/pm_runtime.h:489
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffff800010686380)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffff8000106e7524)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffff8000106ec580)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d680)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071df28)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072aefc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/clk/clk.c (ffff8000107c27b0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/tty/serial/8250/8250_of.c (ffff800010892e64)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108daa30)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_flush_iotlb_all
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
```
```
In drivers/base/dd.c (ffff8000108eb460)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffff800010931680)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffff800010983d00)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/ata/libahci_platform.c (ffff8000109bcf80)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ccc10)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/usb/core/hub.c (ffff800010a19b18)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffff800010a2522c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8a9e4)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010abad0c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abaf30)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a3b0)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b258)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
```
In drivers/memory/mtk-smi.c (ffff800010b8bb3c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_larb_suspend
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_put
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
In drivers/bus/ti-sysc.c (c08293dc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/phy/phy-core.c (c082a1d0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/gpio/gpio-omap.c (c086d958)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
```
```
In drivers/pci/pci.c (c0882638)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (c08878b8)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6700)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a6e2c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08aac24)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_remove
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b6470)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_subsys_powerdown
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c08ba458)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_shutdown
```
```
In drivers/clk/clk.c (c08e9508)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c1585384)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe
```
```
In drivers/clk/tegra/clk-dfll.c (c090c3b4)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_disable
```
```
In drivers/clk/ti/clk-dra7-atl.c (c091ac40)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/clk-dra7-atl.c:atl_clk_disable
```
```
In drivers/tty/serial/8250/8250_of.c (c098e1f0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/tty/serial/omap-serial.c (c099ed48)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
```
In drivers/iommu/omap-iommu.c (c09c2b48)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_domain_deactivate
  - drivers/iommu/omap-iommu.c:omap_iommu_detach
  - drivers/iommu/omap-iommu.c:flush_iotlb_all
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
```
```
In drivers/iommu/qcom_iommu.c (c09cbca0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_flush_iotlb_all
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
```
```
In drivers/base/dd.c (c09d954c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (c0a14764)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/omap-usb-host.c (c0a34cd0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a35b84)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:omap_tll_disable
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/scsi/scsi_pm.c (c0a56484)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/ata/libahci_platform.c (c0a87cbc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_put_resources
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aacf20)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_suspend
  - drivers/mtd/nand/raw/omap_elm.c:elm_remove
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab5e1c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4348)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
```
```
In drivers/usb/core/hub.c (c0af1dd0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (c0afb884)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5d688)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/usb/musb/musb_core.c (c0b65548)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:vbus_show
```
```
In drivers/rtc/rtc-omap.c (c0b8c428)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b9a100)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c83c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba945c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:omap_sr_probe
```
```
In drivers/mmc/core/sdio.c (c0c14de8)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (c0c15d94)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2a928)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
```
```
In drivers/clocksource/timer-ti-dm.c (c0c486fc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_disable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_int_enable
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_prescaler
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_pwm
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_match
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_set_load
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_stop
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
  - drivers/clocksource/timer-ti-dm.c:_omap_dm_timer_request
```
```
In drivers/memory/omap-gpmc.c (c0c71814)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_suspend
  - drivers/memory/omap-gpmc.c:gpmc_remove
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/memory/mtk-smi.c (c0c72acc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_larb_suspend
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_put
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
In drivers/phy/phy-core.c (c000000000820ea0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (c000000000861cbc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (c0000000008681cc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088e500)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f020)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093ad38)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_suspend
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/base/dd.c (c000000000982a8c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (c0000000009d1e90)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
```
```
In drivers/scsi/scsi_pm.c (c000000000a4093c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (c000000000ad30a0)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (c000000000ae0440)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b65fb4)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9e160)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (c000000000c35480)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (c000000000c379dc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffe0004960ba)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffe0004bdc96)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffe0004c1630)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e43e2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_shutdown
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e4fcc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_shutdown
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/clk/clk.c (ffffffe00051016a)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559a16)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_remove
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
```
In drivers/base/dd.c (ffffffe00057f0b8)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a7a44)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffe0005e8ca8)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffe00063e65e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffe0006475b8)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f5e6)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf4fc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffe000710efc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe0007127a2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff815564b3)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff81577a95)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff8157c022)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff81617a7e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff816c5914)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff816faa51)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff817320a5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff817a26ee)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff817acaf2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e3443)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81883c03)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884abc)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff81546973)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff815661d5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff8156adf2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff8160bfae)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff816a0b94)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff816ce861)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b4c5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff8179452e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff8179e4f2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8b45)
Location: include/linux/pm_runtime.h:240
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
In drivers/phy/phy-core.c (ffffffff815521f3)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff815772c5)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff8157bee2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff8164585e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff816f3de4)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff8172a1b1)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770e75)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff817df18e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff817e9592)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181fee3)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840475)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b319)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818d50a3)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5f5c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
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
In drivers/phy/phy-core.c (ffffffff8156c083)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff81591785)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-driver.c (ffffffff81596392)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/clk/clk.c (ffffffff8165fdee)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/clk/clk.c:clk_core_unprepare
```
```
In drivers/base/dd.c (ffffffff8170e614)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
```
```
In drivers/mfd/arizona-core.c (ffffffff817455f1)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_disable
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c615)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_put_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff817f947e)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81803ac2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839e53)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185a945)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818852a9)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1bc3)
Location: include/linux/pm_runtime.h:240
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a7c)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
```
</details>
</li>
</ul>

## Differences
