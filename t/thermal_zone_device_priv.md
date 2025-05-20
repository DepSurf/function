# Function: <code>thermal_zone_device_priv</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *thermal_zone_device_priv(struct thermal_zone_device *tzd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d457d0)
Location: drivers/thermal/thermal_core.c:1383
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_hot
  - drivers/acpi/thermal.c:thermal_get_trend
  - drivers/acpi/thermal.c:thermal_get_crit_temp
  - drivers/acpi/thermal.c:thermal_get_trip_temp
  - drivers/acpi/thermal.c:thermal_get_trip_type
  - drivers/acpi/thermal.c:thermal_get_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
```
**Symbols:**

```
ffffffff81d457d0-ffffffff81d457e8: thermal_zone_device_priv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *thermal_zone_device_priv(struct thermal_zone_device *tzd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfc1e0)
Location: drivers/thermal/thermal_core.c:1448
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_critical
  - drivers/acpi/thermal.c:acpi_thermal_zone_device_hot
  - drivers/acpi/thermal.c:thermal_get_trend
  - drivers/acpi/thermal.c:thermal_get_temp
  - drivers/power/supply/power_supply_core.c:power_supply_read_temp
```
**Symbols:**

```
ffffffff81dfc1e0-ffffffff81dfc1f8: thermal_zone_device_priv (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
