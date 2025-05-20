# Function: <code>__pm_runtime_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815573d0)
Location: drivers/base/power/runtime.c:950
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_type
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_input
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_output
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/wakeirq.c:handle_threaded_wake_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815573d0-ffffffff8155743d: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815a9420)
Location: drivers/base/power/runtime.c:950
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/elevator.c:__elv_add_request
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/wakeirq.c:handle_threaded_wake_irq
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815a9420-ffffffff815a948d: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815d76d0)
Location: drivers/base/power/runtime.c:1027
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/elevator.c:__elv_add_request
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/wakeirq.c:handle_threaded_wake_irq
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815d76d0-ffffffff815d7747: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff815ece50)
Location: drivers/base/power/runtime.c:1027
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/elevator.c:__elv_add_request
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pci/probe.c:pci_scan_bridge
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_pm_prepare
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/domain.c:pm_genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_suspend
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_complete
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
```
**Symbols:**

```
ffffffff815ece50-ffffffff815ecec7: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81654200)
Location: drivers/base/power/runtime.c:1028
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/elevator.c:__elv_add_request
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume_hdmi_audio
  - drivers/spi/spi.c:spi_flash_read
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_complete
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff81654200-ffffffff81654277: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8168f600)
Location: drivers/base/power/runtime.c:1028
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/elevator.c:__elv_add_request
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_mem_exec_op
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff8168f600-ffffffff8168f677: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816af990)
Location: drivers/base/power/runtime.c:1035
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_prepare
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:__rpm_callback
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff816af990-ffffffff816afa07: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816e94c0)
Location: drivers/base/power/runtime.c:1064
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/soundwire/bus.c:sdw_nwrite
  - drivers/soundwire/bus.c:sdw_nread
```
**Symbols:**

```
ffffffff816e94c0-ffffffff816e953e: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8170d520)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff8170d520-ffffffff8170d59e: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c8af0)
Location: drivers/base/power/runtime.c:1068
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_show_regset32
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/remoteproc/remoteproc_core.c:rproc_fw_boot
```
**Symbols:**

```
ffffffff817c8af0-ffffffff817c8b6e: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817dd8d0)
Location: drivers/base/power/runtime.c:1098
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_show_regset32
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:unlink_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff817dd8d0-ffffffff817dd94e: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817c1c60)
Location: drivers/base/power/runtime.c:1098
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_show_regset32
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_set_cs_timing
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff817c1c60-ffffffff817c1cde: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184b7e0)
Location: drivers/base/power/runtime.c:1117
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_show_regset32
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:__submit_bio
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_evict_key
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/netlink.c:ethnl_ops_begin
```
**Symbols:**

```
ffffffff8184b7e0-ffffffff8184b85e: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81991220)
Location: drivers/base/power/runtime.c:1145
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_show_regset32
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_sriov_configure
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/netlink.c:ethnl_ops_begin
```
**Symbols:**

```
ffffffff81991220-ffffffff8199129f: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01590)
Location: drivers/base/power/runtime.c:1158
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_regset32_show
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/netlink.c:ethnl_ops_begin
```
**Symbols:**

```
ffffffff81b01590-ffffffff81b0160f: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4f6c0)
Location: drivers/base/power/runtime.c:1158
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_regset32_show
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/video/fbdev/efifb.c:efifb_probe
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/netlink.c:ethnl_ops_begin
```
**Symbols:**

```
ffffffff81b4f6c0-ffffffff81b4f73f: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba7c40)
Location: drivers/base/power/runtime.c:1159
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - fs/debugfs/file.c:debugfs_regset32_show
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:__bio_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:__blk_crypto_evict_key
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/phy/phy-core.c:phy_power_on
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
  - drivers/pwm/pwm-lpss.c:pwm_lpss_get_state
  - drivers/pwm/pwm-lpss.c:pwm_lpss_apply
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_resume_one
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_handle_request
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serial/serial_core.c:__uart_start
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:spi_setup
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_device
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:link_peers
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - net/core/dev.c:__dev_open
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/netlink.c:ethnl_ops_begin
```
**Symbols:**

```
ffffffff81ba7c40-ffffffff81ba7cbf: __pm_runtime_resume (STB_GLOBAL)
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
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffff8000108fc928)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/amba/bus.c:amba_remove
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume
  - drivers/tty/serial/8250/8250_dw.c:dw8250_remove
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serdev/core.c:serdev_device_open
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
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_flush_iotlb_all
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_remove
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe
  - drivers/i2c/busses/i2c-sprd.c:sprd_i2c_master_xfer
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_get
```
**Symbols:**

```
ffff8000108fc928-ffff8000108fca20: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c09e6f04)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-renesas-irqc.c:irqc_probe
  - drivers/bus/ti-sysc.c:sysc_remove
  - drivers/bus/ti-sysc.c:sysc_probe
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/gpio/gpio-omap.c:omap_gpio_probe
  - drivers/gpio/gpio-omap.c:omap_gpio_request
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_bus_lock
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_probe
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_probe
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_probe
  - drivers/pci/controller/dwc/pcie-qcom.c:qcom_pcie_probe
  - drivers/amba/bus.c:amba_remove
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_probe
  - drivers/clk/renesas/rcar-usb2-clock-sel.c:rcar_usb2_clock_sel_resume
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe
  - drivers/clk/tegra/clk-dfll.c:dfll_init
  - drivers/clk/tegra/clk-dfll.c:dfll_enable
  - drivers/clk/ti/clk-dra7-atl.c:of_dra7_atl_clk_probe
  - drivers/clk/ti/clk-dra7-atl.c:atl_clk_enable
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_probe
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_alloc_chan_resources
  - drivers/dma/ti/edma.c:edma_tptc_probe
  - drivers/dma/ti/edma.c:edma_probe
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_remove
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
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
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/iommu/omap-iommu.c:omap_iommu_attach_dev
  - drivers/iommu/omap-iommu.c:omap_iommu_domain_activate
  - drivers/iommu/omap-iommu.c:flush_iotlb_all
  - drivers/iommu/omap-iommu.c:flush_iotlb_page
  - drivers/iommu/qcom_iommu.c:qcom_iommu_device_probe
  - drivers/iommu/qcom_iommu.c:qcom_iommu_flush_iotlb_all
  - drivers/iommu/qcom_iommu.c:qcom_iommu_unmap
  - drivers/iommu/qcom_iommu.c:qcom_iommu_detach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_attach_dev
  - drivers/iommu/qcom_iommu.c:qcom_iommu_domain_free
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-host.c:usbhs_omap_probe
  - drivers/mfd/omap-usb-tll.c:omap_tll_enable
  - drivers/mfd/omap-usb-tll.c:omap_tll_init
  - drivers/mfd/omap-usb-tll.c:usbtll_omap_probe
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libahci.c:ahci_port_resume
  - drivers/ata/libahci.c:ahci_transmit_led_message
  - drivers/ata/libahci.c:ahci_show_em_supported
  - drivers/ata/libahci.c:ahci_store_em_buffer
  - drivers/ata/libahci.c:ahci_read_em_buffer
  - drivers/ata/libahci.c:ahci_show_port_cmd
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/mtd/nand/raw/omap_elm.c:elm_resume
  - drivers/mtd/nand/raw/omap_elm.c:elm_probe
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi-mem.c:spi_mem_access_start
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_setup
  - drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_set_cs
  - drivers/net/ethernet/freescale/fec_main.c:fec_drv_remove
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_get_regs
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_write
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_read
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_reset
  - drivers/net/ethernet/ti/cpsw.c:cpsw_remove
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_setup_tc
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_tx_maxrate
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_kill_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_vlan_rx_add_vid
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_ethtool_op_begin
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/musb/musb_core.c:musb_suspend
  - drivers/usb/musb/musb_core.c:musb_remove
  - drivers/usb/musb/musb_core.c:musb_init_controller
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:vbus_show
  - drivers/usb/musb/musb_core.c:musb_ulpi_write
  - drivers/usb/musb/musb_core.c:musb_ulpi_read
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_start
  - drivers/usb/musb/musb_gadget.c:musb_gadget_work
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_write
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_show
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_write
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_show
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_show
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_remove
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_remove
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_probe
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_common
  - drivers/power/avs/smartreflex.c:omap_sr_probe
  - drivers/power/avs/smartreflex.c:sr_enable
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/mmc/host/mmci.c:mmci_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_resume
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_suspend
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_show
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_remove
  - drivers/clocksource/sh_cmt.c:sh_cmt_start
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic
  - drivers/clocksource/timer-ti-dm.c:omap_dm_timer_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
  - drivers/memory/omap-gpmc.c:gpmc_resume
  - drivers/memory/omap-gpmc.c:gpmc_probe
  - drivers/memory/mtk-smi.c:mtk_smi_larb_resume
  - drivers/memory/mtk-smi.c:mtk_smi_larb_get
  - sound/soc/soc-pcm.c:soc_pcm_open
```
**Symbols:**

```
c09e6f04-c09e6fa4: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (c000000000999320)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/tty/serial/8250/8250_of.c:of_serial_resume
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
c000000000999320-c0000000009993f8: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffe00058b91c)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_wakeup
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_probe
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio.c:mmc_sdio_detect
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/mmc/core/block.c:mmc_blk_remove
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffe00058b91c-ffffffe00058b9a4: __pm_runtime_resume (STB_GLOBAL)
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
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816d2c70)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff816d2c70-ffffffff816d2cee: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff816adf60)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff816adf60-ffffffff816adfde: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff817011e0)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff817011e0-ffffffff8170125e: __pm_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pm_runtime_resume(struct device *dev, int rpmflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8171b0a0)
Location: drivers/base/power/runtime.c:1066
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_chip_pm_get
  - block/blk-core.c:blk_queue_enter
  - block/blk-core.c:blk_queue_enter
  - drivers/phy/phy-core.c:phy_pm_runtime_get_sync
  - drivers/phy/phy-core.c:phy_pm_runtime_get
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
  - drivers/pwm/pwm-lpss-pci.c:pwm_lpss_remove_pci
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_config_pm_runtime_get
  - drivers/pci/pci.c:pci_pme_list_scan
  - drivers/pci/pci.c:pci_wakeup
  - drivers/pci/pci-driver.c:pci_pm_poweroff
  - drivers/pci/pci-driver.c:pci_pm_freeze
  - drivers/pci/pci-driver.c:pci_pm_suspend
  - drivers/pci/pci-driver.c:pci_pm_complete
  - drivers/pci/pci-driver.c:pci_device_shutdown
  - drivers/pci/pci-driver.c:pci_device_remove
  - drivers/pci/pci-driver.c:local_pci_probe
  - drivers/pci/pci-sysfs.c:reset_store
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pci-acpi.c:pci_acpi_wake_dev
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_work_fn
  - drivers/pci/pcie/pme.c:pcie_pme_walk_bus
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/acpi/device_pm.c:acpi_subsys_poweroff
  - drivers/acpi/device_pm.c:acpi_subsys_freeze
  - drivers/acpi/device_pm.c:acpi_subsys_suspend
  - drivers/acpi/device_pm.c:acpi_pm_notify_work_func
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/tty/serdev/core.c:serdev_device_open
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/power/qos.c:dev_pm_qos_hide_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_update_flags
  - drivers/base/power/qos.c:dev_pm_qos_hide_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/runtime.c:pm_runtime_get_suppliers
  - drivers/base/power/runtime.c:pm_runtime_irq_safe
  - drivers/base/power/runtime.c:rpm_get_suppliers
  - drivers/base/power/domain.c:genpd_prepare
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_sync_unlock
  - drivers/mfd/arizona-core.c:arizona_clk32k_enable
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_host
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_target
  - drivers/scsi/scsi_pm.c:scsi_autopm_get_device
  - drivers/ata/libata-zpodd.c:zpodd_wake_dev
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_disconnect
  - drivers/usb/core/hcd.c:usb_hcd_platform_shutdown
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
  - drivers/usb/core/driver.c:usb_autopm_get_interface
  - drivers/usb/core/driver.c:usb_autoresume_device
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/port.c:usb_hub_remove_port_device
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/core/port.c:usb_port_runtime_resume
  - drivers/usb/host/ohci-platform.c:ohci_platform_remove
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove
  - drivers/mmc/core/core.c:mmc_get_card
  - drivers/mmc/core/core.c:__mmc_claim_host
  - drivers/mmc/core/sdio_bus.c:sdio_bus_remove
  - drivers/mmc/core/sdio_bus.c:sdio_bus_probe
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_request
```
**Symbols:**

```
ffffffff8171b0a0-ffffffff8171b0fc: __pm_runtime_resume (STB_GLOBAL)
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
