# Function: <code>__probestub_thermal_power_allocator</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __probestub_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81d4f590)
Location: drivers/thermal/thermal_trace_ipa.h:10
Inline: False
```
**Symbols:**

```
ffffffff81d4f590-ffffffff81d4f59f: __probestub_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __probestub_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 total_req_power, u32 total_granted_power, int num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81e05fb0)
Location: drivers/thermal/thermal_trace_ipa.h:10
Inline: False
```
**Symbols:**

```
ffffffff81e05fb0-ffffffff81e05fbf: __probestub_thermal_power_allocator (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 *req_power</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *granted_power</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, tz, req_power, total_req_power, granted_power, total_granted_power, num_actors, power_range, max_allocatable_power, current_temp, delta_temp</code> ➡️ <code>__data, tz, total_req_power, total_granted_power, num_actors, power_range, max_allocatable_power, current_temp, delta_temp</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t num_actors</code> ➡️ <code>int num_actors</code>
</li>
</ul>
</details>
</li>
</ul>
