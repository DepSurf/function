# Function: <code>ctx_sched_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117cbc0)
Location: kernel/events/core.c:2781
Inline: True
Direct callers:
  - kernel/events/core.c:perf_cgroup_switch
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
```
**Symbols:**

```
ffffffff8117cbc0-ffffffff8117cf97: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ee50)
Location: kernel/events/core.c:3004
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8118ee50-ffffffff8118f35d: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119e400)
Location: kernel/events/core.c:3075
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8119e400-ffffffff8119e901: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a69e0)
Location: kernel/events/core.c:3158
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811a69e0-ffffffff811a6ebc: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ba170)
Location: kernel/events/core.c:3052
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811ba170-ffffffff811ba52a: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d32e0)
Location: kernel/events/core.c:3359
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811d32e0-ffffffff811d3450: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3680)
Location: kernel/events/core.c:3354
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811e3680-ffffffff811e37f0: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa830)
Location: kernel/events/core.c:3381
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811fa830-ffffffff811fa9a0: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207900)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81207900-ffffffff81207a70: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81239b00)
Location: kernel/events/core.c:3683
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81239b00-ffffffff81239c70: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81244ba0)
Location: kernel/events/core.c:3752
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81244ba0-ffffffff81244d10: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81246550)
Location: kernel/events/core.c:3774
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81246550-ffffffff812466b2: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81285700)
Location: kernel/events/core.c:3867
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81285700-ffffffff812858a6: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d9cb0)
Location: kernel/events/core.c:3778
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff812d9cb0-ffffffff812d9e65: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813425e0)
Location: kernel/events/core.c:3870
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff813425e0-ffffffff813427e8: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81373650)
Location: kernel/events/core.c:3870
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff81373650-ffffffff8137384c: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139c550)
Location: kernel/events/core.c:3899
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:perf_event_enable_on_exec
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8139c550-ffffffff8139c6c1: ctx_sched_in (STB_LOCAL)
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
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010292110)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffff800010292110-ffff800010292278: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4688)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c04c4688-c04c4834: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003422d0)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
c0000000003422d0-c0000000003424c8: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c6384)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffe0001c6384-ffffffe0001c648e: ctx_sched_in (STB_LOCAL)
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
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fff20)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811fff20-ffffffff81200090: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2c70)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811f2c70-ffffffff811f2de0: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fdcf0)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff811fdcf0-ffffffff811fde60: ctx_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ctx_sched_in(struct perf_event_context *ctx, struct perf_cpu_context *cpuctx, enum event_type_t event_type, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cd50)
Location: kernel/events/core.c:3466
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_event_sched_in
  - kernel/events/core.c:perf_cgroup_switch
```
**Symbols:**

```
ffffffff8120cd50-ffffffff8120cec0: ctx_sched_in (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
</ul>
</details>
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
