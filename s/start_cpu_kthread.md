# Function: <code>start_cpu_kthread</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int start_cpu_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:491
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
```
**Symbols:**

```
ffffffff811f6540-ffffffff811f65f4: start_cpu_kthread (STB_LOCAL)
ffffffff81cb5e6a-ffffffff81cb5e80: start_cpu_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int start_cpu_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:491
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
```
**Symbols:**

```
ffffffff812300a0-ffffffff81230123: start_cpu_kthread (STB_LOCAL)
ffffffff81e66e8c-ffffffff81e66ea2: start_cpu_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int start_cpu_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8127c2f0)
Location: kernel/trace/trace_hwlat.c:491
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
```
**Symbols:**

```
ffffffff8127c2f0-ffffffff8127c395: start_cpu_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int start_cpu_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff81293e20)
Location: kernel/trace/trace_hwlat.c:491
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
```
**Symbols:**

```
ffffffff81293e20-ffffffff81293eec: start_cpu_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int start_cpu_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812af480)
Location: kernel/trace/trace_hwlat.c:491
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_hotplug_workfn
```
**Symbols:**

```
ffffffff812af480-ffffffff812af54c: start_cpu_kthread (STB_LOCAL)
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
