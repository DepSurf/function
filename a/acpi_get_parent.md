# Function: <code>acpi_get_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff814a0635)
Location: drivers/acpi/acpica/nsxfobj.c:120
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
```
**Symbols:**

```
ffffffff814a0635-ffffffff814a06a8: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff814ef929)
Location: drivers/acpi/acpica/nsxfobj.c:118
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff814ef929-ffffffff814ef99c: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8151237e)
Location: drivers/acpi/acpica/nsxfobj.c:118
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8151237e-ffffffff815123f1: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81522aca)
Location: drivers/acpi/acpica/nsxfobj.c:118
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff81522aca-ffffffff81522b3d: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8157724e)
Location: drivers/acpi/acpica/nsxfobj.c:118
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff8157724e-ffffffff815772c1: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815ae1b7)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815ae1b7-ffffffff815ae22a: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815c71a8)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_get_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
```
**Symbols:**

```
ffffffff815c71a8-ffffffff815c721b: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815f8acf)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815f8acf-ffffffff815f8b47: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81619f76)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/xen/pci.c:xen_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81619f76-ffffffff81619fee: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff816c64c5)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff816c64c5-ffffffff816c653d: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff816e44e7)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff816e44e7-ffffffff816e455f: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff816c63b9)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff816c63b9-ffffffff816c6431: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8173d724)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff8173d724-ffffffff8173d79c: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8186ef1b)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff8186ef1b-ffffffff8186ef96: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff819af1c0)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff819af1c0-ffffffff819af26e: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff819f60b0)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff819f60b0-ffffffff819f615e: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81a40f00)
Location: drivers/acpi/acpica/nsxfobj.c:83
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_bay_match
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/numa/srat.c:acpi_get_node
  - drivers/xen/pci.c:xen_add_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_spi_device_alloc
```
**Symbols:**

```
ffffffff81a40f00-ffffffff81a40fae: acpi_get_parent (STB_GLOBAL)
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
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffff800010791a6c)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffff800010791a6c-ffff800010791afc: acpi_get_parent (STB_GLOBAL)
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
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815f70d8)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/xen/pci.c:xen_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815f70d8-ffffffff815f7150: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff815e2617)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815e2617-ffffffff815e268f: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff8160e256)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/xen/pci.c:xen_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff8160e256-ffffffff8160e2ce: acpi_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_parent(acpi_handle handle, acpi_handle *ret_handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsxfobj.c (ffffffff81628106)
Location: drivers/acpi/acpica/nsxfobj.c:82
Inline: True
Direct callers:
  - drivers/pci/pci-acpi.c:pci_acpi_program_hp_params
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_pci_check_ejectable
  - drivers/pci/hotplug/acpi_pcihp.c:acpi_get_hp_hw_control_from_firmware
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/property.c:acpi_node_get_parent
  - drivers/acpi/numa.c:acpi_get_node
  - drivers/acpi/acpica/hwpci.c:acpi_hw_derive_pci_id
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_lpi_info
  - drivers/xen/pci.c:xen_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81628106-ffffffff8162817e: acpi_get_parent (STB_GLOBAL)
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
