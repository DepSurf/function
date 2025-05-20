# Function: <code>acpi_dev_for_each_child_reverse</code>

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
int acpi_dev_for_each_child_reverse(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e6f0)
Location: drivers/acpi/bus.c:1116
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_trim_one
```
**Symbols:**

```
ffffffff8195e6f0-ffffffff8195e74b: acpi_dev_for_each_child_reverse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_dev_for_each_child_reverse(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a4ae0)
Location: drivers/acpi/bus.c:1089
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_trim_one
```
**Symbols:**

```
ffffffff819a4ae0-ffffffff819a4b3b: acpi_dev_for_each_child_reverse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_dev_for_each_child_reverse(struct acpi_device *adev, int (*fn)(struct acpi_device *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ed430)
Location: drivers/acpi/bus.c:1141
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_trim_one
```
**Symbols:**

```
ffffffff819ed430-ffffffff819ed48b: acpi_dev_for_each_child_reverse (STB_GLOBAL)
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
