# Function: <code>x86_pmu_swap_task_ctx</code>

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
void x86_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006930)
Location: arch/x86/events/core.c:2306
Inline: False
```
**Symbols:**

```
ffffffff81006930-ffffffff8100694d: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005950)
Location: arch/x86/events/core.c:2419
Inline: False
```
**Symbols:**

```
ffffffff81005950-ffffffff81005960: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005800)
Location: arch/x86/events/core.c:2639
Inline: False
```
**Symbols:**

```
ffffffff81005800-ffffffff81005810: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005e60)
Location: arch/x86/events/core.c:2638
Inline: False
```
**Symbols:**

```
ffffffff81005e60-ffffffff81005e70: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_context *prev, struct perf_event_context *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810051f0)
Location: arch/x86/events/core.c:2652
Inline: False
```
**Symbols:**

```
ffffffff810051f0-ffffffff81005208: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005d10)
Location: arch/x86/events/core.c:2633
Inline: False
```
**Symbols:**

```
ffffffff81005d10-ffffffff81005d28: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810054c0)
Location: arch/x86/events/core.c:2631
Inline: False
```
**Symbols:**

```
ffffffff810054c0-ffffffff810054d8: x86_pmu_swap_task_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void x86_pmu_swap_task_ctx(struct perf_event_pmu_context *prev_epc, struct perf_event_pmu_context *next_epc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100abc0)
Location: arch/x86/events/core.c:2628
Inline: False
```
**Symbols:**

```
ffffffff8100abc0-ffffffff8100abd8: x86_pmu_swap_task_ctx (STB_LOCAL)
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
