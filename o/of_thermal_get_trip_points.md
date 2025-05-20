# Function: <code>of_thermal_get_trip_points</code>

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
const struct thermal_trip *of_thermal_get_trip_points(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffff800010ad9050)
Location: drivers/thermal/of-thermal.c:164
Inline: False
Direct callers:
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
**Symbols:**

```
ffff800010ad9050-ffff800010ad9080: of_thermal_get_trip_points (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct thermal_trip *of_thermal_get_trip_points(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c0bb944c)
Location: drivers/thermal/of-thermal.c:164
Inline: False
Direct callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_initialize
  - drivers/thermal/armada_thermal.c:armada_thermal_probe
```
**Symbols:**

```
c0bb944c-c0bb9470: of_thermal_get_trip_points (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct thermal_trip *of_thermal_get_trip_points(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c000000000bc03d0)
Location: drivers/thermal/of-thermal.c:164
Inline: False
```
**Symbols:**

```
c000000000bc03d0-c000000000bc03ec: of_thermal_get_trip_points (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct thermal_trip *of_thermal_get_trip_points(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffffffe0006d3880)
Location: drivers/thermal/of-thermal.c:164
Inline: False
```
**Symbols:**

```
ffffffe0006d3880-ffffffe0006d38a8: of_thermal_get_trip_points (STB_GLOBAL)
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
