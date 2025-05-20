# Function: <code>thermal_add_hwmon_sysfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81688810)
Location: drivers/thermal/thermal_hwmon.c:149
Inline: False
```
**Symbols:**

```
ffffffff81688810-ffffffff81688ab3: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff816e96f0)
Location: drivers/thermal/thermal_hwmon.c:149
Inline: False
```
**Symbols:**

```
ffffffff816e96f0-ffffffff816e9988: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff8171a550)
Location: drivers/thermal/thermal_hwmon.c:149
Inline: False
```
**Symbols:**

```
ffffffff8171a550-ffffffff8171a7e8: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81732810)
Location: drivers/thermal/thermal_hwmon.c:149
Inline: False
```
**Symbols:**

```
ffffffff81732810-ffffffff81732aa0: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff817a3980)
Location: drivers/thermal/thermal_hwmon.c:149
Inline: False
```
**Symbols:**

```
ffffffff817a3980-ffffffff817a3c13: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff817eb460)
Location: drivers/thermal/thermal_hwmon.c:126
Inline: False
```
**Symbols:**

```
ffffffff817eb460-ffffffff817eb6e4: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81817170)
Location: drivers/thermal/thermal_hwmon.c:126
Inline: False
```
**Symbols:**

```
ffffffff81817170-ffffffff818173f9: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81859390)
Location: drivers/thermal/thermal_hwmon.c:126
Inline: False
```
**Symbols:**

```
ffffffff81859390-ffffffff81859624: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff8188aea0)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff8188aea0-ffffffff8188b134: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff819598d0)
Location: drivers/thermal/thermal_hwmon.c:132
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff819598d0-ffffffff81959b5f: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (0)
Location: drivers/thermal/thermal_hwmon.c:132
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81c25cda-ffffffff81c25cf2: thermal_add_hwmon_sysfs.cold (STB_LOCAL)
ffffffff819604c0-ffffffff81960789: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (0)
Location: drivers/thermal/thermal_hwmon.c:132
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81c17dc1-ffffffff81c17dd9: thermal_add_hwmon_sysfs.cold (STB_LOCAL)
ffffffff81943a10-ffffffff81943cd9: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (0)
Location: drivers/thermal/thermal_hwmon.c:132
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81d26f96-ffffffff81d26fae: thermal_add_hwmon_sysfs.cold (STB_LOCAL)
ffffffff819e83e0-ffffffff819e86a9: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (0)
Location: drivers/thermal/thermal_hwmon.c:132
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81ef2dae-ffffffff81ef2dc6: thermal_add_hwmon_sysfs.cold (STB_LOCAL)
ffffffff81b4ddd0-ffffffff81b4e09d: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81ce5cb0)
Location: drivers/thermal/thermal_hwmon.c:140
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81ce5cb0-ffffffff81ce5f84: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81d4e280)
Location: drivers/thermal/thermal_hwmon.c:141
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81d4e280-ffffffff81d4e557: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81e04ed0)
Location: drivers/thermal/thermal_hwmon.c:138
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_hwmon.c:devm_thermal_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81e04ed0-ffffffff81e05234: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffff800010ad8b18)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffff800010ad8b18-ffff800010ad8d84: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (c0bb8f54)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
c0bb8f54-c0bb91cc: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (c000000000bbff80)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
c000000000bbff80-c000000000bc02b8: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffe0006d33e8)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffe0006d33e8-ffffffe0006d361e: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81830d20)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81830d20-ffffffff81830fb4: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff817f83b0)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff817f83b0-ffffffff817f8644: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff81880350)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81880350-ffffffff818805e4: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int thermal_add_hwmon_sysfs(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_hwmon.c (ffffffff8189bda0)
Location: drivers/thermal/thermal_hwmon.c:130
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff8189bda0-ffffffff8189c034: thermal_add_hwmon_sysfs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
