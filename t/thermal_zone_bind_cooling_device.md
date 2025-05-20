# Function: <code>thermal_zone_bind_cooling_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81686d20)
Location: drivers/thermal/thermal_core.c:1258
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:passive_store
```
**Symbols:**

```
ffffffff81686d20-ffffffff816871af: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e79c0)
Location: drivers/thermal/thermal_core.c:1264
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:passive_store
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff816e79c0-ffffffff816e7e63: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81716330)
Location: drivers/thermal/thermal_core.c:638
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff81716330-ffffffff817167d3: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172e100)
Location: drivers/thermal/thermal_core.c:674
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff8172e100-ffffffff8172e54e: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179f730)
Location: drivers/thermal/thermal_core.c:674
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff8179f730-ffffffff8179fb84: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e6d10)
Location: drivers/thermal/thermal_core.c:671
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff817e6d10-ffffffff817e7145: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81811e30)
Location: drivers/thermal/thermal_core.c:675
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff81811e30-ffffffff81812266: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81853e70)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff81853e70-ffffffff818542b7: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818858d0)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff818858d0-ffffffff81885d17: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81954b20)
Location: drivers/thermal/thermal_core.c:669
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff81954b20-ffffffff81954f67: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819597a0)
Location: drivers/thermal/thermal_core.c:737
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff819597a0-ffffffff81959be7: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193d3c0)
Location: drivers/thermal/thermal_core.c:671
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff8193d3c0-ffffffff8193d810: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e1c70)
Location: drivers/thermal/thermal_core.c:618
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff819e1c70-ffffffff819e20c0: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b473a0)
Location: drivers/thermal/thermal_core.c:620
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81b473a0-ffffffff81b477d7: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cdeaa0)
Location: drivers/thermal/thermal_core.c:611
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
```
**Symbols:**

```
ffffffff81cdeaa0-ffffffff81cdee6c: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d46f60)
Location: drivers/thermal/thermal_core.c:606
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
```
**Symbols:**

```
ffffffff81d46f60-ffffffff81d4734d: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip_index, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dffdf0)
Location: drivers/thermal/thermal_core.c:761
Inline: False
```
**Symbols:**

```
ffffffff81dffdf0-ffffffff81dffe48: thermal_zone_bind_cooling_device (STB_GLOBAL)
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad29d8)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
  - drivers/thermal/of-thermal.c:of_thermal_bind
```
**Symbols:**

```
ffff800010ad29d8-ffff800010ad2db0: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb3264)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
  - drivers/thermal/of-thermal.c:of_thermal_bind
```
**Symbols:**

```
c0bb3264-c0bb3644: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bba420)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
  - drivers/thermal/of-thermal.c:of_thermal_bind
```
**Symbols:**

```
c000000000bba420-c000000000bba9b4: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cf0ea)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
  - drivers/thermal/of-thermal.c:of_thermal_bind
```
**Symbols:**

```
ffffffe0006cf0ea-ffffffe0006cf414: thermal_zone_bind_cooling_device (STB_GLOBAL)
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
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182b750)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff8182b750-ffffffff8182bb97: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f2de0)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff817f2de0-ffffffff817f3227: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187ad80)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff8187ad80-ffffffff8187b1c7: thermal_zone_bind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int thermal_zone_bind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev, long unsigned int upper, long unsigned int lower, unsigned int weight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81896780)
Location: drivers/thermal/thermal_core.c:681
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__bind
  - drivers/thermal/thermal_core.c:thermal_zone_device_rebind_exception
```
**Symbols:**

```
ffffffff81896780-ffffffff81896bc7: thermal_zone_bind_cooling_device (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int trip_index</code>
</li>
<li>
<b>Param removed. </b>
<code>int trip</code>
</li>
</ul>
</details>
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
