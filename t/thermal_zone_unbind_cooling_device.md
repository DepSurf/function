# Function: <code>thermal_zone_unbind_cooling_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81684100)
Location: drivers/thermal/thermal_core.c:1383
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:passive_store
```
**Symbols:**

```
ffffffff81684100-ffffffff816842b4: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e5760)
Location: drivers/thermal/thermal_core.c:1389
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:passive_store
  - drivers/thermal/thermal_core.c:__unbind
```
**Symbols:**

```
ffffffff816e5760-ffffffff816e58fe: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817155e0)
Location: drivers/thermal/thermal_core.c:762
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff817155e0-ffffffff8171577e: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172d180)
Location: drivers/thermal/thermal_core.c:799
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff8172d180-ffffffff8172d2f6: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8179e7d0)
Location: drivers/thermal/thermal_core.c:799
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff8179e7d0-ffffffff8179e946: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e5da0)
Location: drivers/thermal/thermal_core.c:796
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff817e5da0-ffffffff817e5f15: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81811c50)
Location: drivers/thermal/thermal_core.c:800
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff81811c50-ffffffff81811dc5: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81853c90)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff81853c90-ffffffff81853e0d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818856f0)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff818856f0-ffffffff8188586d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81954290)
Location: drivers/thermal/thermal_core.c:794
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff81954290-ffffffff8195440d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81959200)
Location: drivers/thermal/thermal_core.c:862
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff81959200-ffffffff8195937d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193cd20)
Location: drivers/thermal/thermal_core.c:796
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
```
**Symbols:**

```
ffffffff8193cd20-ffffffff8193ce9d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e15c0)
Location: drivers/thermal/thermal_core.c:743
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
```
**Symbols:**

```
ffffffff819e15c0-ffffffff819e173d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b466d0)
Location: drivers/thermal/thermal_core.c:745
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
```
**Symbols:**

```
ffffffff81b466d0-ffffffff81b4684a: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81cddd20)
Location: drivers/thermal/thermal_core.c:731
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
```
**Symbols:**

```
ffffffff81cddd20-ffffffff81cdde9a: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d46000)
Location: drivers/thermal/thermal_core.c:734
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
```
**Symbols:**

```
ffffffff81d46000-ffffffff81d4617a: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip_index, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dff740)
Location: drivers/thermal/thermal_core.c:822
Inline: False
```
**Symbols:**

```
ffffffff81dff740-ffffffff81dff78c: thermal_zone_unbind_cooling_device (STB_GLOBAL)
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
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad2810)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
  - drivers/thermal/of-thermal.c:of_thermal_unbind
```
**Symbols:**

```
ffff800010ad2810-ffff800010ad2954: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb30d4)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
  - drivers/thermal/of-thermal.c:of_thermal_unbind
```
**Symbols:**

```
c0bb30d4-c0bb3200: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb7370)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
  - drivers/thermal/of-thermal.c:of_thermal_unbind
```
**Symbols:**

```
c000000000bb7370-c000000000bb7544: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006cef5a)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
  - drivers/thermal/of-thermal.c:of_thermal_unbind
```
**Symbols:**

```
ffffffe0006cef5a-ffffffe0006cf07c: thermal_zone_unbind_cooling_device (STB_GLOBAL)
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
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8182b570)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff8182b570-ffffffff8182b6ed: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817f2c00)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff817f2c00-ffffffff817f2d7d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8187aba0)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff8187aba0-ffffffff8187ad1d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int thermal_zone_unbind_cooling_device(struct thermal_zone_device *tz, int trip, struct thermal_cooling_device *cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818965a0)
Location: drivers/thermal/thermal_core.c:806
Inline: False
Direct callers:
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/acpi/thermal.c:acpi_thermal_cooling_device_cb
  - drivers/thermal/thermal_core.c:__unbind
  - drivers/thermal/thermal_core.c:thermal_zone_device_unbind_exception
```
**Symbols:**

```
ffffffff818965a0-ffffffff8189671d: thermal_zone_unbind_cooling_device (STB_GLOBAL)
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
