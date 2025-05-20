# Function: <code>thermal_zone_of_sensor_register</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffff800010ad98d0)
Location: drivers/thermal/of-thermal.c:484
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
**Symbols:**

```
ffff800010ad98d0-ffff800010ad9b18: thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c0bb9b3c)
Location: drivers/thermal/of-thermal.c:484
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
**Symbols:**

```
c0bb9b3c-c0bb9d9c: thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c000000000bc0e60)
Location: drivers/thermal/of-thermal.c:484
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
**Symbols:**

```
c000000000bc0e60-c000000000bc1174: thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_of_sensor_register(struct device *dev, int sensor_id, void *data, const struct thermal_zone_of_device_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffffffe0006d3f66)
Location: drivers/thermal/of-thermal.c:484
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_register
```
**Symbols:**

```
ffffffe0006d3f66-ffffffe0006d4144: thermal_zone_of_sensor_register (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
