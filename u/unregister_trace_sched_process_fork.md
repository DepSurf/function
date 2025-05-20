# Function: <code>unregister_trace_sched_process_fork</code>

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
In kernel/trace/trace_events.c (ffffffff8116b1fd)
Location: include/trace/events/sched.h:266
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
In kernel/trace/trace_events.c (ffffffff811764ed)
Location: include/trace/events/sched.h:266
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
In kernel/trace/ftrace.c (ffffffff8115b3de)
Location: include/trace/events/sched.h:267
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff8117930d)
Location: include/trace/events/sched.h:267
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
In kernel/trace/ftrace.c (ffffffff811684ce)
Location: include/trace/events/sched.h:273
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81186a5d)
Location: include/trace/events/sched.h:273
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
In kernel/trace/ftrace.c (ffffffff811771cc)
Location: include/trace/events/sched.h:273
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81195b16)
Location: include/trace/events/sched.h:273
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
In kernel/trace/ftrace.c (ffffffff81184e1c)
Location: include/trace/events/sched.h:288
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811a3c86)
Location: include/trace/events/sched.h:288
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
In kernel/trace/ftrace.c (ffffffff81191bee)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811b1b58)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffff8119dc1e)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811bd1d8)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b4370)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811d65ea)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffff811b2040)
Location: include/trace/events/sched.h:371
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811d391a)
Location: include/trace/events/sched.h:371
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
In kernel/trace/ftrace.c (ffffffff811b2b40)
Location: include/trace/events/sched.h:371
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811d502a)
Location: include/trace/events/sched.h:371
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
In kernel/trace/ftrace.c (ffffffff811dca70)
Location: include/trace/events/sched.h:369
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff81201eda)
Location: include/trace/events/sched.h:369
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
In kernel/trace/ftrace.c (ffffffff8121300b)
Location: include/trace/events/sched.h:372
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff8123d3d7)
Location: include/trace/events/sched.h:372
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
In kernel/trace/ftrace.c (ffffffff8125c7ab)
Location: include/trace/events/sched.h:372
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff8128aaa7)
Location: include/trace/events/sched.h:372
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
In kernel/trace/ftrace.c (ffffffff812736eb)
Location: include/trace/events/sched.h:372
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff812a79e7)
Location: include/trace/events/sched.h:372
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
In kernel/trace/ftrace.c (ffffffff8128dc7b)
Location: include/trace/events/sched.h:372
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff812c3097)
Location: include/trace/events/sched.h:372
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010216b64)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffff80001023c4ec)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (c04558d8)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (c0477ddc)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (c000000000298ca0)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (c0000000002cb2c0)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffe000176608)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffe0001926dc)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffff8119623e)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811b57f8)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffff8118934e)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811a85f8)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffff8119400e)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811b35c8)
Location: include/trace/events/sched.h:287
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
In kernel/trace/ftrace.c (ffffffff811a1bde)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
```
```
In kernel/trace/trace_events.c (ffffffff811c1668)
Location: include/trace/events/sched.h:287
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_follow_fork
```
</details>
</li>
</ul>

## Differences
