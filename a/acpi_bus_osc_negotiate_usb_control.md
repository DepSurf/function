# Function: <code>acpi_bus_osc_negotiate_usb_control</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff83209787)
Location: drivers/acpi/bus.c:370
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
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
In drivers/acpi/bus.c (ffffffff832f1af5)
Location: drivers/acpi/bus.c:372
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
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
In drivers/acpi/bus.c (ffffffff834a9ae7)
Location: drivers/acpi/bus.c:409
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
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
In drivers/acpi/bus.c (ffffffff83ee174f)
Location: drivers/acpi/bus.c:412
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8370710f)
Location: drivers/acpi/bus.c:409
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_bus_osc_negotiate_usb_control();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/bus.c (0)
Location: drivers/acpi/bus.c:409
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff819ecd60-ffffffff819ecf3b: acpi_bus_osc_negotiate_usb_control (STB_LOCAL)
ffffffff821efedf-ffffffff821efef3: acpi_bus_osc_negotiate_usb_control.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
</ul>
