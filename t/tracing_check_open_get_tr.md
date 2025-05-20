# Function: <code>tracing_check_open_get_tr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a68e0)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811a68e0-ffffffff811a692a: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc830)
Location: kernel/trace/trace.c:323
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811bf430-ffffffff811bf4c6: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba440)
Location: kernel/trace/trace.c:474
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811bd060-ffffffff811bd0f6: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba8b0)
Location: kernel/trace/trace.c:476
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811bcb60-ffffffff811bcbf8: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e4ff0)
Location: kernel/trace/trace.c:489
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811e7610-ffffffff811e76a8: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121db0c)
Location: kernel/trace/trace.c:499
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff8121c150-ffffffff8121c1d9: tracing_check_open_get_tr.part.0 (STB_LOCAL)
ffffffff8121f5c0-ffffffff8121f5ea: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126809c)
Location: kernel/trace/trace.c:498
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812658e0-ffffffff81265969: tracing_check_open_get_tr.part.0 (STB_LOCAL)
ffffffff8126a180-ffffffff8126a1aa: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127f25c)
Location: kernel/trace/trace.c:539
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff8127cc50-ffffffff8127ccd9: tracing_check_open_get_tr.part.0 (STB_LOCAL)
ffffffff81281300-ffffffff8128132a: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81298b9f)
Location: kernel/trace/trace.c:541
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_open_options
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_file_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:tracing_open_generic
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_open_options
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_file_tr
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812979e0-ffffffff81297a69: tracing_check_open_get_tr.part.0 (STB_LOCAL)
ffffffff8129c1b0-ffffffff8129c1da: tracing_check_open_get_tr (STB_GLOBAL)
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
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010223758)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffff800010223758-ffff8000102237ac: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c046100c)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
```
**Symbols:**

```
c046100c-c0461068: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a81b0)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
c0000000002a81b0-c0000000002a8230: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ee3e)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
```
**Symbols:**

```
ffffffe00017ee3e-ffffffe00017ee88: tracing_check_open_get_tr (STB_GLOBAL)
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
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ef00)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff8119ef00-ffffffff8119ef4a: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81191f50)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff81191f50-ffffffff81191f9a: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ccd0)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff8119ccd0-ffffffff8119cd1a: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tracing_check_open_get_tr(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811aa970)
Location: kernel/trace/trace.c:308
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open_generic_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811aa970-ffffffff811aa9ba: tracing_check_open_get_tr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
