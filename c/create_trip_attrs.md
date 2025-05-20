# Function: <code>create_trip_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81687a11)
Location: drivers/thermal/thermal_core.c:1672
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e873a)
Location: drivers/thermal/thermal_core.c:1680
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817197b9)
Location: drivers/thermal/thermal_sysfs.c:512
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81731a79)
Location: drivers/thermal/thermal_sysfs.c:512
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817a2b19)
Location: drivers/thermal/thermal_sysfs.c:511
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817ea438)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff818162e8)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81858521)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81889fd1)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff819589d0)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff819589d0-ffffffff81958d8a: create_trip_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8195e070)
Location: drivers/thermal/thermal_sysfs.c:493
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff8195e070-ffffffff8195e427: create_trip_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81941590)
Location: drivers/thermal/thermal_sysfs.c:413
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff81941590-ffffffff8194194a: create_trip_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (0)
Location: drivers/thermal/thermal_sysfs.c:413
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff819e5eb0-ffffffff819e6274: create_trip_attrs (STB_LOCAL)
ffffffff81d26f09-ffffffff81d26f22: create_trip_attrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (0)
Location: drivers/thermal/thermal_sysfs.c:413
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff81b4b310-ffffffff81b4b6d0: create_trip_attrs (STB_LOCAL)
ffffffff81ef2d21-ffffffff81ef2d3a: create_trip_attrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (0)
Location: drivers/thermal/thermal_sysfs.c:473
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff81ce2d70-ffffffff81ce3130: create_trip_attrs (STB_LOCAL)
ffffffff820a7ab3-ffffffff820a7acc: create_trip_attrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (0)
Location: drivers/thermal/thermal_sysfs.c:433
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff81d4b010-ffffffff81d4b37c: create_trip_attrs (STB_LOCAL)
ffffffff82128e7d-ffffffff82128e96: create_trip_attrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int create_trip_attrs(struct thermal_zone_device *tz, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (0)
Location: drivers/thermal/thermal_sysfs.c:402
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
**Symbols:**

```
ffffffff81e01d30-ffffffff81e0209c: create_trip_attrs (STB_LOCAL)
ffffffff8220a87a-ffffffff8220a893: create_trip_attrs.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffff800010ad7a6c)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (c0bb7fd4)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (c000000000bbe520)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d2700)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8182fe51)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817f74e1)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8187f481)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8189aeb1)
Location: drivers/thermal/thermal_sysfs.c:509
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
