# Function: <code>perf_event_sched_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117d180)
Location: kernel/events/core.c:2058
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:__perf_install_in_context
```
**Symbols:**

```
ffffffff8117d180-ffffffff8117d1fe: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118f360)
Location: kernel/events/core.c:2207
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8118f360-ffffffff8118f3de: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119e910)
Location: kernel/events/core.c:2245
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8119e910-ffffffff8119e98e: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a7060)
Location: kernel/events/core.c:2289
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811a7060-ffffffff811a70de: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ba6d0)
Location: kernel/events/core.c:2223
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811ba6d0-ffffffff811ba74e: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3450)
Location: kernel/events/core.c:2420
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811d3450-ffffffff811d34ce: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e37f0)
Location: kernel/events/core.c:2420
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811e37f0-ffffffff811e386e: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa9a0)
Location: kernel/events/core.c:2423
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811fa9a0-ffffffff811faa21: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207a70)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff81207a70-ffffffff81207af1: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81239c70)
Location: kernel/events/core.c:2657
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff81239c70-ffffffff81239cf1: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81244d10)
Location: kernel/events/core.c:2692
Inline: False
Direct callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:ctx_resched
```
**Symbols:**

```
ffffffff81244d10-ffffffff81244d91: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812466c0)
Location: kernel/events/core.c:2694
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff812466c0-ffffffff81246741: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812858b0)
Location: kernel/events/core.c:2733
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff812858b0-ffffffff81285931: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d9e70)
Location: kernel/events/core.c:2645
Inline: True
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff812d9e70-ffffffff812d9ef2: perf_event_sched_in (STB_LOCAL)
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
In kernel/events/core.c (ffffffff813428f9)
Location: kernel/events/core.c:2639
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff81373959)
Location: kernel/events/core.c:2639
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
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
In kernel/events/core.c (ffffffff8139c7dd)
Location: kernel/events/core.c:2677
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
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
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010292278)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffff800010292278-ffff800010292314: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c4834)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
c04c4834-c04c48b8: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003424d0)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
c0000000003424d0-c000000000342584: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c648e)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffe0001c648e-ffffffe0001c6510: perf_event_sched_in (STB_LOCAL)
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
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200090)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff81200090-ffffffff81200111: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f2de0)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811f2de0-ffffffff811f2e61: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fde60)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff811fde60-ffffffff811fdee1: perf_event_sched_in (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_sched_in(struct perf_cpu_context *cpuctx, struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cec0)
Location: kernel/events/core.c:2508
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
```
**Symbols:**

```
ffffffff8120cec0-ffffffff8120cf41: perf_event_sched_in (STB_LOCAL)
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
