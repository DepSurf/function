# Function: <code>tracepoint_probe_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8113fbd0)
Location: kernel/tracepoint.c:297
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff8113fbd0-ffffffff8113fbe5: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81148230)
Location: kernel/tracepoint.c:297
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff81148230-ffffffff81148245: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811520f0)
Location: kernel/tracepoint.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff811520f0-ffffffff81152105: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811546d0)
Location: kernel/tracepoint.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff811546d0-ffffffff811546e5: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81160ef0)
Location: kernel/tracepoint.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
```
**Symbols:**

```
ffffffff81160ef0-ffffffff81160f05: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8116f970)
Location: kernel/tracepoint.c:300
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff8116f970-ffffffff8116f985: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8117d9f0)
Location: kernel/tracepoint.c:346
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/blktrace.c:get_probe_ref
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff8117d9f0-ffffffff8117da05: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118a670)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
```
**Symbols:**

```
ffffffff8118a670-ffffffff8118a685: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81196580)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81196580-ffffffff81196595: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811abad0)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
```
**Symbols:**

```
ffffffff811abad0-ffffffff811abae5: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a8fa0)
Location: kernel/tracepoint.c:408
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff811a8fa0-ffffffff811a9027: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811a9f10)
Location: kernel/tracepoint.c:529
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff811a9f10-ffffffff811a9f9c: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff811d3a80)
Location: kernel/tracepoint.c:529
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff811d3a80-ffffffff811d3b0c: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81208570)
Location: kernel/tracepoint.c:529
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff81208570-ffffffff8120861e: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81250680)
Location: kernel/tracepoint.c:529
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff81250680-ffffffff8125072e: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81267a30)
Location: kernel/tracepoint.c:529
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
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
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/trace_events_user.c:user_event_reg
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff81267a30-ffffffff81267ade: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81281d60)
Location: kernel/tracepoint.c:529
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
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
  - arch/x86/kernel/trace.c:osnoise_arch_register
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_events_user.c:user_event_reg
  - kernel/trace/trace_events_user.c:user_event_reg
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
```
**Symbols:**

```
ffffffff81281d60-ffffffff81281e0e: tracepoint_probe_register (STB_GLOBAL)
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
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffff80001020eb38)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffff80001020eb38-ffff80001020eb80: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c044d744)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_exit_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/trace_syscalls.c:syscall_enter_register
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
c044d744-c044d764: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (c00000000028ce30)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
c00000000028ce30-c00000000028ce48: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffe00016f8ac)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:register_ftrace_graph
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffe00016f8ac-ffffffe00016f8e8: tracepoint_probe_register (STB_GLOBAL)
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
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118eba0)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff8118eba0-ffffffff8118ebb5: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff81181d20)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff81181d20-ffffffff81181d35: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8118c970)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff8118c970-ffffffff8118c985: tracepoint_probe_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tracepoint_probe_register(struct tracepoint *tp, void *probe, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/tracepoint.c (ffffffff8119a300)
Location: kernel/tracepoint.c:333
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
  - kernel/trace/ftrace.c:ftrace_pid_write
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/ftrace.c:ftrace_pid_follow_fork
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/blktrace.c:blk_register_tracepoints
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/trace_events.c:trace_event_reg
  - kernel/trace/bpf_trace.c:bpf_probe_register
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_cmd_trace
```
**Symbols:**

```
ffffffff8119a300-ffffffff8119a315: tracepoint_probe_register (STB_GLOBAL)
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
