# Function: <code>thermal_notify_tz_trip_change</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(int tz_id, int trip_id, int trip_type, int trip_temp, int trip_hyst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81960080)
Location: drivers/thermal/thermal_netlink.c:319
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81960080-ffffffff819600e4: thermal_notify_tz_trip_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(int tz_id, int trip_id, int trip_type, int trip_temp, int trip_hyst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819435d0)
Location: drivers/thermal/thermal_netlink.c:319
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff819435d0-ffffffff81943634: thermal_notify_tz_trip_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(int tz_id, int trip_id, int trip_type, int trip_temp, int trip_hyst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7fa0)
Location: drivers/thermal/thermal_netlink.c:319
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff819e7fa0-ffffffff819e8004: thermal_notify_tz_trip_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(int tz_id, int trip_id, int trip_type, int trip_temp, int trip_hyst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d920)
Location: drivers/thermal/thermal_netlink.c:364
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81b4d920-ffffffff81b4d99b: thermal_notify_tz_trip_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(int tz_id, int trip_id, int trip_type, int trip_temp, int trip_hyst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce5720)
Location: drivers/thermal/thermal_netlink.c:364
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_temp_store
```
**Symbols:**

```
ffffffff81ce5720-ffffffff81ce579b: thermal_notify_tz_trip_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(int tz_id, int trip_id, int trip_type, int trip_temp, int trip_hyst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4dcf0)
Location: drivers/thermal/thermal_netlink.c:364
Inline: False
Direct callers:
  - drivers/thermal/thermal_trip.c:thermal_zone_set_trip
```
**Symbols:**

```
ffffffff81d4dcf0-ffffffff81d4dd6b: thermal_notify_tz_trip_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_tz_trip_change(const struct thermal_zone_device *tz, const struct thermal_trip *trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e04930)
Location: drivers/thermal/thermal_netlink.c:355
Inline: False
Direct callers:
  - drivers/thermal/thermal_trip.c:thermal_zone_set_trip_temp
  - drivers/thermal/thermal_trip.c:thermal_zone_trip_updated
```
**Symbols:**

```
ffffffff81e04930-ffffffff81e049c0: thermal_notify_tz_trip_change (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct thermal_zone_device *tz</code>
</li>
<li>
<b>Param added. </b>
<code>const struct thermal_trip *trip</code>
</li>
<li>
<b>Param removed. </b>
<code>int tz_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int trip_id</code>
</li>
<li>
<b>Param removed. </b>
<code>int trip_type</code>
</li>
<li>
<b>Param removed. </b>
<code>int trip_temp</code>
</li>
<li>
<b>Param removed. </b>
<code>int trip_hyst</code>
</li>
</ul>
</details>
</li>
</ul>
