# Function: <code>perf_trace_thermal_power_cpu_get_power</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power, u32 static_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816859f0)
Location: include/trace/events/thermal.h:81
Inline: False
```
**Symbols:**

```
ffffffff816859f0-ffffffff81685bdb: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power, u32 static_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e7050)
Location: include/trace/events/thermal.h:93
Inline: False
```
**Symbols:**

```
ffffffff816e7050-ffffffff816e720a: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power, u32 static_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81717aa0)
Location: include/trace/events/thermal.h:93
Inline: False
```
**Symbols:**

```
ffffffff81717aa0-ffffffff81717c5a: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power, u32 static_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172fd50)
Location: include/trace/events/thermal.h:93
Inline: False
```
**Symbols:**

```
ffffffff8172fd50-ffffffff8172ff02: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
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
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad4438)
Location: include/trace/events/thermal.h:95
Inline: False
```
**Symbols:**

```
ffff800010ad4438-ffff800010ad45d0: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb608c)
Location: include/trace/events/thermal.h:95
Inline: False
```
**Symbols:**

```
c0bb608c-c0bb6224: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_get_power(void *__data, const struct cpumask *cpus, long unsigned int freq, u32 *load, size_t load_len, u32 dynamic_power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb8f10)
Location: include/trace/events/thermal.h:95
Inline: False
```
**Symbols:**

```
c000000000bb8f10-c000000000bb9140: perf_trace_thermal_power_cpu_get_power (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
