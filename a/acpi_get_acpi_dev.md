# Function: <code>acpi_get_acpi_dev</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_get_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960f83)
Location: drivers/acpi/scan.c:612
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
**Symbols:**

```
ffffffff81961170-ffffffff81961202: acpi_get_acpi_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_get_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a7383)
Location: drivers/acpi/scan.c:611
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
**Symbols:**

```
ffffffff819a7580-ffffffff819a7612: acpi_get_acpi_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct acpi_device *acpi_get_acpi_dev(acpi_handle handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819efd73)
Location: drivers/acpi/scan.c:611
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev
  - drivers/acpi/scan.c:acpi_scan_clear_dep
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_notify
```
**Symbols:**

```
ffffffff819efed0-ffffffff819eff62: acpi_get_acpi_dev (STB_GLOBAL)
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
