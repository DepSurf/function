# Function: <code>acpi_walk_namespace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8149fa67)
Location: drivers/acpi/acpica/nsxfeval.c:567
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_master
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8149fa67-ffffffff8149fb37: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff814eed86)
Location: drivers/acpi/acpica/nsxfeval.c:566
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_master
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff814eed86-ffffffff814eee5b: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81511816)
Location: drivers/acpi/acpica/nsxfeval.c:566
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_core.c:acpi_set_processor_mapping
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_master
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_acpi_find_bus_speed
```
**Symbols:**

```
ffffffff81511816-ffffffff815118eb: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81521f63)
Location: drivers/acpi/acpica/nsxfeval.c:589
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_check_duplicates
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff81521f63-ffffffff81522038: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8157665e)
Location: drivers/acpi/acpica/nsxfeval.c:589
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff8157665e-ffffffff815767a2: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815ad5de)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff815ad5de-ffffffff815ad720: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815c65d5)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff815c65d5-ffffffff815c6717: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f7ed0)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff815f7ed0-ffffffff815f8017: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81619376)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff81619376-ffffffff816194bd: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c588e)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff816c588e-ffffffff816c59d5: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816e38c1)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff816e38c1-ffffffff816e3a08: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff816c5796)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff816c5796-ffffffff816c58dd: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8173cafb)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff8173cafb-ffffffff8173cc42: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8186e296)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff8186e296-ffffffff8186e3ea: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819adb00)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff819adb00-ffffffff819adc70: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff819f49c0)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff819f49c0-ffffffff819f4b30: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3f7e0)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_control_setup
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_all
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_fields
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/intel/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_find_bus_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff81a3f7e0-ffffffff81a3f950: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffff800010790dc4)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffff800010790dc4-ffff800010790eb4: acpi_walk_namespace (STB_GLOBAL)
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
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815f6554)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff815f6554-ffffffff815f6627: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff815e1aa9)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff815e1aa9-ffffffff815e1b7c: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff8160d656)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff8160d656-ffffffff8160d79d: acpi_walk_namespace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_namespace(acpi_object_type type, acpi_handle start_object, u32 max_depth, acpi_walk_callback descending_callback, acpi_walk_callback ascending_callback, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81627506)
Location: drivers/acpi/acpica/nsxfeval.c:554
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_detect_ejectable
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/acpi/scan.c:acpi_bus_scan
  - drivers/acpi/scan.c:acpi_is_video_device
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/acpi_processor.c:acpi_early_processor_osc
  - drivers/acpi/processor_pdc.c:acpi_early_processor_set_pdc
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_objects
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_handlers
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbmethod.c:acpi_db_evaluate_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_get_bus_info
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_references
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_integrity
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_check_predefined_names
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/pci_slot.c:acpi_pci_slot_enumerate
  - drivers/acpi/ioapic.c:acpi_ioapic_add
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/tty/serdev/core.c:serdev_controller_add
  - drivers/iommu/dmar.c:dmar_device_hotplug
  - drivers/spi/spi.c:spi_register_controller
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices
```
**Symbols:**

```
ffffffff81627506-ffffffff8162764d: acpi_walk_namespace (STB_GLOBAL)
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
