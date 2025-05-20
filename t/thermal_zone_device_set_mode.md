# Function: <code>thermal_zone_device_set_mode</code>

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
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a500)
Location: drivers/thermal/thermal_core.c:492
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff8195a500-ffffffff8195a5af: thermal_zone_device_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193ea30)
Location: drivers/thermal/thermal_core.c:481
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff8193ea30-ffffffff8193eb12: thermal_zone_device_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e3310)
Location: drivers/thermal/thermal_core.c:428
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff819e3310-ffffffff819e33f2: thermal_zone_device_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b48a10)
Location: drivers/thermal/thermal_core.c:430
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff81b48a10-ffffffff81b48b0a: thermal_zone_device_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdf4b0)
Location: drivers/thermal/thermal_core.c:437
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff81cdf4b0-ffffffff81cdf59f: thermal_zone_device_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d476c0)
Location: drivers/thermal/thermal_core.c:432
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff81d476c0-ffffffff81d477af: thermal_zone_device_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int thermal_zone_device_set_mode(struct thermal_zone_device *tz, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:482
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_disable
  - drivers/thermal/thermal_core.c:thermal_zone_device_enable
```
**Symbols:**

```
ffffffff81dfed70-ffffffff81dfee67: thermal_zone_device_set_mode (STB_LOCAL)
ffffffff8220a827-ffffffff8220a83c: thermal_zone_device_set_mode.cold (STB_LOCAL)
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
