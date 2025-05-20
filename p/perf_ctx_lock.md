# Function: <code>perf_ctx_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117c1ac)
Location: kernel/events/core.c:346
Inline: True
Inline callers:
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:__perf_install_in_context
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81195a7b)
Location: kernel/events/core.c:148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a54bd)
Location: kernel/events/core.c:148
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811acad8)
Location: kernel/events/core.c:152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811c0625)
Location: kernel/events/core.c:152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811e09d0)
Location: kernel/events/core.c:152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff811f0e30)
Location: kernel/events/core.c:152
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81208618)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81215986)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8123b8fe)
Location: kernel/events/core.c:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81245f1e)
Location: kernel/events/core.c:161
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81250778)
Location: kernel/events/core.c:162
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128b4d1)
Location: kernel/events/core.c:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dad6d)
Location: kernel/events/core.c:163
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81343050)
Location: kernel/events/core.c:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff813740a9)
Location: kernel/events/core.c:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8139cf59)
Location: kernel/events/core.c:158
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void perf_ctx_lock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010294830)
Location: kernel/events/core.c:151
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
ffff800010294830-ffff800010294860: perf_ctx_lock (STB_LOCAL)
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
In kernel/events/core.c (c04cf960)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (c000000000351018)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffe0001cf2e4)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8120dfd8)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff81200d99)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8120bd76)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
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
In kernel/events/core.c (ffffffff8121abdc)
Location: kernel/events/core.c:151
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
