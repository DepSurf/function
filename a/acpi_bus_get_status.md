# Function: <code>acpi_bus_get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8147ea7f)
Location: drivers/acpi/bus.c:108
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
**Symbols:**

```
ffffffff8147ea7f-ffffffff8147ead9: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814cd2da)
Location: drivers/acpi/bus.c:112
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
```
**Symbols:**

```
ffffffff814cd2da-ffffffff814cd334: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814ef208)
Location: drivers/acpi/bus.c:112
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff814ef208-ffffffff814ef262: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fc140)
Location: drivers/acpi/bus.c:112
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff814fc140-ffffffff814fc1c4: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153deb0)
Location: drivers/acpi/bus.c:139
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8153deb0-ffffffff8153dff0: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81573830)
Location: drivers/acpi/bus.c:140
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81573830-ffffffff8157398d: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158b450)
Location: drivers/acpi/bus.c:109
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8158b450-ffffffff8158b5ad: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc2b0)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815bc2b0-ffffffff815bc40d: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dd570)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815dd570-ffffffff815dd6cd: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688060)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81688060-ffffffff8168819b: acpi_bus_get_status.part.0 (STB_LOCAL)
ffffffff816881a0-ffffffff816881ff: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a5dd0)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff816a5dd0-ffffffff816a5f06: acpi_bus_get_status.part.0 (STB_LOCAL)
ffffffff816a5f10-ffffffff816a5f75: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688b10)
Location: drivers/acpi/bus.c:94
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81688b10-ffffffff81688c25: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fdf50)
Location: drivers/acpi/bus.c:96
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff816fdf50-ffffffff816fe063: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182b8d0)
Location: drivers/acpi/bus.c:97
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8182b8d0-ffffffff8182b9f7: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e270)
Location: drivers/acpi/bus.c:98
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8195e270-ffffffff8195e389: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a4660)
Location: drivers/acpi/bus.c:95
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff819a4660-ffffffff819a4779: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ecfb0)
Location: drivers/acpi/bus.c:95
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/acpi/pci_link.c:acpi_pci_link_get_current
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff819ecfb0-ffffffff819ed0c9: acpi_bus_get_status (STB_GLOBAL)
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
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010768e68)
Location: drivers/acpi/bus.c:96
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff800010768e68-ffff800010768f14: acpi_bus_get_status (STB_GLOBAL)
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
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cfb00)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815cfb00-ffffffff815cfba3: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b96c0)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815b96c0-ffffffff815b9763: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1850)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815d1850-ffffffff815d19ad: acpi_bus_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_bus_get_status(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815eb710)
Location: drivers/acpi/bus.c:96
Inline: True
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_attach
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_bus_check
  - drivers/acpi/pci_link.c:acpi_pci_link_set
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815eb710-ffffffff815eb86d: acpi_bus_get_status (STB_GLOBAL)
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
