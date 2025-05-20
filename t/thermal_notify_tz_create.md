# Function: <code>thermal_notify_tz_create</code>

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
int thermal_notify_tz_create(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff8195fd70)
Location: drivers/thermal/thermal_netlink.c:260
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff8195fd70-ffffffff8195fdc7: thermal_notify_tz_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_tz_create(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819432c0)
Location: drivers/thermal/thermal_netlink.c:260
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff819432c0-ffffffff81943317: thermal_notify_tz_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_tz_create(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7c90)
Location: drivers/thermal/thermal_netlink.c:260
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff819e7c90-ffffffff819e7ce7: thermal_notify_tz_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_tz_create(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d5d0)
Location: drivers/thermal/thermal_netlink.c:305
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81b4d5d0-ffffffff81b4d631: thermal_notify_tz_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_tz_create(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce5350)
Location: drivers/thermal/thermal_netlink.c:305
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
**Symbols:**

```
ffffffff81ce5350-ffffffff81ce53b1: thermal_notify_tz_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_tz_create(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4d920)
Location: drivers/thermal/thermal_netlink.c:305
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
**Symbols:**

```
ffffffff81d4d920-ffffffff81d4d981: thermal_notify_tz_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_tz_create(const struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e04640)
Location: drivers/thermal/thermal_netlink.c:307
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
**Symbols:**

```
ffffffff81e04640-ffffffff81e046a8: thermal_notify_tz_create (STB_GLOBAL)
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
<b>Param removed. </b>
<code>int tz_id</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
</ul>
</details>
</li>
</ul>
