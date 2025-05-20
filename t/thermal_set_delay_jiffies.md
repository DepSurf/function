# Function: <code>thermal_set_delay_jiffies</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void thermal_set_delay_jiffies(long unsigned int *delay_jiffies, int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81942140)
Location: drivers/thermal/thermal_helpers.c:178
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81942140-ffffffff8194217a: thermal_set_delay_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void thermal_set_delay_jiffies(long unsigned int *delay_jiffies, int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff819e6a60)
Location: drivers/thermal/thermal_helpers.c:178
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff819e6a60-ffffffff819e6a9a: thermal_set_delay_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void thermal_set_delay_jiffies(long unsigned int *delay_jiffies, int delay_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_helpers.c (ffffffff81b4bf70)
Location: drivers/thermal/thermal_helpers.c:178
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
  - drivers/thermal/thermal_core.c:thermal_zone_device_register
```
**Symbols:**

```
ffffffff81b4bf70-ffffffff81b4bfaf: thermal_set_delay_jiffies (STB_GLOBAL)
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
In drivers/thermal/thermal_core.c (ffffffff81ce0a76)
Location: drivers/thermal/thermal_core.c:1162
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In drivers/thermal/thermal_core.c (ffffffff81d48c30)
Location: drivers/thermal/thermal_core.c:1145
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
In drivers/thermal/thermal_core.c (ffffffff81dff12f)
Location: drivers/thermal/thermal_core.c:1216
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
