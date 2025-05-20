# Function: <code>perf_cgroup_sched_out</code>

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
In kernel/events/core.c (ffffffff8117f99f)
Location: kernel/events/core.c:538
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff81191c66)
Location: kernel/events/core.c:758
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
In kernel/events/core.c (ffffffff811a1416)
Location: kernel/events/core.c:758
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
In kernel/events/core.c (ffffffff811a8cb3)
Location: kernel/events/core.c:753
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
In kernel/events/core.c (ffffffff811bc513)
Location: kernel/events/core.c:835
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
In kernel/events/core.c (ffffffff811dc6c3)
Location: kernel/events/core.c:846
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
In kernel/events/core.c (ffffffff811ecac3)
Location: kernel/events/core.c:846
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
In kernel/events/core.c (ffffffff812044a3)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (ffffffff81211093)
Location: kernel/events/core.c:847
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff8123d473)
Location: kernel/events/core.c:853
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff812477c3)
Location: kernel/events/core.c:857
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff8124b681)
Location: kernel/events/core.c:855
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
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
In kernel/events/core.c (ffffffff81286751)
Location: kernel/events/core.c:893
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/events/core.c (ffff80001029b56c)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (c04caa58)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (c00000000034b3e8)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (ffffffe0001cdb08)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (ffffffff812096e3)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (ffffffff811fc493)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (ffffffff81207483)
Location: kernel/events/core.c:847
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
In kernel/events/core.c (ffffffff812162a5)
Location: kernel/events/core.c:847
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_out
```
</details>
</li>
</ul>

## Differences
