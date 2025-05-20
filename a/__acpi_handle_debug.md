# Function: <code>__acpi_handle_debug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8147af4d)
Location: drivers/acpi/utils.c:526
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff8147af4d-ffffffff8147aff3: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814c94f3)
Location: drivers/acpi/utils.c:523
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_enumerate_nondev_subnodes
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
**Symbols:**

```
ffffffff814c94f3-ffffffff814c9599: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814eb437)
Location: drivers/acpi/utils.c:523
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
**Symbols:**

```
ffffffff814eb437-ffffffff814eb4dd: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff814f74b0)
Location: drivers/acpi/utils.c:523
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff814f74b0-ffffffff814f7556: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81538750)
Location: drivers/acpi/utils.c:524
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:acpi_s2idle_wake
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/property.c:acpi_init_properties
```
**Symbols:**

```
ffffffff81538750-ffffffff815387f6: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8156e3e0)
Location: drivers/acpi/utils.c:524
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff8156e3e0-ffffffff8156e48c: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81585fa0)
Location: drivers/acpi/utils.c:524
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff81585fa0-ffffffff8158604c: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b6c30)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff815b6c30-ffffffff815b6cde: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815d7e60)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff815d7e60-ffffffff815d7f0e: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816819b0)
Location: drivers/acpi/utils.c:518
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/sleep.c:lpi_check_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_possible
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
**Symbols:**

```
ffffffff816819b0-ffffffff81681a97: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816a0540)
Location: drivers/acpi/utils.c:514
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_get_possible
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
```
**Symbols:**

```
ffffffff816a0540-ffffffff816a05ee: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81682fa0)
Location: drivers/acpi/utils.c:494
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_bus_get_acpi_device
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/power.c:acpi_power_get_state
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff81682fa0-ffffffff8168304e: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff816f80f0)
Location: drivers/acpi/utils.c:508
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:acpi_power_on_unlocked
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff816f80f0-ffffffff816f819e: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff81825210)
Location: drivers/acpi/utils.c:508
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:acpi_power_on_unlocked
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff81825210-ffffffff818252d9: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819563e0)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:acpi_power_on_unlocked
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:acpi_sleep_run_lps0_dsm
  - drivers/acpi/x86/s2idle.c:lpi_check_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff819563e0-ffffffff819564a9: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff8199c7e0)
Location: drivers/acpi/utils.c:546
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:acpi_power_on_unlocked
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal.c:acpi_thermal_get_info
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_trips_update
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
  - drivers/thermal/thermal_acpi.c:thermal_acpi_trip_temp
  - drivers/thermal/thermal_acpi.c:thermal_acpi_trip_temp
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
  - drivers/platform/x86/intel/pmc/tgl.c:pmc_core_get_tgl_lpm_reqs
```
**Symbols:**

```
ffffffff8199c7e0-ffffffff8199c8a9: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff819e49e0)
Location: drivers/acpi/utils.c:618
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/pci/hotplug/acpiphp_glue.c:hotplug_event
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/utils.c:acpi_device_dep
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_evaluate_reference
  - drivers/acpi/utils.c:acpi_get_subsystem_id
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/utils.c:acpi_evaluate_integer
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_power_up_if_adr_present
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/glue.c:acpi_device_notify
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_scan_hot_remove
  - drivers/acpi/mipi-disco-img.c:init_csi2_port
  - drivers/acpi/mipi-disco-img.c:parse_csi2_resource
  - drivers/acpi/mipi-disco-img.c:parse_csi2_resource
  - drivers/acpi/acpi_processor.c:acpi_processor_evaluate_cst
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_free_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_allocate_irq
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/pci_link.c:acpi_pci_link_check_possible
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_resume_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:acpi_power_off_unlocked
  - drivers/acpi/power.c:__acpi_power_off
  - drivers/acpi/power.c:acpi_power_on_unlocked
  - drivers/acpi/power.c:__acpi_power_on
  - drivers/acpi/power.c:__get_state
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_parse_string_ref
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:validate_dsm
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/x86/s2idle.c:lpi_device_get_constraints_amd
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/button.c:acpi_button_notify
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_evaluate_lpi
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
  - drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify_c3
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_fadt
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states
  - drivers/acpi/thermal_lib.c:acpi_trip_temp
  - drivers/acpi/thermal_lib.c:acpi_trip_temp
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/acpi/thermal.c:acpi_thermal_get_temperature
```
**Symbols:**

```
ffffffff819e49e0-ffffffff819e4ae2: __acpi_handle_debug (STB_GLOBAL)
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
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffff8000107653b8)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffff8000107653b8-ffff800010765474: __acpi_handle_debug (STB_GLOBAL)
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
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cb190)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff815cb190-ffffffff815cb23e: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815b41e0)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff815b41e0-ffffffff815b428e: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815cc140)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff815cc140-ffffffff815cc1ee: __acpi_handle_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __acpi_handle_debug(struct _ddebug *descriptor, acpi_handle handle, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/utils.c (ffffffff815e5fe0)
Location: drivers/acpi/utils.c:511
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_hotplug_notify
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/sleep.c:lpi_device_get_constraints
  - drivers/acpi/device_pm.c:__acpi_device_wakeup_enable
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_print_osc_error
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/property.c:acpi_init_properties
  - drivers/acpi/button.c:acpi_lid_notify_state
```
**Symbols:**

```
ffffffff815e5fe0-ffffffff815e608e: __acpi_handle_debug (STB_GLOBAL)
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
