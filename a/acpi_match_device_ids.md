# Function: <code>acpi_match_device_ids</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147e9fc)
Location: drivers/acpi/bus.c:674
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/acpi_pnp.c:is_cmos_rtc_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8147e9fc-ffffffff8147ea17: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cd214)
Location: drivers/acpi/bus.c:750
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814cd214-ffffffff814cd22f: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ef142)
Location: drivers/acpi/bus.c:760
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff814ef142-ffffffff814ef15d: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fc012)
Location: drivers/acpi/bus.c:788
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff814fbfe0-ffffffff814fbffb: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153dd82)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff8153dd50-ffffffff8153dd6b: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81573e10)
Location: drivers/acpi/bus.c:845
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff81573e40-ffffffff81573e72: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158ba30)
Location: drivers/acpi/bus.c:814
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff8158ba60-ffffffff8158ba92: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc7a0)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff815bc7d0-ffffffff815bc802: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dda60)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff815dda90-ffffffff815ddac2: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688211)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff81688020-ffffffff81688052: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a5f91)
Location: drivers/acpi/bus.c:820
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff816a5d90-ffffffff816a5dc5: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688ae1)
Location: drivers/acpi/bus.c:899
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81688a90-ffffffff81688ac5: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fdf21)
Location: drivers/acpi/bus.c:901
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff816fded0-ffffffff816fdf05: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182b89d)
Location: drivers/acpi/bus.c:938
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/pci_root.c:acpi_get_pci_dev
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8182b760-ffffffff8182b787: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e22d)
Location: drivers/acpi/bus.c:945
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:match_device_ids
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8195e070-ffffffff8195e097: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a461d)
Location: drivers/acpi/bus.c:918
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/acpi_pnp.c:acpi_pnp_attach
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:match_device_ids
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff819a4230-ffffffff819a4257: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ecf6d)
Location: drivers/acpi/bus.c:968
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/utils.c:acpi_dev_match_cb
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_osc_control_set
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/acpi_pnp.c:acpi_pnp_attach
  - drivers/acpi/x86/utils.c:acpi_device_override_status
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:match_device_ids
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff819ec960-ffffffff819ec987: acpi_match_device_ids (STB_GLOBAL)
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
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010769d00)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff800010769d48-ffff800010769dac: acpi_match_device_ids (STB_GLOBAL)
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
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cff40)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff815cff70-ffffffff815cffa2: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9b00)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff815b9b30-ffffffff815b9b62: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1d40)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff815d1d70-ffffffff815d1da2: acpi_match_device_ids (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_match_device_ids(struct acpi_device *device, const struct acpi_device_id *ids);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815ebc00)
Location: drivers/acpi/bus.c:815
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_match
  - drivers/acpi/bus.c:acpi_bus_match
Direct callers:
  - drivers/acpi/device_pm.c:acpi_dev_pm_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_find_root
  - drivers/acpi/pci_root.c:acpi_is_root_bridge
  - drivers/acpi/acpi_pnp.c:acpi_is_pnp_device
  - drivers/acpi/x86/utils.c:acpi_device_always_present
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_lookup_speed
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/firmware/efi/dev-path-parser.c:match_acpi_dev
```
**Symbols:**

```
ffffffff815ebc30-ffffffff815ebc62: acpi_match_device_ids (STB_GLOBAL)
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
