# Function: <code>acpi_bus_get_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147f4b4)
Location: drivers/acpi/scan.c:577
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
**Symbols:**

```
ffffffff8147f4b4-ffffffff8147f4f6: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cdd3d)
Location: drivers/acpi/scan.c:597
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
**Symbols:**

```
ffffffff814cdd3d-ffffffff814cdd7f: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814efca2)
Location: drivers/acpi/scan.c:598
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff814efca2-ffffffff814efce4: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff820ec3e5)
Location: drivers/acpi/scan.c:596
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff814fdae0-ffffffff814fdaf0: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff826f52ca)
Location: drivers/acpi/scan.c:597
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff8153f250-ffffffff8153f262: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8271f2a8)
Location: drivers/acpi/scan.c:598
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_probe
```
**Symbols:**

```
ffffffff81575190-ffffffff815751a2: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828d7258)
Location: drivers/acpi/scan.c:598
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8158cf90-ffffffff8158cfa2: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828f10cb)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815bdd40-ffffffff815bdd52: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828fa23a)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815df000-ffffffff815df012: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff82d112be)
Location: drivers/acpi/scan.c:598
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_resources_list_add
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8168aaf0-ffffffff8168ab87: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff82ffed91)
Location: drivers/acpi/scan.c:600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_power_resources_list_add
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff816a8830-ffffffff816a88ce: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff83209d26)
Location: drivers/acpi/scan.c:592
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8168af90-ffffffff8168b045: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff832f20a8)
Location: drivers/acpi/scan.c:589
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff81700a50-ffffffff81700afe: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001147d1e8)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_get_rc_resources
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe_cluster
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff80001076bdc8-ffff80001076bdfc: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828e2f08)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff815d1b00-ffffffff815d1b10: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828daf77)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff815bb6c0-ffffffff815bb6d0: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828f5e36)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe
```
**Symbols:**

```
ffffffff815d32e0-ffffffff815d32f2: acpi_bus_get_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_device(acpi_handle handle, struct acpi_device **device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828fb28e)
Location: drivers/acpi/scan.c:599
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_walk_dep_device_list
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_online
  - drivers/acpi/scan.c:acpi_bus_offline
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_pm.c:acpi_bus_can_wakeup
  - drivers/acpi/device_pm.c:acpi_bus_power_manageable
  - drivers/acpi/device_pm.c:acpi_bus_update_power
  - drivers/acpi/device_pm.c:acpi_bus_set_power
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:show_docked
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_platform_notify
  - drivers/acpi/acpi_lpss.c:lpss_reg_read
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815ed1a0-ffffffff815ed1b2: acpi_bus_get_device (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
