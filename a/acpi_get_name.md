# Function: <code>acpi_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8149ff15)
Location: drivers/acpi/acpica/nsxfname.c:158
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff8149ff15-ffffffff8149ffc4: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff814ef234)
Location: drivers/acpi/acpica/nsxfname.c:158
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff814ef234-ffffffff814ef2ed: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81511cc4)
Location: drivers/acpi/acpica/nsxfname.c:158
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff81511cc4-ffffffff81511d42: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815227aa)
Location: drivers/acpi/acpica/nsxfname.c:158
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff815227aa-ffffffff8152282b: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81576f2e)
Location: drivers/acpi/acpica/nsxfname.c:158
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff81576f2e-ffffffff81576faf: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815ade97)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff815ade97-ffffffff815adf18: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815c6e88)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff815c6e88-ffffffff815c6f09: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f8449)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff815f8449-ffffffff815f84cc: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816198ef)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff816198ef-ffffffff81619972: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c619e)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_run_oshp
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_device_path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff816c619e-ffffffff816c6221: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816e41c0)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_run_oshp
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_device_path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_ibm_smbus_match
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff816e41c0-ffffffff816e4243: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff816c6092)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff816c6092-ffffffff816c6115: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8173d3f7)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff8173d3f7-ffffffff8173d47a: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8186ee14)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff8186ee14-ffffffff8186ee9f: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff819af050)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff819af050-ffffffff819af0f2: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff819f5f40)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff819f5f40-ffffffff819f5fe2: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81a40d90)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:__acpi_handle_debug
  - drivers/acpi/utils.c:acpi_handle_printk
  - drivers/acpi/device_sysfs.c:path_show
  - drivers/acpi/device_sysfs.c:create_of_modalias
  - drivers/acpi/device_sysfs.c:data_node_show_path
  - drivers/acpi/scan.c:acpi_set_pnp_ids
  - drivers/acpi/scan.c:acpi_device_get_busid
  - drivers/acpi/mipi-disco-img.c:init_crs_csi2_swnodes
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:check_slot
```
**Symbols:**

```
ffffffff81a40d90-ffffffff81a40e32: acpi_get_name (STB_GLOBAL)
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
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffff800010791398)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffff800010791398-ffff800010791438: acpi_get_name (STB_GLOBAL)
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
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815f6a51)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff815f6a51-ffffffff815f6ad4: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff815e1f99)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
```
**Symbols:**

```
ffffffff815e1f99-ffffffff815e201c: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff8160dbcf)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff8160dbcf-ffffffff8160dc52: acpi_get_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_name(acpi_handle handle, u32 name_type, struct acpi_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfname.c (ffffffff81627a7f)
Location: drivers/acpi/acpica/nsxfname.c:124
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/utils.c:acpi_handle_path
  - drivers/acpi/utils.c:acpi_util_eval_error
  - drivers/acpi/device_sysfs.c:acpi_object_path
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/ec.c:acpi_ec_register_query_methods
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_fwnode_get_named_child_node
  - drivers/acpi/acpica/dbdisply.c:acpi_db_display_gpes
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/acpica/dbdisply.c:acpi_db_decode_and_display_object
  - drivers/acpi/pci_slot.c:register_slot
```
**Symbols:**

```
ffffffff81627a7f-ffffffff81627b02: acpi_get_name (STB_GLOBAL)
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
