# Function: <code>tracing_init_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81152fa0)
Location: kernel/trace/trace.c:6842
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81152fa0-ffffffff8115304c: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115c1c0)
Location: kernel/trace/trace.c:7249
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff8115c1c0-ffffffff8115c26c: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811669f0)
Location: kernel/trace/trace.c:7535
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811669f0-ffffffff81166a9c: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81169f10)
Location: kernel/trace/trace.c:7904
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81169f10-ffffffff81169f9e: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81176eb0)
Location: kernel/trace/trace.c:7915
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81176eb0-ffffffff81176f3e: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff826fcdde)
Location: kernel/trace/trace.c:8016
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff8117eff0-ffffffff8117f05c: tracing_init_dentry.part.67 (STB_LOCAL)
ffffffff8118651b-ffffffff8118653a: tracing_init_dentry.part.67.cold.77 (STB_LOCAL)
ffffffff811860a0-ffffffff811860b8: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b3cf8)
Location: kernel/trace/trace.c:8090
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff8118c8e0-ffffffff8118c94c: tracing_init_dentry.part.68 (STB_LOCAL)
ffffffff81193eab-ffffffff81193eca: tracing_init_dentry.part.68.cold.77 (STB_LOCAL)
ffffffff81193a00-ffffffff81193a18: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff828ccdc8)
Location: kernel/trace/trace.c:8603
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff8119a130-ffffffff8119a171: tracing_init_dentry.part.0 (STB_LOCAL)
ffffffff811a1a73-ffffffff811a1aa7: tracing_init_dentry.part.0.cold (STB_LOCAL)
ffffffff811a1540-ffffffff811a1558: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811acfc6)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811ad5b1-ffffffff811ad5c6: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811acf90-ffffffff811ad00b: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb290)
Location: kernel/trace/trace.c:8937
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811bb290-ffffffff811bb2de: tracing_init_dentry.part.0 (STB_LOCAL)
ffffffff811c55f8-ffffffff811c560d: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811c4ce0-ffffffff811c4d09: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c290e)
Location: kernel/trace/trace.c:9042
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81be5915-ffffffff81be592a: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811c28e0-ffffffff811c2948: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c397e)
Location: kernel/trace/trace.c:9381
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81bd77bd-ffffffff81bd77d2: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811c3950-ffffffff811c39b8: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811eeb37)
Location: kernel/trace/trace.c:9543
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81cb573f-ffffffff81cb5754: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811eeb00-ffffffff811eeb68: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9576
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81e66748-ffffffff81e6675c: tracing_init_dentry.cold (STB_LOCAL)
ffffffff81226f40-ffffffff81226fbb: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81272250)
Location: kernel/trace/trace.c:9669
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81272250-ffffffff812722da: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81289550)
Location: kernel/trace/trace.c:9834
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81289550-ffffffff812895da: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a48d0)
Location: kernel/trace/trace.c:10029
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff812a48d0-ffffffff812a495a: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010229f50)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffff800010229f50-ffff80001022a000: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04675d0)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
c04675d0-c0467698: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b1a60)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
c0000000002b1a60-c0000000002b1b64: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe0001845e4)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
```
**Symbols:**

```
ffffffe0001845e4-ffffffe00018467c: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a55e6)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811a5bd1-ffffffff811a5be6: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811a55b0-ffffffff811a562b: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198596)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81198b61-ffffffff81198b76: tracing_init_dentry.cold (STB_LOCAL)
ffffffff81198560-ffffffff811985db: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a33b6)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811a39a1-ffffffff811a39b6: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811a3380-ffffffff811a33fb: tracing_init_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *tracing_init_dentry();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b1146)
Location: kernel/trace/trace.c:8654
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811b1731-ffffffff811b1746: tracing_init_dentry.cold (STB_LOCAL)
ffffffff811b1110-ffffffff811b118b: tracing_init_dentry (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct dentry *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
