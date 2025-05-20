# Function: <code>__perf_pmu_sched_task</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __perf_pmu_sched_task(struct perf_cpu_context *cpuctx, bool sched_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812405f0)
Location: kernel/events/core.c:3514
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff812405f0-ffffffff812406cb: __perf_pmu_sched_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __perf_pmu_sched_task(struct perf_cpu_context *cpuctx, bool sched_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246c30)
Location: kernel/events/core.c:3536
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81246c30-ffffffff81246d0b: __perf_pmu_sched_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __perf_pmu_sched_task(struct perf_cpu_context *cpuctx, bool sched_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81280f60)
Location: kernel/events/core.c:3599
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81280f60-ffffffff8128103b: __perf_pmu_sched_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __perf_pmu_sched_task(struct perf_cpu_context *cpuctx, bool sched_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d3570)
Location: kernel/events/core.c:3510
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff812d3570-ffffffff812d3668: __perf_pmu_sched_task (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8133a0bf)
Location: kernel/events/core.c:3579
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136af9f)
Location: kernel/events/core.c:3579
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81393bdf)
Location: kernel/events/core.c:3623
Inline: True
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
