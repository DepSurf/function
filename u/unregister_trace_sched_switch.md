# Function: <code>unregister_trace_sched_switch</code>

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
In kernel/trace/ftrace.c (ffffffff81145b91)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81156739)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811579e0)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/trace_events.c (ffffffff8115f069)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8114e3d0)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_open
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81160fa9)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81162260)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/trace_events.c (ffffffff81169969)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff81158310)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:ftrace_pid_open
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8116ba09)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116cdc0)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/trace_events.c (ffffffff81174e29)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8115b660)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8116eaa1)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fee0)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/trace_events.c (ffffffff81177a79)
Location: include/trace/events/sched.h:124
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff81168750)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8117bb91)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117d060)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/trace_events.c (ffffffff81185119)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff81177420)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8118ac80)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118c380)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/trace_events.c (ffffffff81194199)
Location: include/trace/events/sched.h:128
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8117e2fb)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811985e0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199ad0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/fgraph.c (ffffffff811a0b80)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811a24a9)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8118b399)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811a6170)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7710)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
```
```
In kernel/trace/fgraph.c (ffffffff811aea21)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811b03c7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff811972c9)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811b1960)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2f00)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811ba1a1)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811bb897)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff811ac8d6)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811c9d05)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb3b8)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/fgraph.c (ffffffff811d3021)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811d4afe)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff811aa1e6)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811c73c5)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8a98)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/fgraph.c (ffffffff811d0181)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811d1c8e)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff811aadb8)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811c84e5)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ca0d8)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811d1431)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811d2aa8)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff811d4a58)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811f3eb5)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5ebf)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811fe131)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811ff858)
Location: include/trace/events/sched.h:220
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff81209a9d)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8122d6a1)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f491)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff81238b11)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff81239e9a)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff81252b82)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81279431)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b5d1)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff81285a01)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff81287287)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812bce51)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
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
In kernel/trace/ftrace.c (ffffffff8126a11b)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff81290e71)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812930f1)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_osnoise.c (ffffffff81299566)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
```
```
In kernel/trace/fgraph.c (ffffffff812a26c1)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff812a3fc7)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812e3a1d)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
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
In kernel/trace/ftrace.c (ffffffff8128428b)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff812ac481)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812aec21)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b4be6)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_hook_events
```
```
In kernel/trace/fgraph.c (ffffffff812bdec1)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff812bf927)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff81301a9d)
Location: include/trace/events/sched.h:222
Inline: True
Inline callers:
  - kernel/trace/rv/monitors/wwnr/wwnr.c:disable_wwnr
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
In kernel/trace/ftrace.c (ffff80001020f6ec)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffff80001022f748)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230c18)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffff800010238a08)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffff80001023aac4)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (c044ebb4)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (c046b3f4)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (c046cc3c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (c04745e4)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (c047556c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (c00000000028e64c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (c0000000002b9188)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb48c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (c0000000002c4f88)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (c0000000002c7f7c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffe00017044a)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffe00018778c)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001889ae)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffe00018f820)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffe000190d68)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8118f8e9)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811a9f80)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab520)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811b27c1)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811b3eb7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff81182a29)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff8119cf00)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e0d0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811a55d1)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811a6cb7)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8118d6b9)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811a7d50)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a92f0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811b0591)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811b1c87)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/ftrace.c (ffffffff8119b249)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:clear_ftrace_pids
```
```
In kernel/trace/trace_sched_switch.c (ffffffff811b5af0)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b7130)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/fgraph.c (ffffffff811be621)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
```
In kernel/trace/trace_events.c (ffffffff811bfd27)
Location: include/trace/events/sched.h:138
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
</details>
</li>
</ul>

## Differences
