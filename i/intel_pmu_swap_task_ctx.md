# Function: <code>intel_pmu_swap_task_ctx</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d730)
Location: arch/x86/events/intel/core.c:3853
Inline: False
```
**Symbols:**

```
ffffffff8100d730-ffffffff8100d740: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c790)
Location: arch/x86/events/intel/core.c:4207
Inline: False
```
**Symbols:**

```
ffffffff8100c790-ffffffff8100c7a0: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d1b0)
Location: arch/x86/events/intel/core.c:4486
Inline: False
```
**Symbols:**

```
ffffffff8100d1b0-ffffffff8100d1c0: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d650)
Location: arch/x86/events/intel/core.c:4493
Inline: False
```
**Symbols:**

```
ffffffff8100d650-ffffffff8100d660: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e810)
Location: arch/x86/events/intel/core.c:4555
Inline: False
```
**Symbols:**

```
ffffffff8100e810-ffffffff8100e828: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81011e60)
Location: arch/x86/events/intel/core.c:4679
Inline: False
```
**Symbols:**

```
ffffffff81011e60-ffffffff81011e78: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810114f0)
Location: arch/x86/events/intel/core.c:4810
Inline: False
```
**Symbols:**

```
ffffffff810114f0-ffffffff81011508: intel_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81016c40)
Location: arch/x86/events/intel/core.c:4965
Inline: False
```
**Symbols:**

```
ffffffff81016c40-ffffffff81016c58: intel_pmu_swap_task_ctx (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_event_pmu_context *prev_epc</code>
</li>
<li>
<b>Param added. </b>
<code>struct perf_event_pmu_context *next_epc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct perf_event_context *prev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct perf_event_context *next</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
