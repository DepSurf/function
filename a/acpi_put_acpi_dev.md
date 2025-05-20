# Function: <code>acpi_put_acpi_dev</code>

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
In drivers/acpi/device_pm.c (ffffffff8195b0e7)
Location: include/acpi/acpi_bus.h:794
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff8195d9d6)
Location: include/acpi/acpi_bus.h:794
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/scan.c (ffffffff81963147)
Location: include/acpi/acpi_bus.h:794
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/device_pm.c (ffffffff819a15b7)
Location: include/acpi/acpi_bus.h:811
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff819a3b4b)
Location: include/acpi/acpi_bus.h:811
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/scan.c (ffffffff819a95e7)
Location: include/acpi/acpi_bus.h:811
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
In drivers/acpi/device_pm.c (ffffffff819e9c67)
Location: include/acpi/acpi_bus.h:975
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff819ec27b)
Location: include/acpi/acpi_bus.h:975
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
```
In drivers/acpi/scan.c (ffffffff819f20e7)
Location: include/acpi/acpi_bus.h:975
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
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
