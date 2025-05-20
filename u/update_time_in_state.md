# Function: <code>update_time_in_state</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817e9fc0)
Location: drivers/thermal/thermal_sysfs.c:755
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff817e9fc0-ffffffff817e9ff2: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81815e70)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff81815e70-ffffffff81815ea2: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff818580a0)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff818580a0-ffffffff818580d2: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81889b50)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff81889b50-ffffffff81889b82: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff819588a4)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8195df44)
Location: drivers/thermal/thermal_sysfs.c:742
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff819414f4)
Location: drivers/thermal/thermal_sysfs.c:662
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff819e5d84)
Location: drivers/thermal/thermal_sysfs.c:662
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff81b4b264)
Location: drivers/thermal/thermal_sysfs.c:662
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
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
In drivers/thermal/thermal_sysfs.c (ffffffff81ce2ccd)
Location: drivers/thermal/thermal_sysfs.c:720
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
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
In drivers/thermal/thermal_sysfs.c (ffffffff81d4af5d)
Location: drivers/thermal/thermal_sysfs.c:673
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
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
In drivers/thermal/thermal_sysfs.c (ffffffff81e01c7d)
Location: drivers/thermal/thermal_sysfs.c:642
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
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
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffff800010ad74a0)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffff800010ad74a0-ffff800010ad74e4: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (c0bb7ae8)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
c0bb7ae8-c0bb7b48: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (c000000000bbddd0)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
c000000000bbddd0-c000000000bbde34: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d21cc)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffe0006d21cc-ffffffe0006d2208: update_time_in_state (STB_LOCAL)
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
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8182f9d0)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff8182f9d0-ffffffff8182fa02: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff817f7060)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff817f7060-ffffffff817f7092: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8187f000)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff8187f000-ffffffff8187f032: update_time_in_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_time_in_state(struct cooling_dev_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_sysfs.c (ffffffff8189aa80)
Location: drivers/thermal/thermal_sysfs.c:758
Inline: False
Direct callers:
  - drivers/thermal/thermal_sysfs.c:time_in_state_ms_show
  - drivers/thermal/thermal_sysfs.c:thermal_cooling_device_stats_update
```
**Symbols:**

```
ffffffff8189aa80-ffffffff8189aab2: update_time_in_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
