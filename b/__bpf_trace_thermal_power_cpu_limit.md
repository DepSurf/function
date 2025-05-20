# Function: <code>__bpf_trace_thermal_power_cpu_limit</code>

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
void __bpf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad2708)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
ffff800010ad2708-ffff800010ad2724: __bpf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb2f28)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
c0bb2f28-c0bb2f6c: __bpf_trace_thermal_power_cpu_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_thermal_power_cpu_limit(void *__data, const struct cpumask *cpus, unsigned int freq, long unsigned int cdev_state, u32 power);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bb71b0)
Location: include/trace/events/thermal.h:125
Inline: False
```
**Symbols:**

```
c000000000bb71b0-c000000000bb71dc: __bpf_trace_thermal_power_cpu_limit (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
