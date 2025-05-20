# Function: <code>thermal_notify_tz_gov_change</code>

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
int thermal_notify_tz_gov_change(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81960210)
Location: drivers/thermal/thermal_netlink.c:351
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81960210-ffffffff81960267: thermal_notify_tz_gov_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_tz_gov_change(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81943760)
Location: drivers/thermal/thermal_netlink.c:351
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81943760-ffffffff819437b7: thermal_notify_tz_gov_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_tz_gov_change(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e8130)
Location: drivers/thermal/thermal_netlink.c:351
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff819e8130-ffffffff819e8187: thermal_notify_tz_gov_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_tz_gov_change(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4dad0)
Location: drivers/thermal/thermal_netlink.c:396
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81b4dad0-ffffffff81b4db31: thermal_notify_tz_gov_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_tz_gov_change(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce5910)
Location: drivers/thermal/thermal_netlink.c:396
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81ce5910-ffffffff81ce5971: thermal_notify_tz_gov_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_tz_gov_change(int tz_id, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4dee0)
Location: drivers/thermal/thermal_netlink.c:396
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81d4dee0-ffffffff81d4df41: thermal_notify_tz_gov_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_tz_gov_change(const struct thermal_zone_device *tz, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e04b40)
Location: drivers/thermal/thermal_netlink.c:390
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_policy
```
**Symbols:**

```
ffffffff81e04b40-ffffffff81e04ba4: thermal_notify_tz_gov_change (STB_GLOBAL)
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
</ul>
</details>
</li>
</ul>
