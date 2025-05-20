# Function: <code>__thermal_zone_get_trip</code>

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
int __thermal_zone_get_trip(struct thermal_zone_device *tz, int trip_id, struct thermal_trip *trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_trip.c (ffffffff81d4b890)
Location: drivers/thermal/thermal_trip.c:103
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_show
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_show
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
  - drivers/thermal/thermal_sysfs.c:trip_point_type_show
  - drivers/thermal/thermal_trip.c:thermal_zone_set_trip
  - drivers/thermal/thermal_trip.c:thermal_zone_get_trip
  - drivers/thermal/thermal_trip.c:__thermal_zone_set_trips
  - drivers/thermal/thermal_trip.c:__for_each_thermal_trip
  - drivers/thermal/thermal_helpers.c:__thermal_zone_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
  - drivers/thermal/gov_fair_share.c:fair_share_throttle
  - drivers/thermal/gov_bang_bang.c:thermal_zone_trip_update
  - drivers/thermal/gov_step_wise.c:thermal_zone_trip_update
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:estimate_pid_constants
```
**Symbols:**

```
ffffffff81d4b890-ffffffff81d4b98c: __thermal_zone_get_trip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __thermal_zone_get_trip(struct thermal_zone_device *tz, int trip_id, struct thermal_trip *trip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_trip.c (ffffffff81e02868)
Location: drivers/thermal/thermal_trip.c:122
Inline: True
Inline callers:
  - drivers/thermal/thermal_trip.c:thermal_zone_get_trip
```
**Symbols:**

```
ffffffff81e026c0-ffffffff81e0272f: __thermal_zone_get_trip (STB_GLOBAL)
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
