# Function: <code>of_thermal_is_trip_valid</code>

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
bool of_thermal_is_trip_valid(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffff800010ad9000)
Location: drivers/thermal/of-thermal.c:142
Inline: False
```
**Symbols:**

```
ffff800010ad9000-ffff800010ad9050: of_thermal_is_trip_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool of_thermal_is_trip_valid(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c0bb9414)
Location: drivers/thermal/of-thermal.c:142
Inline: False
Direct callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_control
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_control
```
**Symbols:**

```
c0bb9414-c0bb944c: of_thermal_is_trip_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool of_thermal_is_trip_valid(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (c000000000bc0390)
Location: drivers/thermal/of-thermal.c:142
Inline: False
```
**Symbols:**

```
c000000000bc0390-c000000000bc03c8: of_thermal_is_trip_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool of_thermal_is_trip_valid(struct thermal_zone_device *tz, int trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/of-thermal.c (ffffffe0006d3836)
Location: drivers/thermal/of-thermal.c:142
Inline: False
```
**Symbols:**

```
ffffffe0006d3836-ffffffe0006d3880: of_thermal_is_trip_valid (STB_GLOBAL)
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
