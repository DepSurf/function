# Function: <code>thermal_zone_device_disable</code>

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
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a5d0)
Location: drivers/thermal/thermal_core.c:530
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff8195a5d0-ffffffff8195a5e2: thermal_zone_device_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193eb40)
Location: drivers/thermal/thermal_core.c:519
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff8193eb40-ffffffff8193eb52: thermal_zone_device_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e3420)
Location: drivers/thermal/thermal_core.c:466
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff819e3420-ffffffff819e3432: thermal_zone_device_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b48b30)
Location: drivers/thermal/thermal_core.c:468
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff81b48b30-ffffffff81b48b4a: thermal_zone_device_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdf5e0)
Location: drivers/thermal/thermal_core.c:481
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff81cdf5e0-ffffffff81cdf5fa: thermal_zone_device_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d477f0)
Location: drivers/thermal/thermal_core.c:476
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff81d477f0-ffffffff81d4780a: thermal_zone_device_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_zone_device_disable(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfeeb0)
Location: drivers/thermal/thermal_core.c:520
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_remove
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/thermal/thermal_sysfs.c:mode_store
```
**Symbols:**

```
ffffffff81dfeeb0-ffffffff81dfeeca: thermal_zone_device_disable (STB_GLOBAL)
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
