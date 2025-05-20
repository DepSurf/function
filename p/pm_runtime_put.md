# Function: <code>pm_runtime_put</code>

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
In drivers/phy/phy-core.c (ffffffff8141be9f)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81423419)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_free
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429c70)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_type
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_input
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_output
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a63a)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/pci.c (ffffffff8143732d)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814520e3)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/dd.c (ffffffff8154b45b)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8155511b)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
```
```
In drivers/base/power/runtime.c (ffffffff8155659a)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff8155a814)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8156b6d3)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff815e7bb6)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81608043)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81614162)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff8161eec3)
Location: include/linux/pm_runtime.h:231
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_port_runtime_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In kernel/irq/chip.c (ffffffff810e44e8)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff814645ed)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146bd29)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81475484)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/probe.c (ffffffff8147dfec)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff81482eed)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8149ec5b)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/dd.c (ffffffff8159d74f)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815a7d77)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff815a86c2)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff815ad5f6)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815c0503)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81646841)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81667d15)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81674052)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff816800dd)
Location: include/linux/pm_runtime.h:237
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
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
In kernel/irq/chip.c (ffffffff810ead88)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff814838ed)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148c0f9)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497a54)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/probe.c (ffffffff8149f6ac)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814a447d)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814c088b)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/dd.c (ffffffff815cbacf)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815d60f7)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff815d8b92)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/power/main.c (ffffffff815dc3b6)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff815ef943)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81677931)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff81695a35)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff816a1ce2)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff816ade1d)
Location: include/linux/pm_runtime.h:240
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
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
In kernel/irq/chip.c (ffffffff810ea448)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff8148cdef)
Location: include/linux/pm_runtime.h:228
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81495a79)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1704)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/probe.c (ffffffff814a93f7)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge
```
```
In drivers/pci/pci.c (ffffffff814ae53d)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff814cafd1)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/base/dd.c (ffffffff815e06b6)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff815eab07)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff815ed692)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/power/main.c (ffffffff815f10db)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81603b83)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff8168c009)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff816aaeb0)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff816b6ca2)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff816c2f93)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff8177e819)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
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
In kernel/irq/chip.c (ffffffff810f2958)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff814c8ebf)
Location: include/linux/pm_runtime.h:228
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d1d79)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e00d4)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/probe.c (ffffffff814e8439)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff814ed90d)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8150b5c0)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff815a7add)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/dd.c (ffffffff81647786)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81651eb7)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81654a42)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:__rpm_callback
```
```
In drivers/base/power/main.c (ffffffff816584ef)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8166bf59)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff816f59a3)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/usb/core/hub.c (ffffffff817162f3)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81722532)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff8172ed63)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772e52)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/mmc/core/sdio.c (ffffffff817f4dbb)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818116b7)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff810fad58)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff814f9e73)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81502de2)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f46d)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81512861)
Location: include/linux/pm_runtime.h:228
Inline: True
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8151293d)
Location: include/linux/pm_runtime.h:228
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81517a15)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8151d579)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8153ff60)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff815df77a)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/dd.c (ffffffff81682c76)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8168d797)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81690302)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff8169458d)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816a79d9)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff817336c0)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81734322)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/usb/core/hub.c (ffffffff817550d4)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81761192)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff8176de93)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b33dc)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/mmc/core/sdio.c (ffffffff8183e225)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b757)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff81106518)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff8150ea43)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815178f2)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524b1d)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81527ce8)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8152816d)
Location: include/linux/pm_runtime.h:228
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8152d495)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81532c79)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538cd9)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8155081b)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551898)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81557862)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff815f949a)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff816610d4)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/dd.c (ffffffff816a28b6)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816ad9e7)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816b0962)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff816b4c0d)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8579)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff8175613e)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81756d25)
Location: include/linux/pm_runtime.h:228
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff8177960f)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81785797)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81792513)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d99ad)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/mmc/core/sdio.c (ffffffff8186a1d5)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187ad57)
Location: include/linux/pm_runtime.h:228
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff8110fa9a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff8153d0e3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81545af2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815531fd)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81556f48)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81557407)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8155bd80)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff815623cb)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff815686b8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815806ef)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815817f8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81587891)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8162b79e)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff81696b96)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (ffffffff816d596b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
```
```
In drivers/base/dd.c (ffffffff816db671)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816e7568)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816ea593)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff816eea16)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817039d6)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81792ab4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81793375)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817b7490)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817c3c99)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff817d0e63)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a757)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8183aa72)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818ae0a4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c01eb)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In drivers/soundwire/bus.c (ffffffff818c150d)
Location: include/linux/pm_runtime.h:229
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
In kernel/irq/chip.c (ffffffff8111bd5a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff8155def3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81566a12)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8157489d)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81578588)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81578a37)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8157ce30)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8158356b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff815898f8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a21b9)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a32f8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a9251)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8164d30e)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff816b9726)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (ffffffff816f975b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816ff641)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8170b948)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8170e5f3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff817129bb)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81727d30)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff817b6615)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817b6ec5)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817e7c50)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817f4759)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81801d63)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bac7)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8186c402)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818e0554)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f2d0b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff8112808a)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In fs/debugfs/file.c (ffffffff81482a87)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In drivers/phy/phy-core.c (ffffffff815fffb3)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8160a455)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8161d6bc)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8161da37)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/pci/probe.c (ffffffff816223ca)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8162a12b)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff816307f8)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164ac97)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164bec8)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651eee)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff816fc11e)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff8176e3c9)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff817b264b)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff817b98bd)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff817c6738)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817c9fd3)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff817ce21e)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817e43c5)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff8187d4e6)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8187e4d7)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/usb/core/hub.c (ffffffff818ba5c0)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff818c4329)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff818d1fa4)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e6d9)
Location: include/linux/pm_runtime.h:239
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81940122)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff819b3529)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c891d)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c9f69)
Location: include/linux/pm_runtime.h:239
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
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
In kernel/irq/chip.c (ffffffff81123b9a)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In fs/debugfs/file.c (ffffffff814a0117)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In drivers/phy/phy-core.c (ffffffff81624ea3)
Location: include/linux/pm_runtime.h:417
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162eb65)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81643f10)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81644277)
Location: include/linux/pm_runtime.h:417
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81648fb2)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8165058b)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff81655e98)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166f3e7)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670218)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816748ae)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff8169cc82)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_remove
```
```
In drivers/clk/clk.c (ffffffff8171901e)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff81788da9)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff817c9cf0)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:__device_link_free_srcu
```
```
In drivers/base/dd.c (ffffffff817cdc9a)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff817db1b8)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817deb6d)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81c0edf1)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817f9205)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81c18f25)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8188ca47)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/usb/core/hub.c (ffffffff81c1b0e6)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff818d0219)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff818dc384)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925af9)
Location: include/linux/pm_runtime.h:417
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946296)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff819b5a79)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c866d)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff81123ef1)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In fs/debugfs/file.c (ffffffff814a61e7)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In drivers/phy/phy-core.c (ffffffff81608853)
Location: include/linux/pm_runtime.h:417
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81612805)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626b4b)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81626fd7)
Location: include/linux/pm_runtime.h:417
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8162bb72)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8163313b)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff816380e8)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81651907)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652718)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656dde)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff8167fa22)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_remove
```
```
In drivers/clk/clk.c (ffffffff816fa31e)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff8176c699)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff817ad50c)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff817b16aa)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff817bf508)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817c2f6d)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81c00fef)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff817ddddf)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81c0ad53)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8186f4c9)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_write
  - drivers/spi/spi-mem.c:spi_mem_dirmap_read
  - drivers/spi/spi-mem.c:spi_mem_exec_op
```
```
In drivers/usb/core/hub.c (ffffffff81c0cf54)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff818b3849)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff818bfc2c)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819091e7)
Location: include/linux/pm_runtime.h:417
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81929ad5)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff8199a286)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad5bd)
Location: include/linux/pm_runtime.h:417
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff811444d1)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In fs/debugfs/file.c (ffffffff814fe937)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In drivers/phy/phy-core.c (ffffffff81677493)
Location: include/linux/pm_runtime.h:427
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81681935)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff816963d5)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff816968a7)
Location: include/linux/pm_runtime.h:427
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8169b042)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff816a32ab)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a83e8)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c3687)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c44aa)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8d5e)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81cee9ae)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
```
In drivers/clk/clk.c (ffffffff81775032)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff817f1de9)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff81836785)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff8183a92e)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81849878)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8184d249)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81d03b39)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8186987d)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81d10021)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff818fe8c8)
Location: include/linux/pm_runtime.h:427
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d13f01)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81948cd9)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff8195629c)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9a67)
Location: include/linux/pm_runtime.h:427
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819ccc20)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81a46b3e)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5bb1d)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In net/ethtool/ioctl.c (ffffffff81b3194d)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81b330c1)
Location: include/linux/pm_runtime.h:427
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_complete
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
In kernel/irq/chip.c (ffffffff811680c2)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In fs/debugfs/file.c (ffffffff8158f677)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_show_regset32
```
```
In drivers/phy/phy-core.c (ffffffff81793636)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179d8f5)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7242)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff817b77a7)
Location: include/linux/pm_runtime.h:456
Inline: True
```
```
In drivers/pci/probe.c (ffffffff817bc69d)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff817c54ba)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cafc0)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e90e7)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea0ec)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817eefab)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff81eb60c0)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
```
In drivers/clk/clk.c (ffffffff818aad3e)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff81932517)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff8197877e)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff8197e508)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff8198e8a7)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8199256d)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81ecc1ed)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff819b2543)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81edad7f)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff81a50222)
Location: include/linux/pm_runtime.h:456
Inline: True
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a8100d)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
```
```
In drivers/usb/core/hub.c (ffffffff81a95be0)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81aa1849)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81aafe30)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07b37)
Location: include/linux/pm_runtime.h:456
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2e878)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb491b)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcbd1d)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In net/ethtool/ioctl.c (ffffffff81cbbf39)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81cbe291)
Location: include/linux/pm_runtime.h:456
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_complete
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
In kernel/irq/chip.c (ffffffff8119c582)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In fs/debugfs/file.c (ffffffff816368c7)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
```
In drivers/phy/phy-core.c (ffffffff818a8282)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b4505)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1912)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff818d1f2c)
Location: include/linux/pm_runtime.h:460
Inline: True
```
```
In drivers/pci/probe.c (ffffffff818d8585)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff818e258a)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e93f0)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ec87)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8191018c)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81916aab)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff8195248d)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
```
In drivers/clk/clk.c (ffffffff819f632e)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff81a91047)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff81ae514d)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81aeba78)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81afe8c7)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81b029ed)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81b03ac2)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b2707a)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81bd6b3a)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81bd9382)
Location: include/linux/pm_runtime.h:460
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c182a0)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81c27139)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81c37e80)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97427)
Location: include/linux/pm_runtime.h:460
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc469c)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81d59041)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d7574a)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In net/ethtool/ioctl.c (ffffffff81e7a529)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81e7cd41)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_ops_complete
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
In kernel/irq/chip.c (ffffffff811ae3f6)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In fs/debugfs/file.c (ffffffff8166eca7)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
```
In drivers/phy/phy-core.c (ffffffff818eb172)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f7585)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914902)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81914f2c)
Location: include/linux/pm_runtime.h:460
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8191b85c)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff819259ca)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192ca00)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952304)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819538ac)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a09b)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/video/fbdev/efifb.c (ffffffff819988fa)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/video/fbdev/efifb.c:efifb_destroy
```
```
In drivers/clk/clk.c (ffffffff81a3eac6)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff81adc857)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:devm_serdev_device_release
```
```
In drivers/base/core.c (ffffffff81b333d2)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81b39ce8)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81b4cc87)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81b50a9d)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81b51b22)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81b76c8d)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81c2d56a)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fd82)
Location: include/linux/pm_runtime.h:460
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81c7f2a3)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81c8e0fc)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81c9f232)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe74a)
Location: include/linux/pm_runtime.h:460
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2c30c)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc39ef)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de368a)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In net/ethtool/ioctl.c (ffffffff81ed68bf)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81ed94fc)
Location: include/linux/pm_runtime.h:460
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
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
In kernel/irq/chip.c (ffffffff811bdff6)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
```
In fs/debugfs/file.c (ffffffff816a9717)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_regset32_show
```
```
In drivers/phy/phy-core.c (ffffffff819326b2)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_power_off
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195c872)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8195ce9c)
Location: include/linux/pm_runtime.h:458
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81963c8c)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8196e14a)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/pci-sysfs.c (ffffffff81975290)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b794)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199cd3c)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a363b)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff81a8a3f6)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff81b2efb4)
Location: include/linux/pm_runtime.h:458
Inline: True
```
```
In drivers/base/core.c (ffffffff81b8ad11)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff81b917a8)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81ba5187)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff81ba901d)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:pm_runtime_remove
  - drivers/base/power/runtime.c:rpm_resume
```
```
In drivers/base/power/main.c (ffffffff81baa112)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcaa5d)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff81cdff6a)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2c42)
Location: include/linux/pm_runtime.h:458
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81d33c8b)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (ffffffff81d42c1c)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81d53e82)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4faa)
Location: include/linux/pm_runtime.h:458
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de21dc)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7c2cf)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e9977a)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In net/ethtool/ioctl.c (ffffffff81f9a442)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:__dev_ethtool
```
```
In net/ethtool/netlink.c (ffffffff81f9d3cc)
Location: include/linux/pm_runtime.h:458
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_set_doit
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
In kernel/irq/chip.c (ffff80001018018c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676708)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/phy/phy-core.c (ffff8000106863d8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pci/probe.c (ffff8000106e0354)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffff8000106e751c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee258)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070aa2c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bda8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff800010712508)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721d80)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-keystone.c (ffff8000114b9204)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_remove
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (ffff8000107345a0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/clk/clk.c (ffff8000107bf7d8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (ffff8000107eb538)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_suspend
```
```
In drivers/tty/serdev/core.c (ffff8000108a946c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/iommu/arm-smmu.c (ffff8000108cff20)
Location: include/linux/pm_runtime.h:229
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
In drivers/iommu/rockchip-iommu.c (ffff8000108d98d4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
```
In drivers/base/core.c (ffff8000108e3b60)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffff8000108ea764)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffff8000108fa4ec)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffff8000108fe22c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffff8000109030b8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffff80001091d408)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/ata/libahci.c (ffff8000109b9d24)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_stop
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
```
In drivers/spi/spi.c (ffff8000109c942c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffff8000109cace8)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffff800010a16e5c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffff800010a25280)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffff800010a361bc)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8af3c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffff800010aaee74)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a77c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/host/mmci.c (ffff800010b45720)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b65100)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_stop
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65df8)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e6cc)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (c03d01dc)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ee0c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_remove
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fa60)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_remove
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
```
```
In drivers/bus/ti-sysc.c (c0829358)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/phy/phy-core.c (c082a218)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/gpio/gpio-omap.c (c086d8ac)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_free
  - drivers/gpio/gpio-omap.c:gpio_irq_bus_sync_unlock
```
```
In drivers/pci/probe.c (c087bfa4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c0882624)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (c0889304)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/controller/pcie-rcar.c (c08af0d0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
```
```
In drivers/pci/controller/dwc/pci-dra7xx.c (c15526f8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
```
```
In drivers/pci/controller/dwc/pcie-qcom.c (c08bd26c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
```
```
In drivers/clk/clk.c (c08e81c8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/clk/renesas/rcar-usb2-clock-sel.c (c0904a34)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_remove
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_suspend
```
```
In drivers/dma/tegra20-apb-dma.c (c092a664)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
```
```
In drivers/tty/serdev/core.c (c09a5d08)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/iommu/rockchip-iommu.c (c09c65bc)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_attach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_detach_device
  - drivers/iommu/rockchip-iommu.c:rk_iommu_zap_iova
  - drivers/iommu/rockchip-iommu.c:rk_iommu_irq
```
```
In drivers/iommu/exynos-iommu.c (c09ca0c8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/iommu/exynos-iommu.c:exynos_iommu_attach_device
  - drivers/iommu/exynos-iommu.c:exynos_iommu_detach_device
```
```
In drivers/base/core.c (c09d26a4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (c09d8818)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (c09e5904)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (c09e8d50)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (c09ed4b8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (c0a0279c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/ata/libahci.c (c0a87484)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/ata/libahci.c:ahci_port_stop
  - drivers/ata/libahci.c:ahci_port_suspend
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
```
```
In drivers/spi/spi.c (c0ab2f00)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (c0ab3b94)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_access_end
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad583c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
```
```
In drivers/net/ethernet/ti/cpsw_ethtool.c (c0adaf94)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_complete
```
```
In drivers/usb/core/hub.c (c0aeefd4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/driver.c (c0afb8d0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (c0b096d8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5db5c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/usb/musb/musb_core.c (c0b651e8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_ulpi_write
  - drivers/usb/musb/musb_core.c:musb_ulpi_read
```
```
In drivers/i2c/i2c-core-base.c (c0b90a5c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (c0c1517c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/mmc/host/mmci.c (c0c1f604)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/host/mmci.c:mmci_probe
```
```
In drivers/clocksource/sh_cmt.c (c0c44798)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_stop
```
```
In drivers/clocksource/sh_mtu2.c (c0c45978)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_disable
```
```
In drivers/clocksource/sh_tmu.c (c0c4608c)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/clocksource/timer-ti-dm.c (c0c47698)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c62390)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
```
In sound/soc/soc-dapm.c (c0ca6510)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - sound/soc/soc-dapm.c:dapm_post_sequence_async
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
In kernel/irq/chip.c (c0000000001dad4c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (c000000000820f10)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pci/probe.c (c0000000008591f0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (c000000000861ca8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (c00000000086a8e0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/tty/serdev/core.c (c0000000009409a4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (c000000000978b98)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (c00000000098198c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (c0000000009969d0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (c00000000099b544)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (c0000000009a1768)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (c0000000009c1f30)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (c000000000a8b094)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (c000000000a8c5b0)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (c000000000acf990)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (c000000000ae04a4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (c000000000af4358)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66824)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (c000000000b919f0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (c000000000c37090)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5aa18)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffe0001183a4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffe000496102)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pci/probe.c (ffffffe0004b82aa)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffe0004bdc84)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c268a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d779a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8748)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/clk/clk.c (ffffffe00050b112)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffe00055eb3a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (ffffffe000578ce8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffe00057e580)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffe000589c72)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffe00058cc14)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059cb52)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffe0006195bc)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffe00061a5be)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffe00063bdb2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffe0006475ea)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffe0006536b0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a03d4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b7566)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffe0007121b2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072cd66)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff8111433a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff815564e3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155dee2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/pci/probe.c (ffffffff81571350)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff81577a8b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d788)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815959c9)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596b08)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ca21)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8161336e)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff8167f186)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (ffffffff816bef4b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816c4e31)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816d1098)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816d3d43)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff816d8d3b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816edb10)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff8177b0f5)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8177b9a5)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817a0030)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817acb39)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff817ba143)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/mmc/core/sdio.c (ffffffff81883f14)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8189403b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff8110504a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff815469a3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154d022)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155aead)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pci/probe.c (ffffffff8155fab0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff815661cb)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c558)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584b59)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81585c98)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bbb1)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8160789e)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/base/core.c (ffffffff8169a1fb)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816a00b1)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816ac3b8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff816aefe3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff816b337b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff816c8150)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff8175aea5)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff8175b755)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff81791caa)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff8179e539)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff817abb73)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9017)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c75b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff8111222a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff81552223)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155ad42)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568bcd)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8156c2d8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8156c787)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/pci/probe.c (ffffffff81570b80)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff815772bb)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157d648)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595f09)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597048)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159cfa1)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8164114e)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff816ad566)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (ffffffff816ed41b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff816f3301)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff816ff608)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff817022b3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff8170667b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff8171b1f0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff817ab495)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817abd45)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817dcad0)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817e95d9)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff817f6be3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840947)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81860592)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818d53b4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e7b3b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
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
In kernel/irq/chip.c (ffffffff8111d84a)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_chip_pm_put
```
```
In drivers/phy/phy-core.c (ffffffff8156c0b3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_put
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574bd2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_disable_free
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582aed)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_free
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815867d8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_remove
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81586c87)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/pci/probe.c (ffffffff8158b060)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
```
In drivers/pci/pci.c (ffffffff8159177b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_config_pm_runtime_put
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597af8)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:reset_store
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0389)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1488)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b73d1)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
```
In drivers/clk/clk.c (ffffffff8165b4ce)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_is_enabled
```
```
In drivers/tty/serdev/core.c (ffffffff816c79c6)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_close
```
```
In drivers/base/core.c (ffffffff81707c5b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/core.c:__device_link_free_srcu
  - drivers/base/core.c:device_link_add
```
```
In drivers/base/dd.c (ffffffff8170db31)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/qos.c (ffffffff81719c18)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
```
```
In drivers/base/power/runtime.c (ffffffff8171cad3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_put_suppliers
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_put_suppliers
```
```
In drivers/base/power/main.c (ffffffff817210b3)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81736550)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
```
```
In drivers/spi/spi.c (ffffffff817c544c)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_pump_messages
```
```
In drivers/spi/spi-mem.c (ffffffff817c5cd5)
Location: include/linux/pm_runtime.h:229
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffff817f6d8f)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81803b09)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
```
```
In drivers/usb/core/port.c (ffffffff81810e23)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_suspend
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185ae17)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8187b7a2)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1ed4)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8190485b)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_free
```
</details>
</li>
</ul>

## Differences
