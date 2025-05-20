# Function: <code>stop_kthread</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8116d120)
Location: kernel/trace/trace_hwlat.c:388
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff81170410)
Location: kernel/trace/trace_hwlat.c:386
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8117d5f0)
Location: kernel/trace/trace_hwlat.c:386
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8118c700)
Location: kernel/trace/trace_hwlat.c:386
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8119a070)
Location: kernel/trace/trace_hwlat.c:387
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811a7cd0)
Location: kernel/trace/trace_hwlat.c:387
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811b34d0)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
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
In kernel/trace/trace_hwlat.c (ffffffff811cbc60)
Location: kernel/trace/trace_hwlat.c:403
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
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
In kernel/trace/trace_hwlat.c (ffffffff811c92b0)
Location: kernel/trace/trace_hwlat.c:402
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
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
In kernel/trace/trace_hwlat.c (ffffffff811ca6b0)
Location: kernel/trace/trace_hwlat.c:397
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
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
void stop_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_osnoise.c (ffffffff812965d0)
Location: kernel/trace/trace_osnoise.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpu_die
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
```
**Symbols:**

```
ffffffff812965d0-ffffffff812966f4: stop_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void stop_kthread(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_osnoise.c (ffffffff812b1bd0)
Location: kernel/trace/trace_osnoise.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpu_die
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
```
**Symbols:**

```
ffffffff812b1bd0-ffffffff812b1cf4: stop_kthread (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffff8000102317f0)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
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
In kernel/trace/trace_hwlat.c (c046d334)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (c0000000002bbd30)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffe00018932e)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811abaf0)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8119e9e0)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811a98c0)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811b7700)
Location: kernel/trace/trace_hwlat.c:389
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_reset
  - kernel/trace/trace_hwlat.c:hwlat_tracer_stop
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
