# Function: <code>ctx_sched_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117c5e0)
Location: kernel/events/core.c:2399
Inline: False
Direct callers:
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff8117c5e0-ffffffff8117c73c: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118e1e0)
Location: kernel/events/core.c:2599
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8118e1e0-ffffffff8118e435: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119dc40)
Location: kernel/events/core.c:2663
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8119dc40-ffffffff8119de89: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5680)
Location: kernel/events/core.c:2746
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811a5680-ffffffff811a5853: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b6050)
Location: kernel/events/core.c:2658
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811b6050-ffffffff811b6251: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5850)
Location: kernel/events/core.c:2902
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811d5850-ffffffff811d5a6e: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e5ef0)
Location: kernel/events/core.c:2897
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811e5ef0-ffffffff811e610e: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd6e0)
Location: kernel/events/core.c:2915
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811fd6e0-ffffffff811fd912: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120a990)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8120a990-ffffffff8120abc2: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ac70)
Location: kernel/events/core.c:3169
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8123ac70-ffffffff8123aebc: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245130)
Location: kernel/events/core.c:3213
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81245130-ffffffff8124537c: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81249080)
Location: kernel/events/core.c:3235
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81249080-ffffffff812492c5: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812828b0)
Location: kernel/events/core.c:3293
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff812828b0-ffffffff81282b43: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d7ed0)
Location: kernel/events/core.c:3204
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff812d7ed0-ffffffff812d8197: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133e870)
Location: kernel/events/core.c:3247
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8133e870-ffffffff8133ea2b: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136f880)
Location: kernel/events/core.c:3247
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8136f880-ffffffff8136fa2d: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81398d10)
Location: kernel/events/core.c:3285
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81398d10-ffffffff81398eed: ctx_sched_out (STB_LOCAL)
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
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102996c0)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffff8000102996c0-ffff80001029988c: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8a00)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c04c8a00-c04c8cb4: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000348b90)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c000000000348b90-c000000000348e5c: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cc246)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffe0001cc246-ffffffe0001cc3dc: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202fb0)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81202fb0-ffffffff812031e2: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f5d00)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811f5d00-ffffffff811f5f32: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200d80)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81200d80-ffffffff81200fb2: ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ctx_sched_out(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ff30)
Location: kernel/events/core.c:3000
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_exit_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:task_ctx_sched_out
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8120ff30-ffffffff81210162: ctx_sched_out (STB_LOCAL)
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Param removed. </b>
<code>struct perf_cpu_context *cpuctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx, cpuctx, event_type</code> ➡️ <code>ctx, event_type</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
