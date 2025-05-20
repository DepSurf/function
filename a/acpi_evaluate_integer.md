# Function: <code>acpi_evaluate_integer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147aa2b)
Location: drivers/acpi/utils.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status_handle
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:dock_present
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/button.c:acpi_lid_send_state
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8147aa2b-ffffffff8147aab1: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c8fdc)
Location: drivers/acpi/utils.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status_handle
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/dock.c:dock_present
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814c8fdc-ffffffff814c9062: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eaf20)
Location: drivers/acpi/utils.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status_handle
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:set_processor_node_mapping
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/dock.c:dock_present
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814eaf20-ffffffff814eafa6: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f6f10)
Location: drivers/acpi/utils.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_button_add
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff814f6f10-ffffffff814f6f96: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538220)
Location: drivers/acpi/utils.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff81538220-ffffffff8153831d: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156dea0)
Location: drivers/acpi/utils.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff8156dea0-ffffffff8156dfac: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81585a60)
Location: drivers/acpi/utils.c:283
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff81585a60-ffffffff81585b6e: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6700)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
  - drivers/soundwire/slave.c:sdw_acpi_find_slaves
```
**Symbols:**

```
ffffffff815b6700-ffffffff815b6809: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7930)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff815d7930-ffffffff815d7a39: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81681650)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:processor_physically_present
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/ac.c:get_ac_property
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff81681650-ffffffff81681759: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0010)
Location: drivers/acpi/utils.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:processor_physically_present
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/ac.c:acpi_ac_add
  - drivers/acpi/ac.c:get_ac_property
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_aml_dependency_fix
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff816a0010-ffffffff816a0119: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816835b0)
Location: drivers/acpi/utils.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:hrv_show
  - drivers/acpi/device_sysfs.c:sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:uid_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff816835b0-ffffffff81683686: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f8650)
Location: drivers/acpi/utils.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_get_local_address
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:hrv_show
  - drivers/acpi/device_sysfs.c:sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:uid_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff816f8650-ffffffff816f8723: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825940)
Location: drivers/acpi/utils.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_bridge_d3
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/utils.c:acpi_get_local_address
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:hrv_show
  - drivers/acpi/device_sysfs.c:sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:uid_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
```
**Symbols:**

```
ffffffff81825940-ffffffff81825a34: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956ff0)
Location: drivers/acpi/utils.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/utils.c:acpi_get_local_address
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:hrv_show
  - drivers/acpi/device_sysfs.c:sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_power_state_for_wake
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:uid_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
```
**Symbols:**

```
ffffffff81956ff0-ffffffff819570e4: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199d3a0)
Location: drivers/acpi/utils.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/utils.c:acpi_get_local_address
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:hrv_show
  - drivers/acpi/device_sysfs.c:sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_power_state_for_wake
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:uid_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
  - drivers/thermal/thermal_acpi.c:thermal_acpi_trip_temp
```
**Symbols:**

```
ffffffff8199d3a0-ffffffff8199d4da: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5950)
Location: drivers/acpi/utils.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/utils.c:acpi_get_local_address
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:hrv_show
  - drivers/acpi/device_sysfs.c:sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_power_state_for_wake
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:processor_physically_present
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:uid_show
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/pci_slot.c:check_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal_lib.c:acpi_trip_temp
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_get_trip_points
  - drivers/acpi/thermal.c:acpi_thermal_get_trip_points
  - drivers/acpi/thermal.c:acpi_thermal_get_trip_points
  - drivers/acpi/thermal.c:acpi_thermal_get_trip_points
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/gpu/drm/drm_privacy_screen_x86.c:detect_thinkpad_privacy_screen
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_baytrail_probe_lock_support
```
**Symbols:**

```
ffffffff819e5950-ffffffff819e5a8a: acpi_evaluate_integer (STB_GLOBAL)
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
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010764d08)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/pci-acpi.c:acpi_match_rc
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_get_status
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe
  - drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe
```
**Symbols:**

```
ffff800010764d08-ffff800010764dc0: acpi_evaluate_integer (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cabe0)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815cabe0-ffffffff815cac60: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b3c30)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815b3c30-ffffffff815b3cb0: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cbc10)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff815cbc10-ffffffff815cbd19: acpi_evaluate_integer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_evaluate_integer(acpi_handle handle, acpi_string pathname, struct acpi_object_list *arguments, long long unsigned int *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e5ab0)
Location: drivers/acpi/utils.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/pci-acpi.c:acpi_pci_root_get_mcfg_addr
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:status_show
  - drivers/acpi/device_sysfs.c:acpi_device_hrv_show
  - drivers/acpi/device_sysfs.c:acpi_device_sun_show
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_dev_pm_get_state
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/glue.c:acpi_find_child_device
  - drivers/acpi/glue.c:find_child_checks
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_pdc.c:early_init_pdc
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/dock.c:show_dock_uid
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/acpi_lpss.c:byt_i2c_setup
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/button.c:acpi_lid_input_open
  - drivers/acpi/button.c:acpi_button_resume
  - drivers/acpi/button.c:acpi_lid_update_state
  - drivers/acpi/button.c:acpi_lid_open
  - drivers/acpi/button.c:acpi_button_state_seq_show
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/pci_slot.c:register_slot
  - drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit
  - drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/xen/pci.c:xen_add_device
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/intel_soc_pmic_core.c:intel_soc_pmic_i2c_probe
  - drivers/mfd/intel_soc_pmic_chtwc.c:cht_wc_probe
  - drivers/i2c/busses/i2c-designware-baytrail.c:i2c_dw_probe_lock_support
```
**Symbols:**

```
ffffffff815e5ab0-ffffffff815e5bb9: acpi_evaluate_integer (STB_GLOBAL)
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
