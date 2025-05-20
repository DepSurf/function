# Function: <code>trace_ignore_this_task</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156710)
Location: kernel/trace/trace.c:358
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81156710-ffffffff8115672c: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161820)
Location: kernel/trace/trace.c:360
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81161820-ffffffff8116183c: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81164ba0)
Location: kernel/trace/trace.c:352
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81164ba0-ffffffff81164bbc: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81171ae0)
Location: kernel/trace/trace.c:352
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81171ae0-ffffffff81171b06: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81180c30)
Location: kernel/trace/trace.c:353
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81180c30-ffffffff81180c56: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118e5f0)
Location: kernel/trace/trace.c:354
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff8118e5f0-ffffffff8118e616: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c010)
Location: kernel/trace/trace.c:356
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff8119c010-ffffffff8119c036: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a7a00)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811a7a00-ffffffff811a7a26: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfd60)
Location: kernel/trace/trace.c:389
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811bfd60-ffffffff811bfda2: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd990)
Location: kernel/trace/trace.c:540
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811bd990-ffffffff811bd9d2: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd490)
Location: kernel/trace/trace.c:543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811bd490-ffffffff811bd4d2: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e7f80)
Location: kernel/trace/trace.c:556
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811e7f80-ffffffff811e7fc2: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f9e0)
Location: kernel/trace/trace.c:553
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff8121f9e0-ffffffff8121fa3b: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126a5d0)
Location: kernel/trace/trace.c:552
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff8126a5d0-ffffffff8126a62b: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81281750)
Location: kernel/trace/trace.c:593
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81281750-ffffffff812817ab: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct trace_pid_list *filtered_no_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129c600)
Location: kernel/trace/trace.c:595
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff8129c600-ffffffff8129c65b: trace_ignore_this_task (STB_GLOBAL)
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
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010223f68)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffff800010223f68-ffff800010223fb8: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04616d0)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
c04616d0-c0461728: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a8d40)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
c0000000002a8d40-c0000000002a8d98: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017f4f0)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffe00017f4f0-ffffffe00017f534: trace_ignore_this_task (STB_GLOBAL)
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
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0020)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811a0020-ffffffff811a0046: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193030)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff81193030-ffffffff81193056: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ddf0)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff8119ddf0-ffffffff8119de16: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool trace_ignore_this_task(struct trace_pid_list *filtered_pids, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811abad0)
Location: kernel/trace/trace.c:374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ignore_task_cpu
  - kernel/trace/ftrace.c:ftrace_filter_pid_sched_switch_probe
  - kernel/trace/trace_events.c:ignore_task_cpu
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_wakeup_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_post
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
  - kernel/trace/trace_events.c:event_filter_pid_sched_switch_probe_pre
```
**Symbols:**

```
ffffffff811abad0-ffffffff811abaf6: trace_ignore_this_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_pid_list *filtered_no_pids</code>
</li>
<li>
<b>Param reordered. </b>
<code>filtered_pids, task</code> ➡️ <code>filtered_pids, filtered_no_pids, task</code>
</li>
</ul>
</details>
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
