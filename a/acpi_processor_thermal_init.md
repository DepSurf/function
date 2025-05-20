# Function: <code>acpi_processor_thermal_init</code>

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
int acpi_processor_thermal_init(struct acpi_processor *pr, struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff819d35a0)
Location: drivers/acpi/processor_thermal.c:270
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff819d35a0-ffffffff819d36b4: acpi_processor_thermal_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_thermal_init(struct acpi_processor *pr, struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81a1abe0)
Location: drivers/acpi/processor_thermal.c:278
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81a1abe0-ffffffff81a1acf4: acpi_processor_thermal_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_thermal_init(struct acpi_processor *pr, struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_thermal.c (ffffffff81a65ee0)
Location: drivers/acpi/processor_thermal.c:309
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81a65ee0-ffffffff81a65ff4: acpi_processor_thermal_init (STB_GLOBAL)
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
