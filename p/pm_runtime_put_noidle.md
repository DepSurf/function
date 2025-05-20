# Function: <code>pm_runtime_put_noidle</code>

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
In drivers/phy/phy-core.c (ffffffff8141bd33)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429f85)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/pci/pci-driver.c (ffffffff8143a719)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/power/runtime.c (ffffffff81557bac)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__pm_runtime_disable
```
```
In drivers/usb/core/hcd.c (ffffffff8160c35a)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81613c12)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8161fbd2)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81662403)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9c3a)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816ca761)
Location: include/linux/pm_runtime.h:70
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
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
In kernel/irq/chip.c (ffffffff810e4487)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81464393)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81486639)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/power/runtime.c (ffffffff815a9d6f)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
```
```
In drivers/usb/core/hcd.c (ffffffff8166bf24)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816740f9)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81680567)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816c2633)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8172cc0a)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172d711)
Location: include/linux/pm_runtime.h:75
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
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
In kernel/irq/chip.c (ffffffff810ead27)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81483693)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814a7df9)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/core.c (ffffffff815c807d)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff815d85b8)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff8162f5da)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hcd.c (ffffffff81699c24)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816a1d89)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816ae297)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff816f05f3)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8175ebd8)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817606d1)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
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
In kernel/irq/chip.c (ffffffff810ea3ff)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8148d91b)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814b1da9)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/core.c (ffffffff815dcd16)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff815ecb88)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff816446a5)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hcd.c (ffffffff816af636)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816b7602)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff816c3cf1)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81705f21)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726f9f)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e4d8)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f2cc)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
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
In kernel/irq/chip.c (ffffffff810f290f)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff814c9a7b)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814f148e)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/core.c (ffffffff81643d16)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff81653f38)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff816ad638)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hcd.c (ffffffff8171ac92)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81722ec2)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8172fad1)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817770f1)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817985ef)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81798908)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4a7a)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f5881)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811984)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff810fad0f)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff814f9d85)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8152167e)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/core.c (ffffffff8167f13d)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81690206)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff816e9f78)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817335fc)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff81758ff1)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8176105f)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8176e2ee)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817b7da3)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817db302)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db58e)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cf6a)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ed65)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b533)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff811064cf)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8150e955)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff815374ae)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffff8166104b)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff8169f587)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816b0866)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/scsi/hosts.c (ffffffff8170d9e8)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff8175607a)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff8177d561)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8178561f)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8179296e)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817de497)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818021d2)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8180293e)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81868efa)
Location: include/linux/pm_runtime.h:74
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186ad15)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187aa33)
Location: include/linux/pm_runtime.h:74
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff8110fa5a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8153df47)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81566dfe)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffff816971b4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816d7d3f)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ea48d)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff8174923e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817921a6)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff817bc486)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817c439b)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817d1aac)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8181ef27)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843a1e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81843eb8)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818add4b)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aec24)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0a89)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff8111bd1a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8155ed67)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8158815e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffff816b9d64)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816fbd0a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8170e4ed)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff8176d38e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817b5d77)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff817ecca6)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817f4d3b)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff8180297c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818503e7)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8187539f)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875828)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818e01fb)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e10d0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f34eb)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pm_runtime_put_noidle(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8112804d)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff815ffeca)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8162ee9e)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff816fcae2)
Location: include/linux/pm_runtime.h:78
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8176d9e4)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff817b55d2)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c9e9d)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff8182f958)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81877d10)
Location: include/linux/pm_runtime.h:78
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff818bbab6)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818c41de)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818d2910)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819499a0)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a15c)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/sdio.c (ffffffff819b3283)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b41d0)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8dd2)
Location: include/linux/pm_runtime.h:78
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81877d10-ffffffff81877d28: pm_runtime_put_noidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pm_runtime_put_noidle(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123b5d)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81624dba)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8165455e)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff81719a22)
Location: include/linux/pm_runtime.h:103
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff817883c4)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff817c9d7e)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817dde37)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81c1646a)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81886520)
Location: include/linux/pm_runtime.h:103
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8188bee8)
Location: include/linux/pm_runtime.h:103
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffff818c8896)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818d00ce)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818dcd00)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f560)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fcec)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/sdio.c (ffffffff819b57d3)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b6820)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81c2dbc6)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81886520-ffffffff81886538: pm_runtime_put_noidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pm_runtime_put_noidle(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123ebd)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8160876a)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81636f0e)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff816fad22)
Location: include/linux/pm_runtime.h:103
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8176bd14)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff817ad596)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817c21b7)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/mfd/arizona-irq.c (ffffffff817ee0ab)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/hosts.c (ffffffff81c08174)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81868d90)
Location: include/linux/pm_runtime.h:103
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8186e848)
Location: include/linux/pm_runtime.h:103
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818a9dd9)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff818abed6)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818b36fe)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff818c0070)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819339f3)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933bac)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/sdio.c (ffffffff81999e63)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199afd0)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81c1fd75)
Location: include/linux/pm_runtime.h:103
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81868d90-ffffffff81868da8: pm_runtime_put_noidle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void pm_runtime_put_noidle(struct device *dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8114449d)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff816773aa)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff816a714e)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff81775712)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff817f1444)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81836847)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8184bb17)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:pm_runtime_release_supplier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81d0bff8)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff818f8940)
Location: include/linux/pm_runtime.h:106
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff818fe956)
Location: include/linux/pm_runtime.h:106
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8193ece9)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81940f5b)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81948b8e)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff819566f5)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81994ef8)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6dc3)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d6fdc)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_pm_cleanup
```
```
In drivers/mmc/core/sdio.c (ffffffff81a4667f)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a4790e)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d316d7)
Location: include/linux/pm_runtime.h:106
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff818f8940-ffffffff818f8958: pm_runtime_put_noidle (STB_LOCAL)
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
In kernel/irq/chip.c (ffffffff81167f04)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81792434)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff817c9bd9)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff818aba53)
Location: include/linux/pm_runtime.h:136
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81931a50)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81978856)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff819915b2)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81ed4f30)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81a4d711)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81a502bc)
Location: include/linux/pm_runtime.h:136
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a810b5)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
```
In drivers/usb/core/hub.c (ffffffff81a96dc1)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81a99379)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81aa16cc)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81ab0306)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81af1b8b)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b39971)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39c1a)
Location: include/linux/pm_runtime.h:136
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb4325)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5897)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81efdb9c)
Location: include/linux/pm_runtime.h:136
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff8119c3b4)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff818a6e54)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff818e7609)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff819f7153)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81a903d0)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81ae5015)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b01962)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81b76f04)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81bd7b24)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81bd942c)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c19967)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d349)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c26f5c)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c38404)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81c7ed55)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf069)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf57a)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81d58985)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a0fe)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d7533a)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff811ae204)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff818e9cc4)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac29)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff81a3f353)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf3e2)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81adbbe0)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81b3352b)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81b4fa92)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81bcab94)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81c2e547)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fe2c)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c80987)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81c84248)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81c8df1c)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81c9f7c4)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81ce5fd5)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d3712e)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d3764a)
Location: include/linux/pm_runtime.h:140
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3315)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a9e)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de327a)
Location: include/linux/pm_runtime.h:140
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff811bde04)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81931164)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff819734b9)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/clk/clk.c (ffffffff81a8ac83)
Location: include/linux/pm_runtime.h:138
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b12217)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/tty/serdev/core.c (ffffffff81b2ef40)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81b8ae6a)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/power/runtime.c (ffffffff81ba8012)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:__rpm_put_suppliers
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7c4)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff81ce0f97)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2cec)
Location: include/linux/pm_runtime.h:138
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d35357)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/hcd.c (ffffffff81d38c48)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff81d42a3c)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81d5441b)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff81d9b085)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded366)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe_master
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded8ca)
Location: include/linux/pm_runtime.h:138
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7bbf5)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d37e)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e9936a)
Location: include/linux/pm_runtime.h:138
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffff800010180120)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffff8000106879c8)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106ec538)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/amba/bus.c (ffff8000107b9540)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff8000108915ec)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d74)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serdev/core.c (ffff8000108a9fe8)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffff8000108e6608)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffff8000108fe0d0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffff80001096fa40)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffff8000109c95ec)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cdab4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e67c0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/usb/core/hcd.c (ffff800010a1c358)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffff800010a2592c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffff800010a3713c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffff800010a90f30)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010aba1f4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010aba65c)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca54)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a404)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b214)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffff800010b41740)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e9cc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (c03d0170)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/bus/ti-sysc.c (c0829418)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/phy/phy-core.c (c082b580)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (c0887864)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/amba/bus.c (c08e5ec0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098dd54)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serdev/core.c (c09a64bc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/omap-iommu.c (c09c4858)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
```
```
In drivers/base/core.c (c09d4c84)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (c09e8c3c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (c0a44cb8)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (c0ab3018)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7f68)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac9484)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_probe
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0ad04ac)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad4368)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adaf14)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin
```
```
In drivers/usb/core/hcd.c (c0af3b30)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (c0afbf20)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (c0b0a590)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (c0b633a0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/usb/musb/musb_core.c (c0b668b4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_suspend
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f91c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b99820)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b99c34)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c3a0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/power/avs/smartreflex.c (c0ba93f8)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
```
```
In drivers/mmc/core/sdio.c (c0c14e04)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (c0c15d44)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (c0c1c540)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/host/sdhci.c (c0c25c74)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_set_power_noreg
  - drivers/mmc/host/sdhci.c:sdhci_reset
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e3c4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47818)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c62658)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (c0000000001dacd0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (c000000000820d38)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (c00000000086817c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (c0000000009408f8)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (c00000000097c358)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (c00000000099b380)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (c000000000a29100)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (c000000000a8b218)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (c000000000ad47b4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (c000000000ae0198)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (c000000000af4b34)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (c000000000b6c688)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d2dc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9dbf8)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio.c (c000000000c353f0)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (c000000000c37998)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a530)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffe00011835c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffe000495fee)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffe0004c15fa)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffe00055eae4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffe00057aede)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffe00058cab8)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffe0005d9a1a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffe0006196bc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffe00063f830)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffe000647420)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffe000653ba4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffe0006a3982)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006be9fc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf112)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffe000710f52)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe000712772)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffffffe00071864e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072ca42)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff811142fa)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81557357)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157bfee)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffff8167f7c4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816c14fa)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816d3c3d)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff81721a7e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff8177a857)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff817a5086)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817ad11b)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817bad5c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff818061b7)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/mmc/core/sdio.c (ffffffff81883bbb)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884a90)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8189481b)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff8110500a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81547817)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8156adbe)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/base/core.c (ffffffff8169c7aa)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff816aeedd)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff816faeae)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff8175a607)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff81796b96)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff8179eb1b)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817ac77c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci.c (ffffffff817b5d1e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
```
```
In drivers/usb/host/xhci-pci.c (ffffffff817cd937)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184ccf5)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff811121ea)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff81553097)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157beae)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffff816adba4)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816ef9ca)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff817021ad)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff8176084e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817aabf7)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff817e1b26)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff817e9bbb)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff817f77fc)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff81845267)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a84f)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186acd8)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818d505b)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5f30)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e831b)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff8111d80a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8156cf27)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8159635e)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/tty/serdev/core.c (ffffffff816c8004)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff8170a20a)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/power/runtime.c (ffffffff8171c9cd)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_clean_up_links
  - drivers/base/power/runtime.c:__pm_runtime_disable
  - drivers/base/power/runtime.c:pm_runtime_barrier
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/scsi/hosts.c (ffffffff8177beae)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/spi/spi.c (ffffffff817c4b71)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hcd.c (ffffffff817fbf16)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_end_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff818040eb)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
```
```
In drivers/usb/core/hcd-pci.c (ffffffff81811a3c)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/core/hcd-pci.c:usb_hcd_pci_probe
```
```
In drivers/usb/host/xhci-pci.c (ffffffff8185f7e7)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
  - drivers/usb/host/xhci-pci.c:xhci_pci_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818847df)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81884c68)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1b7b)
Location: include/linux/pm_runtime.h:73
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a50)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904f83)
Location: include/linux/pm_runtime.h:73
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
