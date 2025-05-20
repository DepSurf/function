# Function: <code>acpi_scan_add_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8147fe8a)
Location: drivers/acpi/scan.c:96
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/int340x_thermal.c:acpi_int340x_thermal_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
```
**Symbols:**

```
ffffffff8147fe8a-ffffffff8147fec2: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ce7fd)
Location: drivers/acpi/scan.c:97
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff814ce7fd-ffffffff814ce835: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f0767)
Location: drivers/acpi/scan.c:98
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff814f0767-ffffffff814f079f: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff820ec328)
Location: drivers/acpi/scan.c:92
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff814fdd10-ffffffff814fdd4a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff826f520d)
Location: drivers/acpi/scan.c:93
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff8153fb30-ffffffff8153fb6a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8271f1eb)
Location: drivers/acpi/scan.c:93
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff81575a80-ffffffff81575aba: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828d719b)
Location: drivers/acpi/scan.c:93
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff8158d6a0-ffffffff8158d6da: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828f100d)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff815be490-ffffffff815be4ca: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828fa17c)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff815df750-ffffffff815df78a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff82d111f6)
Location: drivers/acpi/scan.c:93
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff8168abd0-ffffffff8168ac0a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff82ffecc9)
Location: drivers/acpi/scan.c:93
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff816a8910-ffffffff816a894a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff83209c5a)
Location: drivers/acpi/scan.c:91
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff8168b090-ffffffff8168b0ca: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff832f1fdc)
Location: drivers/acpi/scan.c:88
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff81700b40-ffffffff81700b7a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff834aa034)
Location: drivers/acpi/scan.c:89
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff8182e7b0-ffffffff8182e7fa: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff83ee1e55)
Location: drivers/acpi/scan.c:88
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff81961280-ffffffff819612ca: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff83707815)
Location: drivers/acpi/scan.c:87
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff819a7690-ffffffff819a76da: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8393abe5)
Location: drivers/acpi/scan.c:87
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/x86/s2idle.c:acpi_s2idle_setup
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff819f0080-ffffffff819f00ca: acpi_scan_add_handler (STB_GLOBAL)
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
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001147d13c)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_amba.c:acpi_amba_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffff80001076be50-ffff80001076bea4: acpi_scan_add_handler (STB_GLOBAL)
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
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828e2e4a)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff815d1b50-ffffffff815d1b8a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828daeb9)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff815bb710-ffffffff815bb74a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828f5d78)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff815d3a30-ffffffff815d3a6a: acpi_scan_add_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_scan_add_handler(struct acpi_scan_handler *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff828fb1d0)
Location: drivers/acpi/scan.c:94
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_add_handler_with_hotplug
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
  - drivers/acpi/acpi_processor.c:acpi_processor_init
  - drivers/acpi/pci_link.c:acpi_pci_link_init
  - drivers/acpi/acpi_lpss.c:acpi_lpss_init
  - drivers/acpi/acpi_apd.c:acpi_apd_init
  - drivers/acpi/acpi_pnp.c:acpi_pnp_init
  - drivers/acpi/acpi_cmos_rtc.c:acpi_cmos_rtc_init
  - drivers/acpi/container.c:acpi_container_init
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_hotplug_init
  - drivers/acpi/dptf/int340x_thermal.c:acpi_int340x_thermal_init
```
**Symbols:**

```
ffffffff815ed8f0-ffffffff815ed92a: acpi_scan_add_handler (STB_GLOBAL)
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
