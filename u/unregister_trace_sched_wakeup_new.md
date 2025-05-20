# Function: <code>unregister_trace_sched_wakeup_new</code>

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
In kernel/trace/trace_sched_switch.c (ffffffff811566c8)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811579f5)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff8115f0c1)
Location: include/trace/events/sched.h:102
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
In kernel/trace/trace_sched_switch.c (ffffffff81160fbe)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81162275)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811699c1)
Location: include/trace/events/sched.h:102
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
In kernel/trace/trace_sched_switch.c (ffffffff8116ba1e)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116cdd5)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81174e81)
Location: include/trace/events/sched.h:102
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
In kernel/trace/trace_sched_switch.c (ffffffff8116ea08)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116fef5)
Location: include/trace/events/sched.h:102
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81177ad1)
Location: include/trace/events/sched.h:102
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
In kernel/trace/trace_sched_switch.c (ffffffff8117baf8)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117d075)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81185171)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff8118ada5)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118c395)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811941f1)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff81198705)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199ae5)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811a2501)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811a6295)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a7725)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811b041f)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811b1a74)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2f15)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811bb8ef)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811c9d1a)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb3cd)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/trace_events.c (ffffffff811d4b56)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811c73da)
Location: include/trace/events/sched.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8aad)
Location: include/trace/events/sched.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/trace_events.c (ffffffff811d1ce6)
Location: include/trace/events/sched.h:187
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
In kernel/trace/trace_sched_switch.c (ffffffff811c84fa)
Location: include/trace/events/sched.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ca0ed)
Location: include/trace/events/sched.h:187
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811d2b00)
Location: include/trace/events/sched.h:187
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
In kernel/trace/trace_sched_switch.c (ffffffff811f3eca)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5ed4)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811ff8b0)
Location: include/trace/events/sched.h:185
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
In kernel/trace/trace_sched_switch.c (ffffffff8122d6b6)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f4a6)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81239ef2)
Location: include/trace/events/sched.h:185
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
In kernel/trace/trace_sched_switch.c (ffffffff81279446)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b5e6)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff812872df)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/trace_sched_switch.c (ffffffff81290e86)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81293106)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff812a401f)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/trace_sched_switch.c (ffffffff812ac496)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812aec36)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff812bf97f)
Location: include/trace/events/sched.h:185
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
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
In kernel/trace/trace_sched_switch.c (ffff80001022f710)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230c34)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffff80001023ab3c)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (c046b394)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (c046cc54)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (c04755d0)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (c0000000002b910c)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb4b0)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (c0000000002c8010)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffe0001876ec)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001889c8)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffe000190dd0)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811aa094)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab535)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811b3f0f)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff8119d014)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e0e5)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811a6d0f)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811a7e64)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a9305)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811b1cdf)
Location: include/trace/events/sched.h:103
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
In kernel/trace/trace_sched_switch.c (ffffffff811b5c04)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b7145)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811bfd7f)
Location: include/trace/events/sched.h:103
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
</details>
</li>
</ul>

## Differences
