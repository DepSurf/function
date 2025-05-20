# Function: <code>cooling_device_stats_setup</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817ea956)
Location: drivers/thermal/thermal_sysfs.c:904
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff81816836)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff81858a86)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff8188a536)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81958760)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff81958760-ffffffff8195882a: cooling_device_stats_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8195de00)
Location: drivers/thermal/thermal_sysfs.c:894
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff8195de00-ffffffff8195deca: cooling_device_stats_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81941320)
Location: drivers/thermal/thermal_sysfs.c:814
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff81941320-ffffffff819413ea: cooling_device_stats_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff819e5c40)
Location: drivers/thermal/thermal_sysfs.c:814
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff819e5c40-ffffffff819e5d0a: cooling_device_stats_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4b150)
Location: drivers/thermal/thermal_sysfs.c:814
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff81b4b150-ffffffff81b4b239: cooling_device_stats_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81ce3435)
Location: drivers/thermal/thermal_sysfs.c:872
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81d4ae70)
Location: drivers/thermal/thermal_sysfs.c:871
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_reinit
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff81d4ae70-ffffffff81d4aef2: cooling_device_stats_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cooling_device_stats_setup(struct thermal_cooling_device *cdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81e01b90)
Location: drivers/thermal/thermal_sysfs.c:840
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_reinit
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
```
**Symbols:**

```
ffffffff81e01b90-ffffffff81e01c12: cooling_device_stats_setup (STB_LOCAL)
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
In drivers/thermal/thermal_sysfs.c (ffff800010ad7fd0)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (c0bb8518)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (c000000000bbec5c)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffe0006d2bc4)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff818303b6)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff817f7a46)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff8187f9e6)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
In drivers/thermal/thermal_sysfs.c (ffffffff8189b416)
Location: drivers/thermal/thermal_sysfs.c:907
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_setup_sysfs
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
