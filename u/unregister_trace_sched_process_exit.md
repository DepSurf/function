# Function: <code>unregister_trace_sched_process_exit</code>

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
In kernel/trace/trace_events.c (ffffffff8116b213)
Location: include/trace/events/sched.h:227
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
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
In kernel/trace/trace_events.c (ffffffff81176503)
Location: include/trace/events/sched.h:227
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115b3e3)
Location: include/trace/events/sched.h:228
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81179323)
Location: include/trace/events/sched.h:228
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811684d3)
Location: include/trace/events/sched.h:234
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81186a73)
Location: include/trace/events/sched.h:234
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811771d1)
Location: include/trace/events/sched.h:234
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81195b2c)
Location: include/trace/events/sched.h:234
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184e21)
Location: include/trace/events/sched.h:249
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811a3c9c)
Location: include/trace/events/sched.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191bf3)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811b1b6e)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119dc23)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811bd1ee)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010216b68)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffff80001023c4f4)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04558dc)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (c0477de4)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000298ca8)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (c0000000002cb2d4)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000176622)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffe0001926f6)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81196243)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811b580e)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81189353)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811a860e)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81194013)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811b35de)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a1be3)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811c167e)
Location: include/trace/events/sched.h:248
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
</ul>

## Differences
