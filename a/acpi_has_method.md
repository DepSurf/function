# Function: <code>acpi_has_method</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147aff3)
Location: drivers/acpi/utils.c:553
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_dock_match
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8147aff3-ffffffff8147b033: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c9599)
Location: drivers/acpi/utils.c:550
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_dock_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff814c9599-ffffffff814c95d9: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb4dd)
Location: drivers/acpi/utils.c:550
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_dock_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff814eb4dd-ffffffff814eb51d: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f7560)
Location: drivers/acpi/utils.c:550
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff814f7560-ffffffff814f75a0: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538800)
Location: drivers/acpi/utils.c:551
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffffffff81538800-ffffffff81538840: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e490)
Location: drivers/acpi/utils.c:551
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8156e490-ffffffff8156e4d0: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81586050)
Location: drivers/acpi/utils.c:551
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81586050-ffffffff81586090: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6ce0)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815b6ce0-ffffffff815b6d20: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7f10)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815d7f10-ffffffff815d7f50: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81681aa0)
Location: drivers/acpi/utils.c:545
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_scan_init_hotplug
  - drivers/acpi/scan.c:acpi_scan_init_hotplug
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_init_power_state
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_has_acpi_ppc
```
**Symbols:**

```
ffffffff81681aa0-ffffffff81681ae0: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a05f0)
Location: drivers/acpi/utils.c:541
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_init_hotplug
  - drivers/acpi/scan.c:acpi_scan_init_hotplug
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_init_power_state
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_has_acpi_ppc
```
**Symbols:**

```
ffffffff816a05f0-ffffffff816a0630: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81683050)
Location: drivers/acpi/utils.c:535
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff81683050-ffffffff81683090: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f81a0)
Location: drivers/acpi/utils.c:549
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff816f81a0-ffffffff816f81e0: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff818252e0)
Location: drivers/acpi/utils.c:549
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dep
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/reset/core.c:__device_reset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
  - drivers/cpufreq/intel_pstate.c:intel_pstate_platform_pwr_mgmt_exists
```
**Symbols:**

```
ffffffff818252e0-ffffffff81825332: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956600)
Location: drivers/acpi/utils.c:587
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dep
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/reset/core.c:__device_reset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff81956600-ffffffff81956652: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199ca00)
Location: drivers/acpi/utils.c:587
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_lpss.c:acpi_lpss_dep
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/reset/core.c:__device_reset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff8199ca00-ffffffff8199ca52: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5df2)
Location: drivers/acpi/utils.c:659
Inline: True
Inline callers:
  - drivers/acpi/utils.c:acpi_device_dep
Direct callers:
  - drivers/pci/pci.c:pci_pr3_present
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/pci-acpi.c:pci_dev_acpi_reset
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpi_pcihp.c:check_hotplug
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/scan.c:acpi_bus_get_power_flags
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/fan_core.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/reset/core.c:__device_reset
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff819e4b00-ffffffff819e4b52: acpi_has_method (STB_GLOBAL)
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
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff800010765478)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
```
**Symbols:**

```
ffff800010765478-ffff8000107654e4: acpi_has_method (STB_GLOBAL)
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
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb240)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815cb240-ffffffff815cb280: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b4290)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815b4290-ffffffff815b42d0: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc1f0)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815cc1f0-ffffffff815cc230: acpi_has_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_has_method(acpi_handle handle, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e6090)
Location: drivers/acpi/utils.c:538
Inline: False
Direct callers:
  - drivers/pci/pci-acpi.c:acpi_pci_set_power_state
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_remove_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/device_sysfs.c:acpi_device_setup_files
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_device_dep_initialize
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/scan.c:acpi_ata_match
  - drivers/acpi/acpi_adxl.c:adxl_init
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/fan.c:acpi_fan_probe
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_add
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_add_device_handler
  - drivers/pnp/pnpacpi/core.c:pnpacpi_set_resources
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
```
**Symbols:**

```
ffffffff815e6090-ffffffff815e60d0: acpi_has_method (STB_GLOBAL)
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
