# Function: <code>acpi_bus_decode_usb_osc</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_bus_decode_usb_osc(const char *msg, u32 bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81bf292d)
Location: drivers/acpi/bus.c:360
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81bf292d-ffffffff81bf298a: acpi_bus_decode_usb_osc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_bus_decode_usb_osc(const char *msg, u32 bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81cef2b9)
Location: drivers/acpi/bus.c:362
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81cef2b9-ffffffff81cef316: acpi_bus_decode_usb_osc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_bus_decode_usb_osc(const char *msg, u32 bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81eb6bba)
Location: drivers/acpi/bus.c:399
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81eb6bba-ffffffff81eb6c2d: acpi_bus_decode_usb_osc (STB_LOCAL)
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
In drivers/acpi/bus.c (ffffffff83ee1952)
Location: drivers/acpi/bus.c:402
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
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
In drivers/acpi/bus.c (ffffffff83707312)
Location: drivers/acpi/bus.c:399
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_init
  - drivers/acpi/bus.c:acpi_bus_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819eced3)
Location: drivers/acpi/bus.c:399
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_usb_control
  - drivers/acpi/bus.c:acpi_bus_osc_negotiate_usb_control
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
