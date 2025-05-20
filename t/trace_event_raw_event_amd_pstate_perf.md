# Function: <code>trace_event_raw_event_amd_pstate_perf</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_amd_pstate_perf(void *__data, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity, u64 freq, u64 mperf, u64 aperf, u64 tsc, unsigned int cpu_id, bool changed, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81b97980)
Location: drivers/cpufreq/amd-pstate-trace.h:25
Inline: False
```
**Symbols:**

```
ffffffff81b97980-ffffffff81b97a94: trace_event_raw_event_amd_pstate_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_amd_pstate_perf(void *__data, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity, u64 freq, u64 mperf, u64 aperf, u64 tsc, unsigned int cpu_id, bool changed, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81d38880)
Location: drivers/cpufreq/amd-pstate-trace.h:25
Inline: False
```
**Symbols:**

```
ffffffff81d38880-ffffffff81d38994: trace_event_raw_event_amd_pstate_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_amd_pstate_perf(void *__data, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity, u64 freq, u64 mperf, u64 aperf, u64 tsc, unsigned int cpu_id, bool changed, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81da3300)
Location: drivers/cpufreq/amd-pstate-trace.h:25
Inline: False
```
**Symbols:**

```
ffffffff81da3300-ffffffff81da3414: trace_event_raw_event_amd_pstate_perf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_amd_pstate_perf(void *__data, long unsigned int min_perf, long unsigned int target_perf, long unsigned int capacity, u64 freq, u64 mperf, u64 aperf, u64 tsc, unsigned int cpu_id, bool changed, bool fast_switch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cpufreq/amd-pstate-trace.c (ffffffff81e5b380)
Location: drivers/cpufreq/amd-pstate-trace.h:25
Inline: False
```
**Symbols:**

```
ffffffff81e5b380-ffffffff81e5b494: trace_event_raw_event_amd_pstate_perf (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
