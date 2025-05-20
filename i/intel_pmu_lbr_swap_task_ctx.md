# Function: <code>intel_pmu_lbr_swap_task_ctx</code>

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
void intel_pmu_lbr_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014530)
Location: arch/x86/events/intel/lbr.c:420
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff81014530-ffffffff81014580: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014780)
Location: arch/x86/events/intel/lbr.c:599
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff81014780-ffffffff810147f4: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810158e0)
Location: arch/x86/events/intel/lbr.c:599
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff810158e0-ffffffff8101595b: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81016ef0)
Location: arch/x86/events/intel/lbr.c:599
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff81016ef0-ffffffff81016f6b: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81019280)
Location: arch/x86/events/intel/lbr.c:578
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff81019280-ffffffff81019302: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101d1c0)
Location: arch/x86/events/intel/lbr.c:518
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff8101d1c0-ffffffff8101d233: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101cec0)
Location: arch/x86/events/intel/lbr.c:518
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff8101cec0-ffffffff8101cf33: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_lbr_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81022e50)
Location: arch/x86/events/intel/lbr.c:518
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_swap_task_ctx
```
**Symbols:**

```
ffffffff81022e50-ffffffff81022ec3: intel_pmu_lbr_swap_task_ctx (STB_GLOBAL)
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
