# Function: <code>unregister_trace_sched_wakeup</code>

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
In kernel/trace/trace_sched_switch.c (ffffffff811566dd)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81157a0a)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff8115f095)
Location: include/trace/events/sched.h:95
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
In kernel/trace/trace_sched_switch.c (ffffffff81160fd3)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116228a)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81169995)
Location: include/trace/events/sched.h:95
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
In kernel/trace/trace_sched_switch.c (ffffffff8116ba33)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116cdea)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81174e55)
Location: include/trace/events/sched.h:95
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
In kernel/trace/trace_sched_switch.c (ffffffff8116ea1d)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8116ff0a)
Location: include/trace/events/sched.h:95
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81177aa5)
Location: include/trace/events/sched.h:95
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
In kernel/trace/trace_sched_switch.c (ffffffff8117bb0d)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8117d08a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81185145)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff8118adba)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8118c3aa)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811941c5)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff8119871a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff81199afa)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811a24d5)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811a62aa)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a773a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811b03f3)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811b1a89)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b2f2a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811bb8c3)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811c9d2f)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811cb3e2)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/trace_events.c (ffffffff811d4b2a)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811c73ef)
Location: include/trace/events/sched.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811c8ac2)
Location: include/trace/events/sched.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:start_wakeup_tracer
```
```
In kernel/trace/trace_events.c (ffffffff811d1cba)
Location: include/trace/events/sched.h:180
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
In kernel/trace/trace_sched_switch.c (ffffffff811c850f)
Location: include/trace/events/sched.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ca102)
Location: include/trace/events/sched.h:180
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811d2ad4)
Location: include/trace/events/sched.h:180
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
In kernel/trace/trace_sched_switch.c (ffffffff811f3edf)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811f5ee9)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811ff884)
Location: include/trace/events/sched.h:178
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
In kernel/trace/trace_sched_switch.c (ffffffff8122d6cb)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8122f4bb)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff81239ec6)
Location: include/trace/events/sched.h:178
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
In kernel/trace/trace_sched_switch.c (ffffffff8127945b)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8127b5fb)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff812872b3)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812bce56)
Location: include/trace/events/sched.h:178
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
In kernel/trace/trace_sched_switch.c (ffffffff81290e9b)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8129311b)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff812a3ff3)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff812e3a26)
Location: include/trace/events/sched.h:178
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
In kernel/trace/trace_sched_switch.c (ffffffff812ac4ab)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff812aec4b)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff812bf953)
Location: include/trace/events/sched.h:178
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/rv/monitors/wwnr/wwnr.c (ffffffff81301aa6)
Location: include/trace/events/sched.h:178
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
In kernel/trace/trace_sched_switch.c (ffff80001022f720)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffff800010230c4c)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffff80001023ab10)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (c046b3ac)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (c046cc6c)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (c04755a0)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (c0000000002b9120)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bb4c8)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (c0000000002c7fe0)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffe000187706)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001889e2)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffe000190d9c)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811aa0a9)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811ab54a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811b3ee3)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff8119d029)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff8119e0fa)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811a6ce3)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811a7e79)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811a931a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811b1cb3)
Location: include/trace/events/sched.h:96
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
In kernel/trace/trace_sched_switch.c (ffffffff811b5c19)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_start_sched_switch
  - kernel/trace/trace_sched_switch.c:tracing_sched_unregister
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffff811b715a)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
```
In kernel/trace/trace_events.c (ffffffff811bfd53)
Location: include/trace/events/sched.h:96
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
</details>
</li>
</ul>

## Differences
