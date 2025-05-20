# Function: <code>perf_trace_thermal_power_cpu_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816863c0)
Location: include/trace/events/thermal.h:113
Inline: False
```
**Symbols:**

```
ffffffff816863c0-ffffffff81686555: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e6ee0)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
ffffffff816e6ee0-ffffffff816e704e: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81717930)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
ffffffff81717930-ffffffff81717a9e: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172fbe0)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
ffffffff8172fbe0-ffffffff8172fd46: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
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
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad41b0)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
ffff800010ad41b0-ffff800010ad4308: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb57b4)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
c0bb57b4-c0bb5920: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb8d20)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
c000000000bb8d20-c000000000bb8f10: perf_trace_thermal_power_cpu_limit (STB_LOCAL)
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
