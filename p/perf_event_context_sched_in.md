# Function: <code>perf_event_context_sched_in</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_context_sched_in(struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117d200)
Location: kernel/events/core.c:2817
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff8117d200-ffffffff8117d2d0: perf_event_context_sched_in (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81191402)
Location: kernel/events/core.c:3055
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff811a0bb2)
Location: kernel/events/core.c:3126
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff811a856c)
Location: kernel/events/core.c:3209
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff811bbcdc)
Location: kernel/events/core.c:3103
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff811dbe6e)
Location: kernel/events/core.c:3410
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff811ec22e)
Location: kernel/events/core.c:3405
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff81203c3e)
Location: kernel/events/core.c:3432
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff8121082e)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff8123ca45)
Location: kernel/events/core.c:3734
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_context_sched_in(struct perf_event_context *ctx, struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81245540)
Location: kernel/events/core.c:3803
Inline: False
Direct callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:__perf_event_task_sched_in
```
**Symbols:**

```
ffffffff81245540-ffffffff8124569b: perf_event_context_sched_in (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8124aabd)
Location: kernel/events/core.c:3825
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff8128687a)
Location: kernel/events/core.c:3921
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff812da785)
Location: kernel/events/core.c:3830
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff81342835)
Location: kernel/events/core.c:3913
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff81373895)
Location: kernel/events/core.c:3913
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff8139c715)
Location: kernel/events/core.c:3945
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffff80001029ad60)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (c04ca1dc)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (c00000000034a990)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffe0001cd422)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff81208e7e)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff811fbc0e)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff81206c1e)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
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
In kernel/events/core.c (ffffffff812159a5)
Location: kernel/events/core.c:3517
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
