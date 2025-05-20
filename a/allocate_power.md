# Function: <code>allocate_power</code>

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
In drivers/thermal/power_allocator.c (ffffffff81689d3c)
Location: drivers/thermal/power_allocator.c:332
Inline: True
Inline callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff816eab10)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff816eab10-ffffffff816eb26e: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff8171ba30)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8171ba30-ffffffff8171c18e: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff81733cb0)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81733cb0-ffffffff81734431: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff817a4e70)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817a4e70-ffffffff817a55f9: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff817ec950)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817ec950-ffffffff817ed0a2: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff81818a70)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81818a70-ffffffff818191cd: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff8185ab90)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8185ab90-ffffffff8185b329: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff8188c6a0)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8188c6a0-ffffffff8188ce39: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff8195b6f0)
Location: drivers/thermal/gov_power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8195b6f0-ffffffff8195bb17: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81962360)
Location: drivers/thermal/gov_power_allocator.c:382
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81962360-ffffffff819627c9: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81945780)
Location: drivers/thermal/gov_power_allocator.c:383
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81945780-ffffffff81945cd1: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819ea1b0)
Location: drivers/thermal/gov_power_allocator.c:383
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff819ea1b0-ffffffff819ea6fe: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4fea0)
Location: drivers/thermal/gov_power_allocator.c:383
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81b4fea0-ffffffff81b50440: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce7e00)
Location: drivers/thermal/gov_power_allocator.c:382
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81ce7e00-ffffffff81ce837f: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81d505e0)
Location: drivers/thermal/gov_power_allocator.c:381
Inline: False
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81d505e0-ffffffff81d50b5f: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81e074b0)
Location: drivers/thermal/gov_power_allocator.c:398
Inline: True
Direct callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81e074b0-ffffffff81e078f5: allocate_power.constprop.0 (STB_LOCAL)
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
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffff800010adb348)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffff800010adb348-ffff800010adbab8: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (c0bbb630)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
c0bbb630-c0bbbed0: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (c000000000bc2e50)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
c000000000bc2e50-c000000000bc376c: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffe0006d54c2)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffe0006d54c2-ffffffe0006d5ae0: allocate_power (STB_LOCAL)
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
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff81832520)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81832520-ffffffff81832cb9: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff817f9bb0)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff817f9bb0-ffffffff817fa349: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff81881b50)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff81881b50-ffffffff818822e9: allocate_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int allocate_power(struct thermal_zone_device *tz, int control_temp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/power_allocator.c (ffffffff8189d5c0)
Location: drivers/thermal/power_allocator.c:332
Inline: False
Direct callers:
  - drivers/thermal/power_allocator.c:power_allocator_throttle
```
**Symbols:**

```
ffffffff8189d5c0-ffffffff8189dd86: allocate_power (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
