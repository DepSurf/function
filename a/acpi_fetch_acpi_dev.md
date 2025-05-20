# Function: <code>acpi_fetch_acpi_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_fetch_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff834aa0ff)
Location: drivers/acpi/scan.c:598
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
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8182e640-ffffffff8182e6cd: acpi_fetch_acpi_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_fetch_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff83ee1f06)
Location: drivers/acpi/scan.c:590
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
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
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
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff819610d0-ffffffff8196115d: acpi_fetch_acpi_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_fetch_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff837078c6)
Location: drivers/acpi/scan.c:589
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_scan
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
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff819a74e0-ffffffff819a756d: acpi_fetch_acpi_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_fetch_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8393ac96)
Location: drivers/acpi/scan.c:589
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_scan
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
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/dock.c:docked_show
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_extract_power_resources
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:__acpi_node_get_property_reference
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:bind_unbind_cdev_cb
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff819eff80-ffffffff819f000d: acpi_fetch_acpi_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
