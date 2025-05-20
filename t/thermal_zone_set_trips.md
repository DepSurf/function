# Function: <code>thermal_zone_set_trips</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff8171a070)
Location: drivers/thermal/thermal_helpers.c:119
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff8171a070-ffffffff8171a1ef: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81732320)
Location: drivers/thermal/thermal_helpers.c:119
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81732320-ffffffff817324b6: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff817a3470)
Location: drivers/thermal/thermal_helpers.c:119
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff817a3470-ffffffff817a3622: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff817eadf0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff817eadf0-ffffffff817eafa4: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81816cd0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81816cd0-ffffffff81816e84: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81859218-ffffffff8185922f: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff81858f10-ffffffff8185908f: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff8188acc8-ffffffff8188acdf: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff8188a9c0-ffffffff8188ab3f: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:129
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff819596ff-ffffffff81959716: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff81959580-ffffffff819596ff: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:129
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81c25c63-ffffffff81c25c7a: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff8195ec30-ffffffff8195edaf: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:129
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81c17d62-ffffffff81c17d79: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff81941fb0-ffffffff81942137: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:129
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81d26f22-ffffffff81d26f39: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff819e68e0-ffffffff819e6a60: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:129
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81ef2d3a-ffffffff81ef2d51: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff81b4bdc0-ffffffff81b4bf67: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffff800010ad85a0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffff800010ad85a0-ffff800010ad8744: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (c0bb89f4)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
c0bb89f4-c0bb8b9c: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (c000000000bbf3a0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
c000000000bbf3a0-c000000000bbf5dc: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffe0006d2fe2)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffe0006d2fe2-ffffffe0006d3118: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81830b48-ffffffff81830b5f: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff81830840-ffffffff818309bf: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff817f81d8-ffffffff817f81ef: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff817f7ed0-ffffffff817f804f: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff81880178-ffffffff8188018f: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff8187fe70-ffffffff8187ffef: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void thermal_zone_set_trips(struct thermal_zone_device *tz);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_helpers.c (0)
Location: drivers/thermal/thermal_helpers.c:116
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:trip_point_hyst_store
```
**Symbols:**

```
ffffffff8189bbc4-ffffffff8189bbdb: thermal_zone_set_trips.cold (STB_LOCAL)
ffffffff8189b8a0-ffffffff8189ba1f: thermal_zone_set_trips (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
