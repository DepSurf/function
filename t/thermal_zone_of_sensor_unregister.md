# Function: <code>thermal_zone_of_sensor_unregister</code>

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
void thermal_zone_of_sensor_unregister(struct device *dev, struct thermal_zone_device *tzd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffff800010ad94a0)
Location: drivers/thermal/of-thermal.c:556
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_release
```
**Symbols:**

```
ffff800010ad94a0-ffff800010ad9514: thermal_zone_of_sensor_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void thermal_zone_of_sensor_unregister(struct device *dev, struct thermal_zone_device *tzd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c0bb9774)
Location: drivers/thermal/of-thermal.c:556
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_release
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_remove
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_probe
```
**Symbols:**

```
c0bb9774-c0bb97e8: thermal_zone_of_sensor_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void thermal_zone_of_sensor_unregister(struct device *dev, struct thermal_zone_device *tzd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c000000000bc07d0)
Location: drivers/thermal/of-thermal.c:556
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_release
```
**Symbols:**

```
c000000000bc07d0-c000000000bc0880: thermal_zone_of_sensor_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void thermal_zone_of_sensor_unregister(struct device *dev, struct thermal_zone_device *tzd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffffffe0006d3bf4)
Location: drivers/thermal/of-thermal.c:556
Inline: False
Direct callers:
  - drivers/thermal/of-thermal.c:devm_thermal_zone_of_sensor_release
```
**Symbols:**

```
ffffffe0006d3bf4-ffffffe0006d3c64: thermal_zone_of_sensor_unregister (STB_GLOBAL)
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
