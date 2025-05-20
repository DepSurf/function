# Function: <code>bind_tz</code>

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
In drivers/thermal/thermal_core.c (ffffffff81687a39)
Location: drivers/thermal/thermal_core.c:355
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
In drivers/thermal/thermal_core.c (ffffffff816e8bec)
Location: drivers/thermal/thermal_core.c:355
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
In drivers/thermal/thermal_core.c (ffffffff81716ffa)
Location: drivers/thermal/thermal_core.c:1078
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff8172e99b)
Location: drivers/thermal/thermal_core.c:1116
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff8179ffd6)
Location: drivers/thermal/thermal_core.c:1112
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff817e751f)
Location: drivers/thermal/thermal_core.c:1110
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff818137a2)
Location: drivers/thermal/thermal_core.c:1115
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff818565a3)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
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
In drivers/thermal/thermal_core.c (ffffffff81887c3b)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void bind_tz(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1158
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81955140-ffffffff819552be: bind_tz (STB_LOCAL)
ffffffff8195733b-ffffffff8195734d: bind_tz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void bind_tz(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1226
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81959dc0-ffffffff81959f3e: bind_tz (STB_LOCAL)
ffffffff81c25abc-ffffffff81c25ace: bind_tz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void bind_tz(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1167
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff8193d9e0-ffffffff8193db5e: bind_tz (STB_LOCAL)
ffffffff81c17c32-ffffffff81c17c45: bind_tz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bind_tz(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1119
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff819e2290-ffffffff819e240e: bind_tz (STB_LOCAL)
ffffffff81d26d74-ffffffff81d26d87: bind_tz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bind_tz(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:1122
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81b479c0-ffffffff81b47b53: bind_tz (STB_LOCAL)
ffffffff81ef2bf8-ffffffff81ef2c0b: bind_tz.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bind_tz(struct thermal_zone_device *tz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdf0f0)
Location: drivers/thermal/thermal_core.c:1122
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
**Symbols:**

```
ffffffff81cdf0f0-ffffffff81cdf2a4: bind_tz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d48e6c)
Location: drivers/thermal/thermal_core.c:1126
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dff286)
Location: drivers/thermal/thermal_core.c:1197
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In drivers/thermal/thermal_core.c (ffff800010ad56f4)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (c0bb49a8)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (c000000000bbb5dc)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (ffffffe0006d07bc)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (ffffffff8182dabb)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (ffffffff817f514b)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (ffffffff8187d0eb)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
In drivers/thermal/thermal_core.c (ffffffff81898b1b)
Location: drivers/thermal/thermal_core.c:1170
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
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
</ul>
