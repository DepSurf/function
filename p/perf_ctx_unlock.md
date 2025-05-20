# Function: <code>perf_ctx_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81178420)
Location: kernel/events/core.c:354
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff81178420-ffffffff81178444: perf_ctx_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811886d0)
Location: kernel/events/core.c:156
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
ffffffff811886d0-ffffffff811886f4: perf_ctx_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81197ab0)
Location: kernel/events/core.c:156
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
ffffffff81197ab0-ffffffff81197ad4: perf_ctx_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119f670)
Location: kernel/events/core.c:160
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
ffffffff8119f670-ffffffff8119f694: perf_ctx_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b3040)
Location: kernel/events/core.c:160
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
ffffffff811b3040-ffffffff811b3064: perf_ctx_unlock (STB_LOCAL)
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
In kernel/events/core.c (ffffffff811e0ad7)
Location: kernel/events/core.c:160
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff811f0f37)
Location: kernel/events/core.c:160
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff8120873f)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff81215aad)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff8123b9e6)
Location: kernel/events/core.c:166
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff81246006)
Location: kernel/events/core.c:169
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff81250873)
Location: kernel/events/core.c:170
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff8128b5c1)
Location: kernel/events/core.c:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff812dae53)
Location: kernel/events/core.c:171
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff81343128)
Location: kernel/events/core.c:166
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff81374183)
Location: kernel/events/core.c:166
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff8139d033)
Location: kernel/events/core.c:166
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_install_in_context
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029fbc8)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04bfc08)
Location: kernel/events/core.c:159
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
c04bfc08-c04bfc50: perf_ctx_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033dd50)
Location: kernel/events/core.c:159
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
c00000000033dd50-c00000000033ddf0: perf_ctx_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_ctx_unlock(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8384)
Location: kernel/events/core.c:159
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
**Symbols:**

```
ffffffe0001c8384-ffffffe0001c8438: perf_ctx_unlock (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8120e0ff)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff81200eb0)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff8120be9d)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
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
In kernel/events/core.c (ffffffff8121acff)
Location: kernel/events/core.c:159
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_pmu_sched_task
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_pmu_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:event_function
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
