# Function: <code>acpi_find_child_by_adr</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_by_adr(struct acpi_device *adev, acpi_bus_address adr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff8195e8d0)
Location: drivers/acpi/glue.c:212
Inline: False
Direct callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
```
**Symbols:**

```
ffffffff8195e8d0-ffffffff8195e939: acpi_find_child_by_adr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_by_adr(struct acpi_device *adev, acpi_bus_address adr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819a4cc0)
Location: drivers/acpi/glue.c:212
Inline: False
Direct callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
```
**Symbols:**

```
ffffffff819a4cc0-ffffffff819a4d29: acpi_find_child_by_adr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_device *acpi_find_child_by_adr(struct acpi_device *adev, acpi_bus_address adr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/glue.c (ffffffff819ed610)
Location: drivers/acpi/glue.c:212
Inline: False
Direct callers:
  - drivers/usb/core/usb-acpi.c:usb_acpi_get_companion_for_port
```
**Symbols:**

```
ffffffff819ed610-ffffffff819ed679: acpi_find_child_by_adr (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
