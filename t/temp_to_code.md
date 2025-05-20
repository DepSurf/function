# Function: <code>temp_to_code</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/samsung/exynos_tmu.c (c0bbeb50)
Location: drivers/thermal/samsung/exynos_tmu.c:209
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_set_trip_temp
Direct callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_emulation
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos7_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos5433_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_hyst
  - drivers/thermal/samsung/exynos_tmu.c:exynos4412_tmu_set_trip_temp
  - drivers/thermal/samsung/exynos_tmu.c:exynos4210_tmu_set_trip_temp
```
**Symbols:**

```
c0bbea7c-c0bbeac4: temp_to_code.part.0 (STB_LOCAL)
```
</details>
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
