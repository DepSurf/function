# Function: <code>perf_event_context_sched_out</code>

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
In kernel/events/core.c (ffffffff8117fea5)
Location: kernel/events/core.c:2538
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff81191c38)
Location: kernel/events/core.c:2772
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff811a13e8)
Location: kernel/events/core.c:2836
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff811a8c84)
Location: kernel/events/core.c:2919
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff811bc4e4)
Location: kernel/events/core.c:2823
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff811dc694)
Location: kernel/events/core.c:3067
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff811eca94)
Location: kernel/events/core.c:3062
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff81204474)
Location: kernel/events/core.c:3086
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff81211064)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, int ctxn, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123d040)
Location: kernel/events/core.c:3341
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff8123d040-ffffffff8123d38a: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, int ctxn, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247280)
Location: kernel/events/core.c:3385
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81247280-ffffffff812476db: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, int ctxn, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124b120)
Location: kernel/events/core.c:3407
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff8124b120-ffffffff8124b57e: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, int ctxn, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81284710)
Location: kernel/events/core.c:3470
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81284710-ffffffff81284c22: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, int ctxn, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d8c10)
Location: kernel/events/core.c:3381
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff812d8c10-ffffffff812d9113: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813411e0)
Location: kernel/events/core.c:3454
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff813411e0-ffffffff813415a9: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81372160)
Location: kernel/events/core.c:3454
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81372160-ffffffff81372522: perf_event_context_sched_out (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_context_sched_out(struct task_struct *task, struct task_struct *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139b4d0)
Location: kernel/events/core.c:3498
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff8139b4d0-ffffffff8139b89a: perf_event_context_sched_out (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029b548)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (c04caa24)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (c00000000034b3c0)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffe0001cdac0)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff812096b4)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff811fc464)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff81207454)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff812161f1)
Location: kernel/events/core.c:3171
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
</details>
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
<b>Param removed. </b>
<code>int ctxn</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, ctxn, next</code> ➡️ <code>task, next</code>
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
