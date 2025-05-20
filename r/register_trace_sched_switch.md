# Function: <code>register_trace_sched_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81145da6)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811566a3)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157b09)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114e600)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81160f13)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81162389)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158542)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8116b973)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116cee9)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/ftrace.c (ffffffff8115b96f)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8116e9e3)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81170009)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/ftrace.c (ffffffff81168a3f)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8117bad3)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117d189)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/ftrace.c (ffffffff81177739)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8118abf1)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118c4ad)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
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
In kernel/trace/ftrace.c (ffffffff81184cd3)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81198551)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199bfd)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811a0aaa)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
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
In kernel/trace/ftrace.c (ffffffff81191ac7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811a60ca)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a783f)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811ae818)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff8119daf7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811b18e7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b302f)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811b9f98)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff811b4113)
Location: include/trace/events/sched.h:138
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811c9b7e)
Location: include/trace/events/sched.h:138
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb4a3)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/fgraph.c (ffffffff811d2e16)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff811b1de3)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811c723e)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8b83)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/fgraph.c (ffffffff811cff76)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff811b28f1)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811c83a2)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ca20f)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811d120f)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff811dc821)
Location: include/trace/events/sched.h:220
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811f3d72)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5b6f)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811fdf0f)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff81212d53)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8122d526)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f11d)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff812388c9)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff8125c463)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8127922a)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b179)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff81285769)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812bcf17)
Location: include/trace/events/sched.h:222
Inline: True
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
In kernel/trace/ftrace.c (ffffffff81273398)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81290c6a)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81292c99)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_osnoise.c (ffffffff8129931f)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
```
```
In kernel/trace/fgraph.c (ffffffff812a2429)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812e3ae7)
Location: include/trace/events/sched.h:222
Inline: True
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
In kernel/trace/ftrace.c (ffffffff8128d928)
Location: include/trace/events/sched.h:222
Inline: True
```
```
In kernel/trace/trace_sched_switch.c (ffffffff812ac27a)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812ae7c9)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b499f)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
```
```
In kernel/trace/fgraph.c (ffffffff812bdbf7)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff81301b67)
Location: include/trace/events/sched.h:222
Inline: True
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
In kernel/trace/ftrace.c (ffff8000102169e0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffff80001022f674)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230d5c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffff8000102387b4)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (c0455754)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (c046b338)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (c046cd6c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (c04742ac)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (c000000000298abc)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (c0000000002b9028)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb63c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (c0000000002c4c00)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffe0001764a6)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffe0001876c0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe000188af0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffe00018f706)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
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
In kernel/trace/ftrace.c (ffffffff81196117)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811a9f07)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab64f)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811b25b8)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff81189227)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8119ce87)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e1ff)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811a53c8)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff81193ee7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811a7cd7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a941f)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811b0388)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
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
In kernel/trace/ftrace.c (ffffffff811a1ab7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_write
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811b5a77)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b725f)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811be325)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
</details>
</li>
</ul>

## Differences
