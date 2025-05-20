# Function: <code>acpi_fan_create_attributes</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_fan_create_attributes(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_attr.c (ffffffff8188b390)
Location: drivers/acpi/fan_attr.c:73
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff8188b390-ffffffff8188b516: acpi_fan_create_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_fan_create_attributes(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_attr.c (ffffffff819d2060)
Location: drivers/acpi/fan_attr.c:73
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff819d2060-ffffffff819d21e6: acpi_fan_create_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_fan_create_attributes(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_attr.c (ffffffff81a19660)
Location: drivers/acpi/fan_attr.c:73
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff81a19660-ffffffff81a197f4: acpi_fan_create_attributes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_fan_create_attributes(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/fan_attr.c (ffffffff81a64930)
Location: drivers/acpi/fan_attr.c:73
Inline: False
Direct callers:
  - drivers/acpi/fan_core.c:acpi_fan_probe
```
**Symbols:**

```
ffffffff81a64930-ffffffff81a64ac4: acpi_fan_create_attributes (STB_GLOBAL)
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
