# Function: <code>thermal_notify_tz_trip_up</code>

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
int thermal_notify_tz_trip_up(int tz_id, int trip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff8195ff50)
Location: drivers/thermal/thermal_netlink.c:295
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff8195ff50-ffffffff8195ffa6: thermal_notify_tz_trip_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_tz_trip_up(int tz_id, int trip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819434a0)
Location: drivers/thermal/thermal_netlink.c:295
Inline: False
```
**Symbols:**

```
ffffffff819434a0-ffffffff819434f6: thermal_notify_tz_trip_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_tz_trip_up(int tz_id, int trip_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7e70)
Location: drivers/thermal/thermal_netlink.c:295
Inline: False
```
**Symbols:**

```
ffffffff819e7e70-ffffffff819e7ec6: thermal_notify_tz_trip_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_tz_trip_up(int tz_id, int trip_id, int temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d7d0)
Location: drivers/thermal/thermal_netlink.c:340
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff81b4d7d0-ffffffff81b4d838: thermal_notify_tz_trip_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_tz_trip_up(int tz_id, int trip_id, int temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce55a0)
Location: drivers/thermal/thermal_netlink.c:340
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:handle_thermal_trip
```
**Symbols:**

```
ffffffff81ce55a0-ffffffff81ce5608: thermal_notify_tz_trip_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_tz_trip_up(int tz_id, int trip_id, int temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4db70)
Location: drivers/thermal/thermal_netlink.c:340
Inline: False
```
**Symbols:**

```
ffffffff81d4db70-ffffffff81d4dbd8: thermal_notify_tz_trip_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_tz_trip_up(const struct thermal_zone_device *tz, const struct thermal_trip *trip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e048a0)
Location: drivers/thermal/thermal_netlink.c:345
Inline: False
```
**Symbols:**

```
ffffffff81e048a0-ffffffff81e04919: thermal_notify_tz_trip_up (STB_GLOBAL)
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
