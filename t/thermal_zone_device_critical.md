# Function: <code>thermal_zone_device_critical</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81c25a27)
Location: drivers/thermal/thermal_core.c:383
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81c25a27-ffffffff81c25a78: thermal_zone_device_critical (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81c17b92)
Location: drivers/thermal/thermal_core.c:378
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81c17b92-ffffffff81c17be3: thermal_zone_device_critical (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d26cae)
Location: drivers/thermal/thermal_core.c:327
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81d26cae-ffffffff81d26cdb: thermal_zone_device_critical (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ef2b0d)
Location: drivers/thermal/thermal_core.c:327
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81ef2b0d-ffffffff81ef2b44: thermal_zone_device_critical (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cddac0)
Location: drivers/thermal/thermal_core.c:317
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81cddac0-ffffffff81cddaf7: thermal_zone_device_critical (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d45fb0)
Location: drivers/thermal/thermal_core.c:316
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81d45fb0-ffffffff81d45fe7: thermal_zone_device_critical (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void thermal_zone_device_critical(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfd080)
Location: drivers/thermal/thermal_core.c:338
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
```
**Symbols:**

```
ffffffff81dfd080-ffffffff81dfd0bc: thermal_zone_device_critical (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
