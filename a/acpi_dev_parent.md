# Function: <code>acpi_dev_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195b5cf)
Location: include/acpi/acpi_bus.h:461
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
```
```
In drivers/acpi/scan.c (ffffffff81962551)
Location: include/acpi/acpi_bus.h:461
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_get_busid
```
```
In drivers/acpi/acpi_platform.c (ffffffff8197032c)
Location: include/acpi/acpi_bus.h:461
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff81976715)
Location: include/acpi/acpi_bus.h:461
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/spi/spi.c (ffffffff81bd8884)
Location: include/acpi/acpi_bus.h:461
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a1a9f)
Location: include/acpi/acpi_bus.h:464
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
```
```
In drivers/acpi/scan.c (ffffffff819a8951)
Location: include/acpi/acpi_bus.h:464
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_get_busid
```
```
In drivers/acpi/acpi_platform.c (ffffffff819b696c)
Location: include/acpi/acpi_bus.h:464
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff819bc8f5)
Location: include/acpi/acpi_bus.h:464
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/spi/spi.c (ffffffff81c2f273)
Location: include/acpi/acpi_bus.h:464
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819ea14f)
Location: include/acpi/acpi_bus.h:559
Inline: True
Inline callers:
  - drivers/acpi/device_pm.c:acpi_device_set_power
  - drivers/acpi/device_pm.c:acpi_device_get_power
```
```
In drivers/acpi/scan.c (ffffffff819f1361)
Location: include/acpi/acpi_bus.h:559
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_device_get_busid
```
```
In drivers/acpi/acpi_platform.c (ffffffff81a00f1c)
Location: include/acpi/acpi_bus.h:559
Inline: True
Inline callers:
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
```
```
In drivers/acpi/property.c (ffffffff81a071e5)
Location: include/acpi/acpi_bus.h:559
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_fwnode_get_parent
  - drivers/acpi/property.c:acpi_init_properties
```
```
In drivers/spi/spi.c (ffffffff81ce1ee3)
Location: include/acpi/acpi_bus.h:559
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
