# Function: <code>start_kthread</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8116d340)
Location: kernel/trace/trace_hwlat.c:367
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8116d340-ffffffff8116d38c: start_kthread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff81170a60)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff81170a60-ffffffff81170b4d: start_kthread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8117dc20)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8117dc20-ffffffff8117dd0d: start_kthread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8118cd20-ffffffff8118cdf3: start_kthread.isra.0 (STB_LOCAL)
ffffffff8118cf19-ffffffff8118cf3b: start_kthread.isra.0.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:349
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8119a290-ffffffff8119a377: start_kthread.isra.1 (STB_LOCAL)
ffffffff8119a872-ffffffff8119a894: start_kthread.isra.1.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:349
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811a7ef0-ffffffff811a7fd2: start_kthread.isra.0 (STB_LOCAL)
ffffffff811a84c3-ffffffff811a84fa: start_kthread.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811b36f0-ffffffff811b37d6: start_kthread.isra.0 (STB_LOCAL)
ffffffff811b3cea-ffffffff811b3d0c: start_kthread.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int start_kthread(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:365
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811cc360-ffffffff811cc449: start_kthread (STB_LOCAL)
ffffffff811cc60d-ffffffff811cc62f: start_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int start_kthread(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:365
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811c99b0-ffffffff811c9aa2: start_kthread (STB_LOCAL)
ffffffff81be5c61-ffffffff81be5c84: start_kthread.cold (STB_LOCAL)
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
In kernel/trace/trace_hwlat.c (ffffffff811cada0)
Location: kernel/trace/trace_hwlat.c:360
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
```
</details>
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
int start_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_osnoise.c (ffffffff81296fa0)
Location: kernel/trace/trace_osnoise.c:1996
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_hotplug_workfn
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
```
**Symbols:**

```
ffffffff81296fa0-ffffffff81297109: start_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int start_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_osnoise.c (ffffffff812b25f0)
Location: kernel/trace/trace_osnoise.c:1996
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_hotplug_workfn
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
```
**Symbols:**

```
ffffffff812b25f0-ffffffff812b2759: start_kthread (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffff800010231a40)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffff800010231a40-ffff800010231b54: start_kthread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (c046d58c)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (c0000000002bc030)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
c0000000002bc030-c0000000002bc1a4: start_kthread.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffe000189812)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffe000189812-ffffffe000189908: start_kthread.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811abd10-ffffffff811abdf6: start_kthread.isra.0 (STB_LOCAL)
ffffffff811ac30a-ffffffff811ac32c: start_kthread.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8119ec00-ffffffff8119ece6: start_kthread.isra.0 (STB_LOCAL)
ffffffff8119f1da-ffffffff8119f1fc: start_kthread.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811a9ae0-ffffffff811a9bc6: start_kthread.isra.0 (STB_LOCAL)
ffffffff811aa0da-ffffffff811aa0fc: start_kthread.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_hwlat.c (0)
Location: kernel/trace/trace_hwlat.c:351
Inline: True
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811b7920-ffffffff811b7a06: start_kthread.isra.0 (STB_LOCAL)
ffffffff811b7f1a-ffffffff811b7f3c: start_kthread.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
