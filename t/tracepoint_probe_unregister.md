# Function: <code>tracepoint_probe_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8113f730)
Location: kernel/tracepoint.c:311
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
**Symbols:**

```
ffffffff8113f730-ffffffff8113f903: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81147da0)
Location: kernel/tracepoint.c:311
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff81147da0-ffffffff81147f8c: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81151c40)
Location: kernel/tracepoint.c:315
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff81151c40-ffffffff81151e2c: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811542b0)
Location: kernel/tracepoint.c:316
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff811542b0-ffffffff81154458: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81160ac0)
Location: kernel/tracepoint.c:316
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff81160ac0-ffffffff81160c71: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8116fcb0)
Location: kernel/tracepoint.c:314
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
```
**Symbols:**

```
ffffffff8116fcb0-ffffffff8116fe5f: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8117d540)
Location: kernel/tracepoint.c:360
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
```
**Symbols:**

```
ffffffff8117d540-ffffffff8117d711: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118a6e0)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
```
**Symbols:**

```
ffffffff8118a6e0-ffffffff8118a8aa: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811965f0)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff811965f0-ffffffff811967ba: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811ab450)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
```
**Symbols:**

```
ffffffff811ab450-ffffffff811ab4cb: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9370)
Location: kernel/tracepoint.c:422
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff811a9370-ffffffff811a93eb: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9680)
Location: kernel/tracepoint.c:543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
```
**Symbols:**

```
ffffffff811a9680-ffffffff811a9a0a: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff81cb4020-ffffffff81cb4035: tracepoint_probe_unregister.cold (STB_LOCAL)
ffffffff811d3270-ffffffff811d35cd: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff81e64f6a-ffffffff81e64f7e: tracepoint_probe_unregister.cold (STB_LOCAL)
ffffffff81207cd0-ffffffff8120804e: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:543
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff8205ca71-ffffffff8205ca85: tracepoint_probe_unregister.cold (STB_LOCAL)
ffffffff81250740-ffffffff81250abe: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff820db412-ffffffff820db426: tracepoint_probe_unregister.cold (STB_LOCAL)
ffffffff81267af0-ffffffff81267e4e: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/tracepoint.c (0)
Location: kernel/tracepoint.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_unregister
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
```
**Symbols:**

```
ffffffff821b711f-ffffffff821b7133: tracepoint_probe_unregister.cold (STB_LOCAL)
ffffffff812814a0-ffffffff812817fe: tracepoint_probe_unregister (STB_GLOBAL)
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
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffff80001020e638)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffff80001020e638-ffff80001020e884: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c044d190)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
c044d190-c044d420: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c00000000028cf00)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
c00000000028cf00-c00000000028d218: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffe00016f3d8)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffe00016f3d8-ffffffe00016f5e0: tracepoint_probe_unregister (STB_GLOBAL)
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
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118ec10)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8118ec10-ffffffff8118edda: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81181d90)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff81181d90-ffffffff81181f5a: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118c9e0)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8118c9e0-ffffffff8118cbaa: tracepoint_probe_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tracepoint_probe_unregister(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8119a370)
Location: kernel/tracepoint.c:347
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/blktrace.c:put_probe_ref
  - kernel/trace/fgraph.c:unregister_ftrace_graph
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_follow_fork
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_unregister
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
**Symbols:**

```
ffffffff8119a370-ffffffff8119a53a: tracepoint_probe_unregister (STB_GLOBAL)
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
