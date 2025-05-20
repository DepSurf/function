# Function: <code>__traceiter_thermal_power_allocator</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819613e0)
Location: include/trace/events/thermal_power_allocator.h:10
Inline: False
```
**Symbols:**

```
ffffffff819613e0-ffffffff81961465: __traceiter_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819448f0)
Location: include/trace/events/thermal_power_allocator.h:10
Inline: False
```
**Symbols:**

```
ffffffff819448f0-ffffffff81944973: __traceiter_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff819e9320)
Location: include/trace/events/thermal_power_allocator.h:10
Inline: False
```
**Symbols:**

```
ffffffff819e9320-ffffffff819e93a3: __traceiter_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81b4eed0)
Location: include/trace/events/thermal_power_allocator.h:10
Inline: False
```
**Symbols:**

```
ffffffff81b4eed0-ffffffff81b4ef75: __traceiter_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81ce6d10)
Location: include/trace/events/thermal_power_allocator.h:10
Inline: False
```
**Symbols:**

```
ffffffff81ce6d10-ffffffff81ce6db5: __traceiter_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 *req_power, u32 total_req_power, u32 *granted_power, u32 total_granted_power, size_t num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81d4f4d0)
Location: drivers/thermal/thermal_trace_ipa.h:10
Inline: False
```
**Symbols:**

```
ffffffff81d4f4d0-ffffffff81d4f575: __traceiter_thermal_power_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_thermal_power_allocator(void *__data, struct thermal_zone_device *tz, u32 total_req_power, u32 total_granted_power, int num_actors, u32 power_range, u32 max_allocatable_power, int current_temp, s32 delta_temp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/gov_power_allocator.c (ffffffff81e05f00)
Location: drivers/thermal/thermal_trace_ipa.h:10
Inline: False
```
**Symbols:**

```
ffffffff81e05f00-ffffffff81e05f9d: __traceiter_thermal_power_allocator (STB_GLOBAL)
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
