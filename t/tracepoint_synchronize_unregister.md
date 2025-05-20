# Function: <code>tracepoint_synchronize_unregister</code>

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
In kernel/trace/blktrace.c (ffffffff8115ae69)
Location: include/linux/tracepoint.h:92
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
```
```
In kernel/trace/trace_event_perf.c (ffffffff811625b3)
Location: include/linux/tracepoint.h:92
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff820b0aaa)
Location: include/linux/tracepoint.h:92
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff81165749)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
```
```
In kernel/trace/trace_event_perf.c (ffffffff8116cd87)
Location: include/linux/tracepoint.h:78
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff820e85e0)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff81170ba9)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
```
```
In kernel/trace/trace_event_perf.c (ffffffff81178047)
Location: include/linux/tracepoint.h:78
Inline: True
```
```
In drivers/i2c/i2c-core.c (ffffffff821ce2d4)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff81173c34)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
```
```
In kernel/trace/trace_event_perf.c (ffffffff8117ad57)
Location: include/linux/tracepoint.h:78
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff822c34cc)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff81180e0d)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_event_perf.c (ffffffff811885ad)
Location: include/linux/tracepoint.h:78
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff828d670b)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff8118ffa7)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_event_perf.c (ffffffff8119775d)
Location: include/linux/tracepoint.h:78
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82907ff0)
Location: include/linux/tracepoint.h:78
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff8119d7a7)
Location: include/linux/tracepoint.h:82
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811a4531)
Location: include/linux/tracepoint.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811a58cd)
Location: include/linux/tracepoint.h:82
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811a8103)
Location: include/linux/tracepoint.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a906f)
Location: include/linux/tracepoint.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811ada11)
Location: include/linux/tracepoint.h:82
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82adfe14)
Location: include/linux/tracepoint.h:82
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff811ab4e7)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811b23e1)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b37db)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b6280)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b6fe0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bd933)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82b04ea4)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
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
In kernel/trace/blktrace.c (ffffffff811b6cd7)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811bda61)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811bedcb)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c1910)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c2630)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c8ce3)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82b13e10)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff819749be)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffff811cf834)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
```
```
In kernel/trace/trace_events.c (ffffffff811d6ff6)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d87ab)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811db619)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dc99f)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e51a6)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82f258be)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81a49c9e)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/tracepoint.c (ffffffff811a9330)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_remove_func
```
```
In kernel/trace/blktrace.c (ffffffff811cccd4)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_unregister_tracepoints
```
```
In kernel/trace/trace_events.c (ffffffff811d44c6)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d58cb)
Location: include/linux/tracepoint.h:81
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d8749)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9acf)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e2bd6)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8321de47)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81a4f53e)
Location: include/linux/tracepoint.h:81
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
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
In kernel/trace/blktrace.c (ffffffff811cdfc7)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811d5b56)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6deb)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811d9bcd)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db02f)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811e3b66)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff83451e24)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81a34c07)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_cmd_trace
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffff811faa17)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff81202906)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff81203c9d)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff81206f9d)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81208639)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff81209102)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff81213e67)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff835454bd)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81ae9fc8)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
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
In kernel/trace/blktrace.c (ffffffff81234b43)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff8123dd96)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123f07f)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff812428c9)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243bf2)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff81244f2e)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8124e260)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8372398c)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81c6c7f8)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
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
In kernel/trace/blktrace.c (ffffffff81281423)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff8128b6f6)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128ccff)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff812902f9)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812917e2)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff81292dae)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff8129be20)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/rv/rv.c (ffffffff812bc3cd)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
```
```
In kernel/trace/rv/rv_reactors.c (ffffffff812bd945)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
```
```
In drivers/i2c/i2c-core-base.c (ffffffff842b26e8)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81e243e4)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
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
In kernel/trace/blktrace.c (ffffffff8129e0d3)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff812a85f6)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9c7f)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff812ad4b9)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aea42)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b001e)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff812b9590)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/rv/rv.c (ffffffff812e306d)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
```
```
In kernel/trace/rv/rv_reactors.c (ffffffff812e4505)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
```
```
In drivers/i2c/i2c-core-base.c (ffffffff83af53c8)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81e99924)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
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
In kernel/trace/blktrace.c (ffffffff812b97b3)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff812c4306)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c598f)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c99e9)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812caf62)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_free
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:event_trigger_free
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cc58e)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffffffff812d5be0)
Location: include/linux/tracepoint.h:91
Inline: True
```
```
In kernel/trace/rv/rv.c (ffffffff813010bd)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:monitoring_on_write_data
  - kernel/trace/rv/rv.c:enabled_monitors_open
```
```
In kernel/trace/rv/rv_reactors.c (ffffffff81302585)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - kernel/trace/rv/rv_reactors.c:reacting_on_write_data
```
```
In drivers/i2c/i2c-core-base.c (ffffffff83d51184)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81f5c054)
Location: include/linux/tracepoint.h:91
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
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
In kernel/trace/blktrace.c (ffff800010234c40)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffff80001023ce08)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffff80001023e234)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffff800010240fd8)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffff800010241d70)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffff80001024949c)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffff8000114baa3c)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffff800010c1a670)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (c0470af0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (c04786bc)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (c0479868)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
```
```
In kernel/trace/trace_events_filter.c (c047ca60)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (c047d748)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In drivers/i2c/i2c-core-base.c (c15c0cd0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (c0d32a58)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (c0000000002c04b0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (c0000000002cc304)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (c0000000002cdcf8)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
```
```
In kernel/trace/trace_events_filter.c (c0000000002d1e4c)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d3b4c)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (c0000000002dde54)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (c0000000013ce508)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (c000000000d0afa4)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffe00018c5c0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffe000192ea0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffe000193baa)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_event_unreg
```
```
In kernel/trace/trace_events_filter.c (ffffffe000195eba)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffe000196c4e)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0000a2424)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffe000794f42)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffff811af2f7)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811b6081)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b73eb)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b9f30)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bac50)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811c1303)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In net/core/drop_monitor.c (ffffffff8191498e)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffff811a2147)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811a8e81)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811aa1cb)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811acd10)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ada30)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811b40e3)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In net/core/drop_monitor.c (ffffffff818ce74e)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffff811ad0c7)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811b3e51)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811b51bb)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b7d00)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b8a20)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811bf0d3)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82b0f126)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff819659be)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
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
In kernel/trace/blktrace.c (ffffffff811baf97)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:put_probe_ref
```
```
In kernel/trace/trace_events.c (ffffffff811c1ef1)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_trace_del_tracer
  - kernel/trace/trace_events.c:ftrace_event_pid_write
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
```
```
In kernel/trace/trace_event_perf.c (ffffffff811c325b)
Location: include/linux/tracepoint.h:80
Inline: True
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c5da0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c6ac0)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:set_trigger_filter
  - kernel/trace/trace_events_trigger.c:trigger_data_free
```
```
In kernel/trace/trace_events_hist.c (ffffffff811cd173)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
```
In drivers/i2c/i2c-core-base.c (ffffffff82b03c48)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_exit
```
```
In net/core/drop_monitor.c (ffffffff81987bfe)
Location: include/linux/tracepoint.h:80
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_trace_off_set
```
</details>
</li>
</ul>

## Differences
