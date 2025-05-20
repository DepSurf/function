# Function: <code>acpi_device_override_status</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_device_override_status(struct acpi_device *adev, long long unsigned int *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81711be0)
Location: drivers/acpi/x86/utils.c:139
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff81711be0-ffffffff81711e30: acpi_device_override_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_device_override_status(struct acpi_device *adev, long long unsigned int *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81840ef0)
Location: drivers/acpi/x86/utils.c:148
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff81840ef0-ffffffff81841148: acpi_device_override_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_device_override_status(struct acpi_device *adev, long long unsigned int *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81977940)
Location: drivers/acpi/x86/utils.c:148
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff81977940-ffffffff81977b98: acpi_device_override_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_device_override_status(struct acpi_device *adev, long long unsigned int *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff819be490)
Location: drivers/acpi/x86/utils.c:158
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff819be490-ffffffff819be6e4: acpi_device_override_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_device_override_status(struct acpi_device *adev, long long unsigned int *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/utils.c (ffffffff81a08d80)
Location: drivers/acpi/x86/utils.c:158
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_get_status
```
**Symbols:**

```
ffffffff81a08d80-ffffffff81a08fcd: acpi_device_override_status (STB_GLOBAL)
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
