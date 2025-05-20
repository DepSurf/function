# Function: <code>thermal_zone_device_register_with_trips</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register_with_trips(const char *type, struct thermal_trip *trips, int num_trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1195
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff820a7a8b-ffffffff820a7a9f: thermal_zone_device_register_with_trips.cold (STB_LOCAL)
ffffffff81ce08a0-ffffffff81ce0e1e: thermal_zone_device_register_with_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register_with_trips(const char *type, struct thermal_trip *trips, int num_trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, const struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1204
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff82128e55-ffffffff82128e69: thermal_zone_device_register_with_trips.cold (STB_LOCAL)
ffffffff81d48a40-ffffffff81d490a9: thermal_zone_device_register_with_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct thermal_zone_device *thermal_zone_device_register_with_trips(const char *type, struct thermal_trip *trips, int num_trips, int mask, void *devdata, struct thermal_zone_device_ops *ops, const struct thermal_zone_params *tzp, int passive_delay, int polling_delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1275
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
  - drivers/thermal/thermal_core.c:thermal_tripless_zone_device_register
```
**Symbols:**

```
ffffffff8220a83c-ffffffff8220a851: thermal_zone_device_register_with_trips.cold (STB_LOCAL)
ffffffff81dfeee0-ffffffff81dff511: thermal_zone_device_register_with_trips (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct thermal_zone_params *tzp</code> ➡️ <code>const struct thermal_zone_params *tzp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
