# Function: <code>perf_ctx_disable</code>

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
void perf_ctx_disable(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81338fb0)
Location: kernel/events/core.c:692
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81338fb0-ffffffff8133900e: perf_ctx_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_ctx_disable(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136a360)
Location: kernel/events/core.c:692
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8136a360-ffffffff8136a3be: perf_ctx_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_ctx_disable(struct perf_event_context *ctx, bool cgroup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813936e0)
Location: kernel/events/core.c:693
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff813936e0-ffffffff81393762: perf_ctx_disable (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool cgroup</code>
</li>
</ul>
</details>
</li>
</ul>
