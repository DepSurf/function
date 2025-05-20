# Function: <code>__pmu_ctx_sched_out</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __pmu_ctx_sched_out(struct perf_event_pmu_context *pmu_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133e710)
Location: kernel/events/core.c:3205
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff8133e710-ffffffff8133e858: __pmu_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __pmu_ctx_sched_out(struct perf_event_pmu_context *pmu_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136f720)
Location: kernel/events/core.c:3205
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff8136f720-ffffffff8136f868: __pmu_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __pmu_ctx_sched_out(struct perf_event_pmu_context *pmu_ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81398bb0)
Location: kernel/events/core.c:3243
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:ctx_sched_out
```
**Symbols:**

```
ffffffff81398bb0-ffffffff81398cf8: __pmu_ctx_sched_out (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
