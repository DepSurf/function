# Function: <code>cpu_ctx_sched_out</code>

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
In kernel/events/core.c (ffffffff8117d0ef)
Location: kernel/events/core.c:2715
Inline: True
Inline callers:
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
In kernel/events/core.c (ffffffff8119144d)
Location: kernel/events/core.c:2938
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811a0bfd)
Location: kernel/events/core.c:3009
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811a85cc)
Location: kernel/events/core.c:3092
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811bbd48)
Location: kernel/events/core.c:2996
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811dbf2c)
Location: kernel/events/core.c:3240
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811ec2ec)
Location: kernel/events/core.c:3235
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81203cfb)
Location: kernel/events/core.c:3259
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff812108eb)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff8123b31d)
Location: kernel/events/core.c:3525
Inline: True
Inline callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff8124593d)
Location: kernel/events/core.c:3593
Inline: True
Inline callers:
  - kernel/events/core.c:perf_rotate_context
  - kernel/events/core.c:perf_event_context_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff8124ab48)
Location: kernel/events/core.c:3615
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81286905)
Location: kernel/events/core.c:3678
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff812da810)
Location: kernel/events/core.c:3589
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
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
In kernel/events/core.c (ffff80001029adcc)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (c04ca250)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (c00000000034aa28)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffe0001cd4ce)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81208f3b)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff811fbccb)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81206cdb)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
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
In kernel/events/core.c (ffffffff81215a5b)
Location: kernel/events/core.c:3344
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_task_sched_in
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:ctx_resched
  - kernel/events/core.c:perf_mux_hrtimer_handler
  - kernel/events/core.c:perf_cgroup_switch
```
</details>
</li>
</ul>

## Differences
