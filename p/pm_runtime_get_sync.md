# Function: <code>pm_runtime_get_sync</code>

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
In drivers/phy/phy-core.c (ffffffff8141be2b)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/pci.c (ffffffff814372e2)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81439426)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-driver.c:pci_device_remove
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814520b0)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81507616)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81540e87)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/base/dd.c (ffffffff8154b41a)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815550c6)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
```
```
In drivers/base/power/runtime.c (ffffffff81557457)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156b7ac)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff8157c1f6)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff8157e1f1)
Location: include/linux/pm_runtime.h:226
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff815b8d46)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
```
```
In drivers/spi/spi.c (ffffffff815e7ed5)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81607f2d)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_resume
```
```
In drivers/usb/core/driver.c (ffffffff816140e6)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff8161eca1)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_hub_remove_port_device
```
```
In drivers/mmc/core/core.c (ffffffff816bdc8c)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_get_card
```
```
In drivers/mmc/core/sdio.c (ffffffff816c9bf5)
Location: include/linux/pm_runtime.h:226
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816ca7b5)
Location: include/linux/pm_runtime.h:226
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
In kernel/irq/chip.c (ffffffff810e4469)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8146448b)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffff8147dc8a)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81482ea2)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81486628)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149ec28)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8155ae2a)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
```
```
In drivers/base/dd.c (ffffffff8159d316)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815a7d5d)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff815a94a7)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c04db)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff815d12be)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d34ba)
Location: include/linux/pm_runtime.h:232
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81611c56)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81641e01)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff81646861)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81668cf6)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81673fd6)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff8168009f)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/mmc/core/core.c (ffffffff8171f8e6)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff8172cbc5)
Location: include/linux/pm_runtime.h:232
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172d765)
Location: include/linux/pm_runtime.h:232
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
In kernel/irq/chip.c (ffffffff810ead09)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8148378b)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffff8149f34a)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814a4432)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814a7de8)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c0858)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81585636)
Location: include/linux/pm_runtime.h:235
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815a2f8d)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/base/core.c (ffffffff815c7f4a)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff815cc3a2)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815d60dd)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff815d8b22)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815ef91b)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff815fefc3)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff8160020a)
Location: include/linux/pm_runtime.h:235
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816414e6)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81672ee1)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff81677951)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81696a16)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff816a1c66)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff816adddf)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/mmc/core/core.c (ffffffff81752176)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff8175eb8f)
Location: include/linux/pm_runtime.h:235
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760725)
Location: include/linux/pm_runtime.h:235
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
In kernel/irq/chip.c (ffffffff810ea3d2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8148cd75)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffff814a915a)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814ae4f2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814b1d98)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814caf97)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81598d76)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6b35)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/base/core.c (ffffffff815dcbd4)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff815e0f55)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815eaaed)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff815ed622)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81603b5b)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff81612e3f)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff816140aa)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff81655db6)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81687741)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff8168bf6c)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff816abd8c)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff816b6c26)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff816c2f55)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff816e7416)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726c47)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81727196)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff81770bd6)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e48f)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177f2c0)
Location: include/linux/pm_runtime.h:223
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
In kernel/irq/chip.c (ffffffff810f28e2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff814c8e45)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffff814e818d)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff814ed8c2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff814f1478)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150b586)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff815abc86)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fdb86)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d862)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/base/core.c (ffffffff81643bd4)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81648065)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81651e9d)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816549d2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166bf31)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff8167b6af)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c74a)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816bf366)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff816f0ff7)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
```
```
In drivers/spi/spi.c (ffffffff816f58fc)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817171ec)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817224b6)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff8172ed25)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81753c56)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772dab)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81798297)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81799016)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff817e6916)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4a2f)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f5875)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8181191f)
Location: include/linux/pm_runtime.h:223
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
In kernel/irq/chip.c (ffffffff810facee)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff814f9df2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8151274a)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff815128d2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff815177f9)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8151d522)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81521668)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8153ff26)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff815e3c90)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816374c5)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/base/core.c (ffffffff8167efdd)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/base/dd.c (ffffffff81683576)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8168d77d)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81690292)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a79b1)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff816b73f2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b81c2)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff816fb997)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff817335e2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81733fc2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/usb/core/hub.c (ffffffff81756042)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81761124)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff8176de45)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817942ca)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3378)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817daf47)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff817db5dc)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff8182fc55)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff8183cf18)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183ed59)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b4d0)
Location: include/linux/pm_runtime.h:223
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
In kernel/irq/chip.c (ffffffff811064ae)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8150e9c2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81527fa0)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81528102)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8152d279)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81532c22)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81537498)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538cb4)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815507d0)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81557826)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff815fe070)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655aa5)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff81661037)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff8169f41d)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/base/dd.c (ffffffff816a3279)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816ad9cd)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816b08f2)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8551)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff816d8628)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d9402)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/scsi/scsi_pm.c (ffffffff8171e377)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff81756060)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81756c96)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8177a52e)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81785724)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff817924c5)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817ba89a)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9949)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81802587)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8180298c)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff8185bec5)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff81868ea8)
Location: include/linux/pm_runtime.h:223
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186ad09)
Location: include/linux/pm_runtime.h:223
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187a9d0)
Location: include/linux/pm_runtime.h:223
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
In kernel/irq/chip.c (ffffffff8110fa39)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8153d04e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815571e0)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff815573a3)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8155b9c9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81562372)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81566de8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81568694)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815806a0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81587858)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8162ce15)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689c45)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816971a1)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816d7d33)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/base/dd.c (ffffffff816dc0b2)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816e754e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816ea510)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817039e9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff81713858)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714a2b)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81759a67)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff81792187)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817932f9)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817b806f)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817bbfc8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff817c3c34)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff817d0e20)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817fa1ca)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a6f5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183b43c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81843437)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff818444ec)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff8189fd85)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff818adcf8)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818aec18)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c035c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/soundwire/bus.c (ffffffff818c14da)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/soundwire/bus.c:sdw_nwrite
  - drivers/soundwire/bus.c:sdw_nread
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
In kernel/irq/chip.c (ffffffff8111bcf9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8155de5e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81578820)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff815789d3)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8157ca79)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81583512)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81588148)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff815898d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2160)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9218)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8164e4d5)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac1f5)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816b9d51)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816fbcf5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff817000e2)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8170b92e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8170e570)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81727d43)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff81737b58)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738d3b)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8177d977)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff817b5d5a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817b6e49)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817e8840)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817ec7f8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff817f46f4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff81801d20)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8182b00a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184ba65)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186cdcc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874db7)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81875e3c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff818d22f5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff818e01a8)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e10c4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f2e5c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff81128029)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In fs/debugfs/file.c (ffffffff81482a0e)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In block/keyslot-manager.c (ffffffff8158166f)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff815fff1e)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8161d405)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8161d9d3)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff81622009)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8162a0d2)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8162ee88)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff816307d4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651eb5)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff816fcab5)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817634fd)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff8176d9d1)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff817b55bd)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff817b8f40)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff817c671e)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817c9f34)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e43a4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff817f4ae8)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f66bb)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81840ee7)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff8187aa22)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8187d979)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818b7d8c)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818bbed8)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff818c42c4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff818d1f56)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818fceaa)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e67f)
Location: include/linux/pm_runtime.h:234
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81941827)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949b95)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194a19c)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff819a4a35)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff819b322a)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b41c4)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c860c)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cba3c)
Location: include/linux/pm_runtime.h:234
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
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
In kernel/irq/chip.c (ffffffff81123b39)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In fs/debugfs/file.c (ffffffff814a009e)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In block/keyslot-manager.c (ffffffff8159e69f)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff81624e0e)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81643cd5)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81644213)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff81648bf9)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81650532)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81654548)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81655e74)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81674875)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81c0044e)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/clk/clk.c (ffffffff817199f5)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177e55d)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff817883b1)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff817c9d69)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff817cdc23)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff817db19e)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817de983)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f921c)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff81808568)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff818093eb)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81851407)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff818896dd)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8188bea7)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff818c669c)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818c8c98)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff818d01b4)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff818dc336)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff819057da)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925aa8)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81947b2e)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194f865)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8194fd2c)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff819a7ad5)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff819b577a)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b6814)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c835c)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff81123e99)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In fs/debugfs/file.c (ffffffff814a616e)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In block/keyslot-manager.c (ffffffff815a5492)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff816087be)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626a95)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81626f73)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8162b7b9)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff816330e2)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81636ef8)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff816380c4)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656da5)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81bf1f3c)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816facf5)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761e25)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff8176bd01)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff817ad581)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff817b1633)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff817bf4ee)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817c2d83)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817dddbe)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff817ed138)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/scsi/scsi_pm.c (ffffffff81834497)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff818691a0)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8186e807)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c0d1b5)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff818ac248)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff818b37e4)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff818bfbe0)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff818e8fca)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909198)
Location: include/linux/pm_runtime.h:384
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192b44e)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819334b5)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81933bec)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff8198c7d5)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff81999e0a)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199afc4)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad2ac)
Location: include/linux/pm_runtime.h:384
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
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
In kernel/irq/chip.c (ffffffff81144479)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In fs/debugfs/file.c (ffffffff814fe8be)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In block/keyslot-manager.c (ffffffff8160df62)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In drivers/phy/phy-core.c (ffffffff816773fe)
Location: include/linux/pm_runtime.h:394
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81696315)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8169684a)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8169ac89)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff816a3252)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff816a7138)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a83c4)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8d25)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81cee971)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/clk/clk.c (ffffffff817756e5)
Location: include/linux/pm_runtime.h:394
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5e85)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff817f1431)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81836832)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff8183a895)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8184985e)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8184d113)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81869894)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/scsi/scsi_pm.c (ffffffff818c0497)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff818fbe86)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff818fe915)
Location: include/linux/pm_runtime.h:394
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d14191)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81941298)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff81948c74)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff81956250)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81985440)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9a18)
Location: include/linux/pm_runtime.h:394
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ce62e)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6867)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff819d701c)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff81a37e35)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a47902)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5b7fc)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ethtool/ioctl.c (ffffffff81b30e1a)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81b33004)
Location: include/linux/pm_runtime.h:394
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
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
In fs/debugfs/file.c (ffffffff8158f5fe)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In block/blk-crypto-profile.c (ffffffff816c2a82)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff8179398b)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7185)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff817b7739)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff817bc436)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff817c5452)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff817c9bc3)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cafa5)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817eef6f)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81eb6082)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff834b375d)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81925397)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff81931a3c)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81978841)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff8197e47e)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8198e88d)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff819924dc)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b255a)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/scsi/scsi_pm.c (ffffffff81a0cae7)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/usb/core/hub.c (ffffffff81edece6)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81a999b7)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff81aa17d4)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff81aafde4)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81ae10e0)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07ae8)
Location: include/linux/pm_runtime.h:423
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b302fe)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b393e5)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81b39c70)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff81ba4a05)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb588b)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb9bc)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ethtool/ioctl.c (ffffffff81cbbd6c)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81cbe1c4)
Location: include/linux/pm_runtime.h:423
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
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
In fs/debugfs/file.c (ffffffff8163684e)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
```
In block/blk-crypto-profile.c (ffffffff81783e12)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff818a866b)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1855)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff818d1e69)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff818d8316)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff818e2512)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff818e75f3)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e93d5)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81916a6f)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81952379)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83eee3ca)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81cc7)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff81a903bc)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81ae4d7b)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81aeb9ee)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81afe8ad)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81b0294c)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b273cf)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/scsi/scsi_pm.c (ffffffff81b8c867)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff81bd7ac5)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/usb/core/hub.c (ffffffff81c18c29)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c1d7b7)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff81c270b4)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff81c37e34)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81c6c9d0)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c973d8)
Location: include/linux/pm_runtime.h:427
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4a69)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf165)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ccf5e0)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff81d46c35)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d5a0ef)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d7530c)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ethtool/ioctl.c (ffffffff81e7a35c)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81e7cc64)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
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
In fs/debugfs/file.c (ffffffff8166ec2e)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
```
In block/blk-crypto-profile.c (ffffffff817c40f2)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff818eb55b)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914845)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81914e69)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8191b5e6)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81925952)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8192ac13)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192c9e5)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a05f)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff8199878f)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff8371400a)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acd2c7)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff81adbbcc)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81b33380)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81b39c5e)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81b4cc6d)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81b509fc)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b76dbf)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/scsi/scsi_pm.c (ffffffff81be0877)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff81c2e4e8)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/usb/core/hub.c (ffffffff81c7fc01)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81c846a7)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff81c8e074)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff81c9f1e1)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81cd3fc0)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe6f8)
Location: include/linux/pm_runtime.h:427
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c3a9)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d37215)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81d376b0)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff81db1425)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4a8f)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de324c)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ethtool/ioctl.c (ffffffff81ed6652)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81ed9024)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
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
In fs/debugfs/file.c (ffffffff816a969e)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
```
In block/blk-crypto-profile.c (ffffffff81808d82)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In drivers/phy/phy-core.c (ffffffff81932a9b)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_on
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195c7b5)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8195cdd9)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff81963a16)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8196e0d2)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff819734a3)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81975275)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a35ff)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff83947a6a)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b20397)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_get_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_break_ctl
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_empty
  - drivers/tty/serial/8250/8250_port.c:serial8250_default_handle_irq
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_handle_stop_tx
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_sleep
```
```
In drivers/tty/serdev/core.c (ffffffff81b2ef2c)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff81b8acbf)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81b9171e)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81ba516d)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81ba8f7c)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcab8f)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/scsi/scsi_pm.c (ffffffff81c358a7)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff81ce0f38)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/usb/core/hub.c (ffffffff81d347b8)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff81d390a7)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff81d42b94)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
```
```
In drivers/usb/core/port.c (ffffffff81d53e31)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81d88f80)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4f58)
Location: include/linux/pm_runtime.h:425
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de2279)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded495)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff81ded930)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff81e697b5)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d36f)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e9933c)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In net/ethtool/ioctl.c (ffffffff81f9a1d2)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81f9ced4)
Location: include/linux/pm_runtime.h:425
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_begin
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
In kernel/irq/chip.c (ffff8000101800f4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676798)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/phy/phy-core.c (ffff8000106862f8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffff8000106e01e0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffff8000106e7484)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffff8000106ec520)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee238)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070a9d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff8000107124c8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071d9ac)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e2f8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721b98)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072aecc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff800011479c28)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff80001073440c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/amba/bus.c (ffff8000107b952c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
```
```
In drivers/clk/clk.c (ffff8000107bda98)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb670)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume
```
```
In drivers/tty/serial/8250/8250_port.c (ffff800010886fa0)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_dw.c (ffff800010891590)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892d54)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serial/8250/8250_of.c (ffff8000108935dc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
```
```
In drivers/tty/serdev/core.c (ffff8000108a9fd4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/arm-smmu.c (ffff8000108cff40)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_device_shutdown
  - drivers/iommu/arm-smmu.c:arm_smmu_remove_device
  - drivers/iommu/arm-smmu.c:arm_smmu_add_device
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
  - drivers/iommu/arm-smmu.c:arm_smmu_iotlb_sync
  - drivers/iommu/arm-smmu.c:arm_smmu_flush_iotlb_all
  - drivers/iommu/arm-smmu.c:arm_smmu_unmap
  - drivers/iommu/arm-smmu.c:arm_smmu_map
  - drivers/iommu/arm-smmu.c:arm_smmu_attach_dev
  - drivers/iommu/arm-smmu.c:arm_smmu_domain_free
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108daa14)
Location: include/linux/pm_runtime.h:224
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
In drivers/base/core.c (ffff8000108e65f8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffff8000108eb42c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffff8000108fa4d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffff8000108fe190)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091d418)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffff800010932c48)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffff800010933a18)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffff800010983c9c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/ata/libahci.c (ffff8000109baec4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
```
In drivers/ata/libahci_platform.c (ffff8000109bd664)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/spi/spi.c (ffff8000109c95d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffff8000109cac54)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109cd99c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e6734)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/usb/core/hub.c (ffff800010a180c4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffff800010a1b8fc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffff800010a25204)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffff800010a36188)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8ade8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffff800010aafaf0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9b44)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffff800010abace0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/i2c/busses/i2c-omap.c (ffff800010abaef8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
```
```
In drivers/i2c/busses/i2c-sprd.c (ffff800010abca28)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer
```
```
In drivers/mmc/core/core.c (ffff800010b2d7bc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a360)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3b204)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffff800010b4170c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/host/mmci.c (ffff800010b44ce4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_remove
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b64d80)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65fe0)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e910)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/memory/mtk-smi.c (ffff800010b8c154)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_get
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
In kernel/irq/chip.c (c03d0158)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f074)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fb58)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/bus/ti-sysc.c (c08293bc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/phy/phy-core.c (c082a170)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/gpio/gpio-omap.c (c086d670)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_request
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_bus_lock
```
```
In drivers/pci/probe.c (c087be98)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c08825c0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (c0887850)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (c08892e4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a69dc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c08a74fc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/pci/controller/pci-tegra.c (c08ac6ec)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08ada68)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
```
```
In drivers/pci/controller/pcie-rcar.c (c08aefa4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b6440)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c1552330)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bd0fc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/amba/bus.c (c08e5ea0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
```
```
In drivers/clk/clk.c (c08e94e0)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904c34)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume
```
```
In drivers/clk/tegra/clk-dfll.c (c090c248)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_enable
```
```
In drivers/clk/ti/clk-dra7-atl.c (c091aacc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/clk-dra7-atl.c:atl_clk_enable
```
```
In drivers/dma/tegra20-apb-dma.c (c092a5e8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_alloc_chan_resources
```
```
In drivers/dma/ti/edma.c (c092db20)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_tptc_probe
  - drivers/dma/ti/edma.c:edma_probe
```
```
In drivers/tty/serial/8250/8250_port.c (c0985484)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (c098dd24)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
```
```
In drivers/tty/serial/8250/8250_of.c (c098e928)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
```
In drivers/tty/serial/omap-serial.c (c099ed20)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_remove
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_config_rs485
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_get_char
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char
  - drivers/tty/serial/omap-serial.c:serial_omap_pm
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_shutdown
  - drivers/tty/serial/omap-serial.c:serial_omap_break_ctl
  - drivers/tty/serial/omap-serial.c:serial_omap_set_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_get_mctrl
  - drivers/tty/serial/omap-serial.c:serial_omap_tx_empty
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/omap-serial.c:serial_omap_unthrottle
  - drivers/tty/serial/omap-serial.c:serial_omap_throttle
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_rx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_enable_ms
```
```
In drivers/tty/serdev/core.c (c09a64a8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/iommu/omap-iommu.c (c09c4738)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_domain_activate
  - drivers/iommu/omap-iommu.c:flush_iotlb_all
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
```
```
In drivers/iommu/qcom_iommu.c (c09cbc84)
Location: include/linux/pm_runtime.h:224
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
In drivers/base/core.c (c09d4c70)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (c09d9514)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (c09e58ec)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (c09e8cc0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (c0a028d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (c0a15b70)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (c0a169f0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/mfd/omap-usb-host.c (c0a34cb8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
```
```
In drivers/mfd/omap-usb-tll.c (c0a35a40)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/omap-usb-tll.c:omap_tll_enable
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
```
```
In drivers/scsi/scsi_pm.c (c0a56430)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/ata/libahci.c (c0a8609c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
```
In drivers/ata/libahci_platform.c (c0a883bc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
```
```
In drivers/mtd/nand/raw/omap_elm.c (c0aacd24)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
```
```
In drivers/spi/spi.c (c0ab3004)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (c0ab3b14)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_access_start
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab7eac)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ac93e8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0ad034c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad42e0)
Location: include/linux/pm_runtime.h:224
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
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adaee8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin
```
```
In drivers/usb/core/hub.c (c0aeff14)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (c0af3850)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (c0afb868)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (c0b096a4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5daf8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/usb/musb/musb_core.c (c0b667f0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_suspend
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:vbus_show
  - drivers/usb/musb/musb_core.c:musb_ulpi_write
  - drivers/usb/musb/musb_core.c:musb_ulpi_read
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f9dc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_start
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
```
```
In drivers/usb/musb/musb_debugfs.c (c0b7154c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_show
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_show
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_show
```
```
In drivers/rtc/rtc-omap.c (c0b8c7ac)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
```
In drivers/i2c/i2c-core-base.c (c0b91684)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c0b991fc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c0b9a0d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9c2a0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
```
```
In drivers/i2c/busses/i2c-omap.c (c0b9c800)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
```
```
In drivers/power/avs/smartreflex.c (c0ba93b4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:sr_enable
```
```
In drivers/mmc/core/core.c (c0c06c38)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (c0c14d64)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (c0c15d38)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (c0c1c50c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/mmc/host/mmci.c (c0c1e87c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_remove
```
```
In drivers/mmc/host/omap_hsmmc.c (c0c2c220)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
```
```
In drivers/mmc/host/sdhci-esdhc-imx.c (c0c2e3b4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
```
```
In drivers/clocksource/sh_cmt.c (c0c448c4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
```
```
In drivers/clocksource/sh_mtu2.c (c0c45a10)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
```
```
In drivers/clocksource/sh_tmu.c (c0c46248)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47650)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c625b4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
```
In drivers/memory/omap-gpmc.c (c0c7191c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/memory/omap-gpmc.c:gpmc_resume
  - drivers/memory/omap-gpmc.c:gpmc_probe
```
```
In drivers/memory/mtk-smi.c (c0c73114)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_get
```
```
In sound/soc/soc-dapm.c (c0ca7e0c)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In sound/soc/soc-pcm.c (c0cb1940)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:soc_pcm_open
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
In kernel/irq/chip.c (c0000000001daca8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (c000000000820ddc)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (c000000000858fec)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c000000000861bf8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (c00000000086815c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (c00000000086a8b8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088e978)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (c00000000088f708)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/tty/serial/8250/8250_port.c (c00000000092dfdc)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (c00000000093ac44)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
```
```
In drivers/tty/serdev/core.c (c0000000009408e0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (c00000000097c340)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (c000000000982a48)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (c0000000009969b4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (c00000000099b464)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c1f44)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (c0000000009d1d40)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4964)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (c000000000a408ac)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (c000000000a8b200)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (c000000000a8c4e0)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (c000000000ad0da8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (c000000000ad5328)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (c000000000ae03f4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (c000000000af430c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b667a4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (c000000000b92e30)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d610)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (c000000000b9e124)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (c000000000c23e14)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (c000000000c35370)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (c000000000c37a20)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a45c)
Location: include/linux/pm_runtime.h:224
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
In kernel/irq/chip.c (ffffffe000118342)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffe00049604a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffe0004b8098)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffe0004bdc1c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffe0004c15e6)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c2670)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7746)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e46f0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e54ee)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
```
```
In drivers/clk/clk.c (ffffffe00050cf70)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551ec8)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559aaa)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffe00055ead4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffe00057b08c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffe00057f084)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffe000589c5a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffe00058cb8a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cc4a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a8b74)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9884)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffe0005e8c50)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffe0006196ac)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffe00061a52c)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffe00063cc44)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffe00063fec8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffe00064758e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffe00065367c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a034a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b821e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bed4c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffe0006bf4d0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffe000705688)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffe000710ea8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe0007127ca)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/mmc/core/block.c (ffffffe000718620)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_remove
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c9a4)
Location: include/linux/pm_runtime.h:224
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
In kernel/irq/chip.c (ffffffff811142d9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8155644e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffff81570f99)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81577a32)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157bfd8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d764)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595970)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159c9e8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff81614535)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671c65)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff8167f7b1)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816c14e5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816c58d2)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816d107e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816d3cc0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816edb23)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff816fb8b8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fca9b)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81732067)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff8177a83a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8177b929)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817a0c20)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817a4bd8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff817acad4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff817ba100)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff817e33ea)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/mmc/core/core.c (ffffffff81875cb5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff81883b68)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81884a84)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8189418c)
Location: include/linux/pm_runtime.h:224
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
In kernel/irq/chip.c (ffffffff81104fe9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8154690e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pci/probe.c (ffffffff8155f6f9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81566172)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8156ada8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c534)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584b00)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bb78)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff81608a65)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650d65)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/base/core.c (ffffffff8169c795)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816a0b52)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816ac39e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816aef60)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8163)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff816cf6c8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d08ab)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8170b487)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff8175a5ea)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8175b6d9)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81792a60)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817966e8)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff8179e4d4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff817abb30)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8fb5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c8ac)
Location: include/linux/pm_runtime.h:224
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
In kernel/irq/chip.c (ffffffff811121c9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8155218e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8156c570)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8156c723)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff815707c9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81577262)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff8157be98)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d624)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595eb0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159cf68)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff81642315)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a0035)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816adb91)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff816ef9b5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816f3da2)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816ff5ee)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81702230)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b203)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff8172b018)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c1fb)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff81770e37)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff817aabda)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817abcc9)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817dd6c0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817e1678)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff817e9574)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff817f6ba0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff8181fe8a)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818408e5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81860f5c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (ffffffff81868bb3)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a267)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8186b2ec)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff818c7155)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff818d5008)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5f24)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e7c8c)
Location: include/linux/pm_runtime.h:224
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
In kernel/irq/chip.c (ffffffff8111d7e9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_get
```
```
In drivers/phy/phy-core.c (ffffffff8156c01e)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81586a70)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81586c23)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
```
```
In drivers/pci/probe.c (ffffffff8158aca9)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81591722)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_get
```
```
In drivers/pci/pci-driver.c (ffffffff81596348)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597ad4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0330)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b7398)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8165c6f5)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba4f5)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffff816c7ff1)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_open
```
```
In drivers/base/core.c (ffffffff8170a1f5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff8170e5d2)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81719bfe)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8171ca50)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81736563)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/mfd/arizona-core.c (ffffffff81746458)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
```
```
In drivers/mfd/arizona-irq.c (ffffffff8174763b)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
```
In drivers/scsi/scsi_pm.c (ffffffff8178c5d7)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
```
```
In drivers/spi/spi.c (ffffffff817c4b54)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817c5c59)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817f7990)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/hcd.c (ffffffff817fba68)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
```
```
In drivers/usb/core/driver.c (ffffffff81803aa4)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
```
```
In drivers/usb/core/port.c (ffffffff81810de0)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
```
```
In drivers/usb/host/ohci-platform.c (ffffffff81839dfa)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185adb5)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187c16c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818841f7)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
```
In drivers/i2c/busses/i2c-designware-platdrv.c (ffffffff8188527c)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
```
```
In drivers/mmc/core/core.c (ffffffff818e3c05)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1b28)
Location: include/linux/pm_runtime.h:224
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2a44)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819049ac)
Location: include/linux/pm_runtime.h:224
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
</details>
</li>
</ul>

## Differences
