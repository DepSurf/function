# Function: <code>call_filter_check_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114c260)
Location: kernel/trace/trace.c:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
```
**Symbols:**

```
ffffffff8114c260-ffffffff8114c293: call_filter_check_discard.part.27 (STB_LOCAL)
ffffffff8114c2a0-ffffffff8114c2b4: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156670)
Location: kernel/trace/trace.c:309
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81156670-ffffffff811566c2: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160e60)
Location: kernel/trace/trace.c:311
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81160e60-ffffffff81160eb2: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811641b0)
Location: kernel/trace/trace.c:303
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811641b0-ffffffff81164202: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811710f0)
Location: kernel/trace/trace.c:303
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811710f0-ffffffff81171142: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81180270)
Location: kernel/trace/trace.c:304
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81180270-ffffffff811802c2: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118dbe0)
Location: kernel/trace/trace.c:305
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8118dbe0-ffffffff8118dc32: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b660)
Location: kernel/trace/trace.c:307
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8119b660-ffffffff8119b6bf: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a7050)
Location: kernel/trace/trace.c:325
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811a7050-ffffffff811a70af: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bcc73)
Location: kernel/trace/trace.c:340
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811bfcc0-ffffffff811bfd1f: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba888)
Location: kernel/trace/trace.c:491
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811bd8f0-ffffffff811bd94f: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be5e6)
Location: kernel/trace/trace.c:493
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811bd3f0-ffffffff811bd44f: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8e78)
Location: kernel/trace/trace.c:506
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811e7ee0-ffffffff811e7f3f: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f5f0)
Location: kernel/trace/trace.c:516
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8121f5f0-ffffffff8121f67c: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126a1c0)
Location: kernel/trace/trace.c:515
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8126a1c0-ffffffff8126a24c: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81281340)
Location: kernel/trace/trace.c:556
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81281340-ffffffff812813cc: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129c1f0)
Location: kernel/trace/trace.c:558
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8129c1f0-ffffffff8129c27c: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffff800010222edc)
Location: kernel/trace/trace.c:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffff800010221bd8-ffff800010221c5c: call_filter_check_discard.part.0 (STB_LOCAL)
ffff800010223ed0-ffff800010223ef4: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c045f5a8)
Location: kernel/trace/trace.c:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
c045eed0-c045ef50: call_filter_check_discard.part.0 (STB_LOCAL)
c0461634-c0461664: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c0000000002a5968)
Location: kernel/trace/trace.c:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
c0000000002a4f40-c0000000002a501c: call_filter_check_discard.part.0 (STB_LOCAL)
c0000000002a8c70-c0000000002a8c94: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017e458)
Location: kernel/trace/trace.c:325
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffe00017dd80-ffffffe00017de10: call_filter_check_discard.part.0 (STB_LOCAL)
ffffffe00017f46a-ffffffe00017f48e: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f670)
Location: kernel/trace/trace.c:325
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8119f670-ffffffff8119f6cf: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811926c0)
Location: kernel/trace/trace.c:325
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811926c0-ffffffff8119271f: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d440)
Location: kernel/trace/trace.c:325
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8119d440-ffffffff8119d49f: call_filter_check_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int call_filter_check_discard(struct trace_event_call *call, void *rec, struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ab0e0)
Location: kernel/trace/trace.c:325
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811ab0e0-ffffffff811ab13f: call_filter_check_discard (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
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
