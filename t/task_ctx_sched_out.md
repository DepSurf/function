# Function: <code>task_ctx_sched_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117c740)
Location: kernel/events/core.c:2698
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8117c740-ffffffff8117c7a3: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118e440)
Location: kernel/events/core.c:2195
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff8118e440-ffffffff8118e48f: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119de90)
Location: kernel/events/core.c:2233
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff8119de90-ffffffff8119dedf: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5860)
Location: kernel/events/core.c:2276
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff811a5860-ffffffff811a5887: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b6260)
Location: kernel/events/core.c:2210
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff811b6260-ffffffff811b6288: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d5a70)
Location: kernel/events/core.c:2407
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff811d5a70-ffffffff811d5a97: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e6110)
Location: kernel/events/core.c:2407
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff811e6110-ffffffff811e6137: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fd920)
Location: kernel/events/core.c:2410
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff811fd920-ffffffff811fd946: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120abd0)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff8120abd0-ffffffff8120abf6: task_ctx_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81240b53)
Location: kernel/events/core.c:2644
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff8124b103)
Location: kernel/events/core.c:2679
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff81251844)
Location: kernel/events/core.c:2681
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff8128d064)
Location: kernel/events/core.c:2720
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff812e1d36)
Location: kernel/events/core.c:2632
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff8134a2d6)
Location: kernel/events/core.c:2625
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff8137b316)
Location: kernel/events/core.c:2625
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff813a4516)
Location: kernel/events/core.c:2663
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:ctx_resched
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
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010299890)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffff800010299890-ffff8000102998c8: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8cb4)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
c04c8cb4-c04c8d18: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000348e60)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
c000000000348e60-c000000000348e98: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cc3dc)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffe0001cc3dc-ffffffe0001cc408: task_ctx_sched_out (STB_LOCAL)
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
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812031f0)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff812031f0-ffffffff81203216: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f5f40)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff811f5f40-ffffffff811f5f66: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200fc0)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff81200fc0-ffffffff81200fe6: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_ctx_sched_out(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, enum event_type_t event_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210170)
Location: kernel/events/core.c:2495
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff81210170-ffffffff81210196: task_ctx_sched_out (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct perf_cpu_context *cpuctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>ctx</code> ➡️ <code>cpuctx, ctx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum event_type_t event_type</code>
</li>
</ul>
</details>
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
