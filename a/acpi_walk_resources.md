# Function: <code>acpi_walk_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff814a40d1)
Location: drivers/acpi/acpica/rsxface.c:630
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff814a40d1-ffffffff814a4185: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff814f3414)
Location: drivers/acpi/acpica/rsxface.c:630
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff814f3414-ffffffff814f34ca: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81515f62)
Location: drivers/acpi/acpica/rsxface.c:630
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff81515f62-ffffffff81516018: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81526944)
Location: drivers/acpi/acpica/rsxface.c:630
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff81526944-ffffffff815269fa: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8157d9f5)
Location: drivers/acpi/acpica/rsxface.c:630
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff8157d9f5-ffffffff8157db3e: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815b4bd0)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff815b4bd0-ffffffff815b4d19: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815cdf8c)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff815cdf8c-ffffffff815ce0d5: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815ff7ef)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff815ff7ef-ffffffff815ff940: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81620c99)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff81620c99-ffffffff81620dea: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816cd0a0)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_possible
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff816cd0a0-ffffffff816cd1f1: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816eb0b7)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_possible
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff816eb0b7-ffffffff816eb208: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816ccfc9)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff816ccfc9-ffffffff816cd11a: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81744499)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff81744499-ffffffff817445ea: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8187623c)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff8187623c-ffffffff818763a4: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff819b7ac0)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff819b7ac0-ffffffff819b7c39: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff819fec10)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff819fec10-ffffffff819fed89: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81a49a90)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/mipi-disco-img.c:acpi_mipi_check_crs_csi2
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/acpica/rsxface.c:acpi_get_vendor_resource
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/char/hpet.c:hpet_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff81a49a90-ffffffff81a49c09: acpi_walk_resources (STB_GLOBAL)
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffff800010796580)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/irqchip/qcom-irq-combiner.c:combiner_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/evged.c:ged_probe
  - drivers/acpi/irq.c:acpi_irq_get
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
```
**Symbols:**

```
ffff800010796580-ffff80001079667c: acpi_walk_resources (STB_GLOBAL)
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
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815fb4d9)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff815fb4d9-ffffffff815fb59c: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815e6a09)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - drivers/hv/vmbus_drv.c:vmbus_acpi_add
  - drivers/hv/vmbus_drv.c:vmbus_acpi_add
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff815e6a09-ffffffff815e6acc: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81614f79)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff81614f79-ffffffff816150ca: acpi_walk_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_walk_resources(acpi_handle device_handle, char *name, acpi_walk_resource_callback user_function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8162ee29)
Location: drivers/acpi/acpica/rsxface.c:594
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupts
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/ec.c:ec_parse_device
  - drivers/acpi/pci_root.c:acpi_pci_root_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/acpica/dbcmds.c:acpi_db_device_resources
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/acpi/ioapic.c:handle_ioapic_add
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_build_resource_template
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_resource_option_data
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_allocated_resource
  - arch/x86/pci/mmconfig-shared.c:find_mboard_resource
```
**Symbols:**

```
ffffffff8162ee29-ffffffff8162ef7a: acpi_walk_resources (STB_GLOBAL)
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
