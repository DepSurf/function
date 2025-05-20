# Function: <code>thermal_notify_tz_trip_down</code>

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
int thermal_notify_tz_trip_down(int tz_id, int trip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff8195fef0)
Location: drivers/thermal/thermal_netlink.c:288
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff8195fef0-ffffffff8195ff46: thermal_notify_tz_trip_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_tz_trip_down(int tz_id, int trip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81943440)
Location: drivers/thermal/thermal_netlink.c:288
Inline: False
```
**Symbols:**

```
ffffffff81943440-ffffffff81943496: thermal_notify_tz_trip_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_tz_trip_down(int tz_id, int trip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7e10)
Location: drivers/thermal/thermal_netlink.c:288
Inline: False
```
**Symbols:**

```
ffffffff819e7e10-ffffffff819e7e66: thermal_notify_tz_trip_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_tz_trip_down(int tz_id, int trip_id, int temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d760)
Location: drivers/thermal/thermal_netlink.c:333
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff81b4d760-ffffffff81b4d7c8: thermal_notify_tz_trip_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_tz_trip_down(int tz_id, int trip_id, int temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce5520)
Location: drivers/thermal/thermal_netlink.c:333
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff81ce5520-ffffffff81ce5588: thermal_notify_tz_trip_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_tz_trip_down(int tz_id, int trip_id, int temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4daf0)
Location: drivers/thermal/thermal_netlink.c:333
Inline: False
```
**Symbols:**

```
ffffffff81d4daf0-ffffffff81d4db58: thermal_notify_tz_trip_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_tz_trip_down(const struct thermal_zone_device *tz, const struct thermal_trip *trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e04810)
Location: drivers/thermal/thermal_netlink.c:335
Inline: False
```
**Symbols:**

```
ffffffff81e04810-ffffffff81e04889: thermal_notify_tz_trip_down (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int temp</code>
</li>
</ul>
</details>
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
<code>int temp</code>
</li>
</ul>
</details>
</li>
</ul>
