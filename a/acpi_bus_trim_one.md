# Function: <code>acpi_bus_trim_one</code>

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
int acpi_bus_trim_one(struct acpi_device *adev, void *not_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81960110)
Location: drivers/acpi/scan.c:2459
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_hot_remove
```
**Symbols:**

```
ffffffff81960110-ffffffff8196018a: acpi_bus_trim_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_bus_trim_one(struct acpi_device *adev, void *not_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a6500)
Location: drivers/acpi/scan.c:2503
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_hot_remove
```
**Symbols:**

```
ffffffff819a6500-ffffffff819a657a: acpi_bus_trim_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_bus_trim_one(struct acpi_device *adev, void *not_used);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819eeee0)
Location: drivers/acpi/scan.c:2553
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_device_hotplug
  - drivers/acpi/scan.c:acpi_scan_hot_remove
```
**Symbols:**

```
ffffffff819eeee0-ffffffff819eef5a: acpi_bus_trim_one (STB_LOCAL)
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
