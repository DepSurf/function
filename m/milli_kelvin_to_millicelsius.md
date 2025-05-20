# Function: <code>milli_kelvin_to_millicelsius</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff816e7931)
Location: include/linux/units.h:9
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81704edd)
Location: include/linux/units.h:9
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff816e65b2)
Location: include/linux/units.h:13
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff8175f902)
Location: include/linux/units.h:33
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81893265)
Location: include/linux/units.h:33
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff819dac53)
Location: include/linux/units.h:36
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
In drivers/acpi/thermal.c (ffffffff81a2286f)
Location: include/linux/units.h:36
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/thermal/thermal_acpi.c (ffffffff81d4e8ed)
Location: include/linux/units.h:36
Inline: True
Inline callers:
  - drivers/thermal/thermal_acpi.c:thermal_acpi_trip_temp
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
In drivers/acpi/thermal_lib.c (ffffffff81a6bd67)
Location: include/linux/units.h:41
Inline: True
Inline callers:
  - drivers/acpi/thermal_lib.c:thermal_acpi_critical_trip_temp
  - drivers/acpi/thermal_lib.c:thermal_acpi_hot_trip_temp
  - drivers/acpi/thermal_lib.c:thermal_acpi_passive_trip_temp
  - drivers/acpi/thermal_lib.c:thermal_acpi_active_trip_temp
```
```
In drivers/acpi/thermal.c (ffffffff81a6d1ba)
Location: include/linux/units.h:41
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
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
