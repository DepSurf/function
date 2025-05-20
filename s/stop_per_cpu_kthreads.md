# Function: <code>stop_per_cpu_kthreads</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void stop_per_cpu_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811f6a40)
Location: kernel/trace/trace_hwlat.c:478
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff811f6a40-ffffffff811f6ae0: stop_per_cpu_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void stop_per_cpu_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812304b0)
Location: kernel/trace/trace_hwlat.c:478
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff812304b0-ffffffff81230556: stop_per_cpu_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void stop_per_cpu_kthreads();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8127c750)
Location: kernel/trace/trace_hwlat.c:478
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
**Symbols:**

```
ffffffff8127c750-ffffffff8127c7fd: stop_per_cpu_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
void stop_per_cpu_kthreads();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812942a0)
Location: kernel/trace/trace_hwlat.c:478
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296f40)
Location: kernel/trace/trace_osnoise.c:1981
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:start_kthread
```
**Symbols:**

```
ffffffff812942a0-ffffffff8129434d: stop_per_cpu_kthreads (STB_LOCAL)
ffffffff81296f40-ffffffff81296f8f: stop_per_cpu_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
void stop_per_cpu_kthreads();
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812af900)
Location: kernel/trace/trace_hwlat.c:478
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_mode_write
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2590)
Location: kernel/trace/trace_osnoise.c:1981
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:start_kthread
```
**Symbols:**

```
ffffffff812af900-ffffffff812af9ad: stop_per_cpu_kthreads (STB_LOCAL)
ffffffff812b2590-ffffffff812b25df: stop_per_cpu_kthreads (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
