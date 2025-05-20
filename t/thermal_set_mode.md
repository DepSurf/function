# Function: <code>thermal_set_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff814b0681)
Location: drivers/acpi/thermal.c:559
Inline: False
```
**Symbols:**

```
ffffffff814b0681-ffffffff814b06de: thermal_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff814fffb4)
Location: drivers/acpi/thermal.c:559
Inline: False
```
**Symbols:**

```
ffffffff814fffb4-ffffffff81500011: thermal_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff8152300d)
Location: drivers/acpi/thermal.c:560
Inline: False
```
**Symbols:**

```
ffffffff8152300d-ffffffff8152306a: thermal_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff81535070)
Location: drivers/acpi/thermal.c:560
Inline: False
```
**Symbols:**

```
ffffffff81535070-ffffffff815350db: thermal_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffffffff815969b0)
Location: drivers/acpi/thermal.c:560
Inline: False
```
**Symbols:**

```
ffffffff815969b0-ffffffff81596a74: thermal_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:560
Inline: False
```
**Symbols:**

```
ffffffff815cdd70-ffffffff815cde21: thermal_set_mode (STB_LOCAL)
ffffffff815ce407-ffffffff815ce41a: thermal_set_mode.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:560
Inline: False
```
**Symbols:**

```
ffffffff815e7370-ffffffff815e7421: thermal_set_mode (STB_LOCAL)
ffffffff815e79e6-ffffffff815e79f9: thermal_set_mode.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:546
Inline: False
```
**Symbols:**

```
ffffffff81619000-ffffffff816190ba: thermal_set_mode (STB_LOCAL)
ffffffff81619612-ffffffff81619625: thermal_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:541
Inline: False
```
**Symbols:**

```
ffffffff8163a620-ffffffff8163a6da: thermal_set_mode (STB_LOCAL)
ffffffff8163abcb-ffffffff8163abde: thermal_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:543
Inline: False
```
**Symbols:**

```
ffffffff816e7590-ffffffff816e7649: thermal_set_mode (STB_LOCAL)
ffffffff816e7990-ffffffff816e79a3: thermal_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/thermal.c (ffff8000107a5e08)
Location: drivers/acpi/thermal.c:541
Inline: False
```
**Symbols:**

```
ffff8000107a5e08-ffff8000107a5e8c: thermal_set_mode (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:541
Inline: False
```
**Symbols:**

```
ffffffff8162e900-ffffffff8162e9ba: thermal_set_mode (STB_LOCAL)
ffffffff8162eeab-ffffffff8162eebe: thermal_set_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int thermal_set_mode(struct thermal_zone_device *thermal, enum thermal_device_mode mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/thermal.c (0)
Location: drivers/acpi/thermal.c:541
Inline: False
```
**Symbols:**

```
ffffffff816487a0-ffffffff8164885a: thermal_set_mode (STB_LOCAL)
ffffffff81648d4b-ffffffff81648d5e: thermal_set_mode.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
