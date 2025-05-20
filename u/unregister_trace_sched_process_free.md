# Function: <code>unregister_trace_sched_process_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b4375)
Location: include/trace/events/sched.h:241
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811d6600)
Location: include/trace/events/sched.h:241
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2045)
Location: include/trace/events/sched.h:325
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811d3930)
Location: include/trace/events/sched.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2b45)
Location: include/trace/events/sched.h:325
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811d5040)
Location: include/trace/events/sched.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811dca75)
Location: include/trace/events/sched.h:323
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81201ef0)
Location: include/trace/events/sched.h:323
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81213010)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff8123d3ed)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125c7b0)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff8128aabd)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812736f0)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff812a79fd)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128dc80)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff812c30ad)
Location: include/trace/events/sched.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
