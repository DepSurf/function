# Function: <code>acpi_handle_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147ad94)
Location: drivers/acpi/utils.c:498
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff8147ad94-ffffffff8147ae3a: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c9341)
Location: drivers/acpi/utils.c:495
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff814c9341-ffffffff814c93e7: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb285)
Location: drivers/acpi/utils.c:495
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff814eb285-ffffffff814eb32b: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f72e0)
Location: drivers/acpi/utils.c:495
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff814f72e0-ffffffff814f7386: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538580)
Location: drivers/acpi/utils.c:496
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_eject_request
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff81538580-ffffffff81538626: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e210)
Location: drivers/acpi/utils.c:496
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff8156e210-ffffffff8156e2bc: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81585dd0)
Location: drivers/acpi/utils.c:496
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff81585dd0-ffffffff81585e7c: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6a60)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff815b6a60-ffffffff815b6b0e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7c90)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff815d7c90-ffffffff815d7d3e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/utils.c (0)
Location: drivers/acpi/utils.c:487
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff81682478-ffffffff816824d0: acpi_handle_printk.cold (STB_LOCAL)
ffffffff81681fd0-ffffffff8168206c: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0370)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff816a0370-ffffffff816a041e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682d90)
Location: drivers/acpi/utils.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/ac.c:acpi_ac_get_state
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81682d90-ffffffff81682e3e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f7ee0)
Location: drivers/acpi/utils.c:477
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff816f7ee0-ffffffff816f7f8e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81824ee0)
Location: drivers/acpi/utils.c:477
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81824ee0-ffffffff81824fa9: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81956070)
Location: drivers/acpi/utils.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_tie_nondev_subnodes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff81956070-ffffffff81956139: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c470)
Location: drivers/acpi/utils.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_tie_nondev_subnodes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff8199c470-ffffffff8199c539: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e5460)
Location: drivers/acpi/utils.c:587
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/boot.c:acpi_register_ioapic
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluation_failure_warn
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_bus_extract_wakeup_device_power_package
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:extract_crs_csi2_conn_info
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/dock.c:handle_dock
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/power.c:acpi_device_sleep_wake
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_data_add_buffer_props
  - drivers/acpi/property.c:acpi_tie_nondev_subnodes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_resume
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_adjust_trip
  - drivers/acpi/thermal.c:update_trip_devices
  - drivers/acpi/thermal.c:update_trip_devices
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/battery.c:acpi_battery_get_info
  - drivers/acpi/battery.c:acpi_battery_get_info
```
**Symbols:**

```
ffffffff819e5460-ffffffff819e5562: acpi_handle_printk (STB_GLOBAL)
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
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff8000107651d8)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffff8000107651d8-ffff80001076529c: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:960
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:960
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/acpi.h:960
Inline: True
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
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cafc0)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff815cafc0-ffffffff815cb06e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b4010)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff815b4010-ffffffff815b40be: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cbf70)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff815cbf70-ffffffff815cc01e: acpi_handle_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_handle_printk(const char *level, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e5e10)
Location: drivers/acpi/utils.c:483
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_disable_and_eject_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/acpi/utils.c:acpi_evaluate_dsm
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_lck
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/utils.c:acpi_evaluate_ej0
  - drivers/acpi/device_sysfs.c:acpi_expose_nondev_subnodes
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_device_add
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_ids_walk
  - drivers/acpi/acpi_processor.c:acpi_hwp_native_thermal_lvt_osc
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/dock.c:acpi_dock_add
  - drivers/acpi/dock.c:dock_notify
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
**Symbols:**

```
ffffffff815e5e10-ffffffff815e5ebe: acpi_handle_printk (STB_GLOBAL)
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
