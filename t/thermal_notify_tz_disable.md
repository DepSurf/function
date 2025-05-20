# Function: <code>thermal_notify_tz_disable</code>

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
int thermal_notify_tz_disable(int tz_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff8195fe90)
Location: drivers/thermal/thermal_netlink.c:281
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff8195fe90-ffffffff8195fee3: thermal_notify_tz_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_notify_tz_disable(int tz_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819433e0)
Location: drivers/thermal/thermal_netlink.c:281
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff819433e0-ffffffff81943433: thermal_notify_tz_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_notify_tz_disable(int tz_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff819e7db0)
Location: drivers/thermal/thermal_netlink.c:281
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff819e7db0-ffffffff819e7e03: thermal_notify_tz_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_notify_tz_disable(int tz_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81b4d700)
Location: drivers/thermal/thermal_netlink.c:326
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff81b4d700-ffffffff81b4d75d: thermal_notify_tz_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_notify_tz_disable(int tz_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81ce54b0)
Location: drivers/thermal/thermal_netlink.c:326
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff81ce54b0-ffffffff81ce550d: thermal_notify_tz_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_notify_tz_disable(int tz_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81d4da80)
Location: drivers/thermal/thermal_netlink.c:326
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff81d4da80-ffffffff81d4dadd: thermal_notify_tz_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_notify_tz_disable(const struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_netlink.c (ffffffff81e047a0)
Location: drivers/thermal/thermal_netlink.c:328
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_set_mode
```
**Symbols:**

```
ffffffff81e047a0-ffffffff81e04800: thermal_notify_tz_disable (STB_GLOBAL)
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
