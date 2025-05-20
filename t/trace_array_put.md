# Function: <code>trace_array_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114d850)
Location: kernel/trace/trace.c:304
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
```
**Symbols:**

```
ffffffff8114d850-ffffffff8114d89f: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156060)
Location: kernel/trace/trace.c:302
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81156060-ffffffff811560af: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160820)
Location: kernel/trace/trace.c:304
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81160820-ffffffff8116086f: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81163be0)
Location: kernel/trace/trace.c:296
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81163be0-ffffffff81163c1a: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81170b50)
Location: kernel/trace/trace.c:296
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffff81170b50-ffffffff81170b7f: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117fc40)
Location: kernel/trace/trace.c:297
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff8117fc40-ffffffff8117fc6f: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118d5b0)
Location: kernel/trace/trace.c:298
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff8118d5b0-ffffffff8118d5df: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119aec0)
Location: kernel/trace/trace.c:300
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:system_tr_open
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff8119aec0-ffffffff8119aeef: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a6520)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff811a6520-ffffffff811a655a: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfbb0)
Location: kernel/trace/trace.c:312
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init_instances
```
**Symbols:**

```
ffffffff811bc8f0-ffffffff811bc933: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd7d9)
Location: kernel/trace/trace.c:463
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init_instances
```
**Symbols:**

```
ffffffff811ba500-ffffffff811ba543: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd2d9)
Location: kernel/trace/trace.c:465
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff811ba970-ffffffff811ba9b3: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e7da9)
Location: kernel/trace/trace.c:478
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff811e5410-ffffffff811e5453: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121dbc6)
Location: kernel/trace/trace.c:488
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff8121afd0-ffffffff8121b015: trace_array_put.part.0 (STB_LOCAL)
ffffffff8121c720-ffffffff8121c773: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81268156)
Location: kernel/trace/trace.c:487
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff812649b0-ffffffff812649f5: trace_array_put.part.0 (STB_LOCAL)
ffffffff81267070-ffffffff812670c3: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff836da17d)
Location: kernel/trace/trace.c:528
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff8127b9e0-ffffffff8127ba25: trace_array_put.part.0 (STB_LOCAL)
ffffffff8127e190-ffffffff8127e1e3: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390c6ef)
Location: kernel/trace/trace.c:530
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:tracing_release_options
  - kernel/trace/trace.c:tracing_release_options
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_single_release_file_tr
  - kernel/trace/trace.c:tracing_single_release_file_tr
  - kernel/trace/trace.c:tracing_open_file_tr
  - kernel/trace/trace.c:tracing_open_file_tr
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace_events.c:trace_put_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:remove_hist_vars
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff812966d0-ffffffff81296715: trace_array_put.part.0 (STB_LOCAL)
ffffffff81298fd0-ffffffff81299023: trace_array_put (STB_GLOBAL)
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
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff8000102232f8)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffff8000102232f8-ffff800010223360: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0460c58)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
c0460c58-c0460c8c: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a7bf0)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
c0000000002a7bf0-c0000000002a7c50: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ea74)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
```
**Symbols:**

```
ffffffe00017ea74-ffffffe00017eac2: trace_array_put (STB_GLOBAL)
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
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119eb40)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff8119eb40-ffffffff8119eb7a: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81191b90)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff81191b90-ffffffff81191bca: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c910)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff8119c910-ffffffff8119c94a: trace_array_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811aa5b0)
Location: kernel/trace/trace.c:301
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_release
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_release
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_release
  - kernel/trace/trace_events.c:subsystem_release
  - kernel/trace/trace_events.c:subsystem_open
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:remove_hist_vars
```
**Symbols:**

```
ffffffff811aa5b0-ffffffff811aa5ea: trace_array_put (STB_GLOBAL)
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
