# Function: <code>start_per_cpu_kthreads</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811f6ce4)
Location: kernel/trace/trace_hwlat.c:579
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
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
In kernel/trace/trace_hwlat.c (ffffffff8123080a)
Location: kernel/trace/trace_hwlat.c:575
Inline: True
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
In kernel/trace/trace_hwlat.c (ffffffff8127c93a)
Location: kernel/trace/trace_hwlat.c:575
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int start_per_cpu_kthreads(struct trace_array *tr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8129447a)
Location: kernel/trace/trace_hwlat.c:579
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297250)
Location: kernel/trace/trace_osnoise.c:2034
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
```
**Symbols:**

```
ffffffff81297250-ffffffff81297394: start_per_cpu_kthreads (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int start_per_cpu_kthreads(struct trace_array *tr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812afada)
Location: kernel/trace/trace_hwlat.c:579
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b28a0)
Location: kernel/trace/trace_osnoise.c:2034
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
  - kernel/trace/trace_osnoise.c:osnoise_options_write
```
**Symbols:**

```
ffffffff812b28a0-ffffffff812b29e4: start_per_cpu_kthreads (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
