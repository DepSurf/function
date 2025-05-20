# Function: <code>acpi_spi_device_alloc</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct spi_device *acpi_spi_device_alloc(struct spi_controller *ctlr, struct acpi_device *adev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2460
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81eda6d9-ffffffff81eda70a: acpi_spi_device_alloc.cold (STB_LOCAL)
ffffffff81a4c400-ffffffff81a4c5ac: acpi_spi_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct spi_device *acpi_spi_device_alloc(struct spi_controller *ctlr, struct acpi_device *adev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd53b0)
Location: drivers/spi/spi.c:2637
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81bd53b0-ffffffff81bd5589: acpi_spi_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct spi_device *acpi_spi_device_alloc(struct spi_controller *ctlr, struct acpi_device *adev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2b620)
Location: drivers/spi/spi.c:2646
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81c2b620-ffffffff81c2b7f9: acpi_spi_device_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct spi_device *acpi_spi_device_alloc(struct spi_controller *ctlr, struct acpi_device *adev, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cde150)
Location: drivers/spi/spi.c:2778
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff81cde150-ffffffff81cde37e: acpi_spi_device_alloc (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
