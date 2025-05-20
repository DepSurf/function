# Function: <code>thermal_zone_get_by_id</code>

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
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195c9c0)
Location: drivers/thermal/thermal_core.c:672
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff8195c9c0-ffffffff8195ca28: thermal_zone_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81940140)
Location: drivers/thermal/thermal_core.c:623
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff81940140-ffffffff819401a8: thermal_zone_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e4a60)
Location: drivers/thermal/thermal_core.c:570
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff819e4a60-ffffffff819e4ac8: thermal_zone_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b49c60)
Location: drivers/thermal/thermal_core.c:572
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff81b49c60-ffffffff81b49ccc: thermal_zone_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce13f0)
Location: drivers/thermal/thermal_core.c:563
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff81ce13f0-ffffffff81ce145c: thermal_zone_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d49660)
Location: drivers/thermal/thermal_core.c:558
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff81d49660-ffffffff81d496cc: thermal_zone_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct thermal_zone_device *thermal_zone_get_by_id(int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81e00470)
Location: drivers/thermal/thermal_core.c:599
Inline: False
Direct callers:
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_gov
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_temp
  - drivers/thermal/thermal_netlink.c:thermal_genl_cmd_tz_get_trip
```
**Symbols:**

```
ffffffff81e00470-ffffffff81e004dc: thermal_zone_get_by_id (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
