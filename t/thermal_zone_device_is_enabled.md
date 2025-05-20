# Function: <code>thermal_zone_device_is_enabled</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a326)
Location: drivers/thermal/thermal_core.c:536
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff8195c740-ffffffff8195c779: thermal_zone_device_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193fc54)
Location: drivers/thermal/thermal_core.c:525
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff8193ff60-ffffffff8193ff99: thermal_zone_device_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e4594)
Location: drivers/thermal/thermal_core.c:472
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff819e4880-ffffffff819e48b9: thermal_zone_device_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b4973d)
Location: drivers/thermal/thermal_core.c:474
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_core.c:handle_thermal_trip
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff81b49a70-ffffffff81b49aaf: thermal_zone_device_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdf2f9)
Location: drivers/thermal/thermal_core.c:487
Inline: True
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff81ce11e0-ffffffff81ce11fd: thermal_zone_device_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d4739d)
Location: drivers/thermal/thermal_core.c:482
Inline: True
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff81d49450-ffffffff81d4946d: thermal_zone_device_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int thermal_zone_device_is_enabled(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfe484)
Location: drivers/thermal/thermal_core.c:526
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_resume
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
  - drivers/thermal/thermal_core.c:thermal_zone_device_check
Direct callers:
  - drivers/thermal/thermal_sysfs.c:mode_show
```
**Symbols:**

```
ffffffff81e00260-ffffffff81e0027d: thermal_zone_device_is_enabled (STB_GLOBAL)
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
