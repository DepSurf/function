# Function: <code>perf_event_exit_event</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81196738)
Location: kernel/events/core.c:9931
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811a61b8)
Location: kernel/events/core.c:10191
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811ad966)
Location: kernel/events/core.c:10438
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811c14cb)
Location: kernel/events/core.c:10470
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811e18be)
Location: kernel/events/core.c:11000
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff811f1d2e)
Location: kernel/events/core.c:11043
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff812098fc)
Location: kernel/events/core.c:11394
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81216c6c)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81240cf2)
Location: kernel/events/core.c:12110
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
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
In kernel/events/core.c (ffffffff8124b2a3)
Location: kernel/events/core.c:12394
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_exit_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124f330)
Location: kernel/events/core.c:12587
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff8124f330-ffffffff8124f3f0: perf_event_exit_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_exit_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128a1c0)
Location: kernel/events/core.c:12708
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff8128a1c0-ffffffff8128a2ca: perf_event_exit_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_exit_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812deb90)
Location: kernel/events/core.c:12678
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff812deb90-ffffffff812ded1e: perf_event_exit_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_exit_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81346d90)
Location: kernel/events/core.c:12923
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff81346d90-ffffffff81346f1d: perf_event_exit_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_exit_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81377e90)
Location: kernel/events/core.c:12965
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff81377e90-ffffffff8137801f: perf_event_exit_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_exit_event(struct perf_event *event, struct perf_event_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a1170)
Location: kernel/events/core.c:13061
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
```
**Symbols:**

```
ffffffff813a1170-ffffffff813a12ff: perf_event_exit_event (STB_LOCAL)
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
In kernel/events/core.c (ffff80001029eab0)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
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
In kernel/events/core.c (c04ce40c)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task_context
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
In kernel/events/core.c (c000000000352f54)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffe0001d0030)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8120f2bc)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff81202066)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8120d05c)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
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
In kernel/events/core.c (ffffffff8121bf3f)
Location: kernel/events/core.c:11507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exit_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
