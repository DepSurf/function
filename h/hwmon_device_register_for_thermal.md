# Function: <code>hwmon_device_register_for_thermal</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_for_thermal(struct device *dev, const char *name, void *drvdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81b45cf0)
Location: drivers/hwmon/hwmon.c:932
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81b45cf0-ffffffff81b45d35: hwmon_device_register_for_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_for_thermal(struct device *dev, const char *name, void *drvdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81cdcf10)
Location: drivers/hwmon/hwmon.c:933
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81cdcf10-ffffffff81cdcf55: hwmon_device_register_for_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_for_thermal(struct device *dev, const char *name, void *drvdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81d45400)
Location: drivers/hwmon/hwmon.c:940
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81d45400-ffffffff81d45445: hwmon_device_register_for_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *hwmon_device_register_for_thermal(struct device *dev, const char *name, void *drvdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hwmon/hwmon.c (ffffffff81dfbe10)
Location: drivers/hwmon/hwmon.c:940
Inline: True
Direct callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81dfbe10-ffffffff81dfbe55: hwmon_device_register_for_thermal (STB_GLOBAL)
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
