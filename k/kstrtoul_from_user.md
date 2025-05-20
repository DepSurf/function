# Function: <code>kstrtoul_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81402120)
Location: lib/kstrtox.c:340
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:event_enable_write
  - kernel/trace/trace_events.c:system_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81402120-ffffffff814021a9: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81449cd0)
Location: lib/kstrtox.c:404
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81449cd0-ffffffff81449d6e: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81468690)
Location: lib/kstrtox.c:400
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81468690-ffffffff8146872e: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146dd90)
Location: lib/kstrtox.c:402
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff8146dd90-ffffffff8146de2c: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8149a0c0)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff8149a0c0-ffffffff8149a15c: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cf370)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff814cf370-ffffffff814cf40c: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e3c80)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff814e3c80-ffffffff814e3d1c: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81510060)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81510060-ffffffff815100fc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152df60)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff8152df60-ffffffff8152dffc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81591a20)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81591a20-ffffffff81591abc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae560)
Location: lib/kstrtox.c:400
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff815ae560-ffffffff815ae5fc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b9060)
Location: lib/kstrtox.c:407
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff815b9060-ffffffff815b90fc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8161f8d0)
Location: lib/kstrtox.c:408
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff8161f8d0-ffffffff8161f983: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (0)
Location: lib/kstrtox.c:424
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff816ee1c0-ffffffff816ee1c5: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (0)
Location: lib/kstrtox.c:424
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff817decc0-ffffffff817decc5: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (0)
Location: lib/kstrtox.c:424
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff8181e4a0-ffffffff8181e4a5: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (0)
Location: lib/kstrtox.c:424
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_subbuf_size_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81864310-ffffffff81864315: kstrtoul_from_user (STB_GLOBAL)
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
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff80001063a3d8)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffff80001063a3d8-ffff80001063a494: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07df95c)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
c07df95c-c07dfa50: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e1190)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
c0000000007e1190-c0000000007e1280: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe000466afc)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffe000466afc-ffffffe000466b80: kstrtoul_from_user (STB_GLOBAL)
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
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81526540)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81526540-ffffffff815265dc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81516820)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff81516820-ffffffff815168bc: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815225d0)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff815225d0-ffffffff8152266c: kstrtoul_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kstrtoul_from_user(const char *s, size_t count, unsigned int base, long unsigned int *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153bf50)
Location: lib/kstrtox.c:403
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace.c:buffer_percent_write
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:trace_options_core_write
  - kernel/trace/trace.c:trace_options_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_max_lat_write
  - kernel/trace/trace.c:tracing_thresh_write
  - kernel/trace/trace.c:tracing_saved_cmdlines_size_write
  - kernel/trace/trace_stack.c:stack_max_size_write
  - kernel/trace/trace_functions_graph.c:graph_depth_write
  - kernel/trace/trace_events.c:system_enable_write
  - kernel/trace/trace_events.c:event_enable_write
  - drivers/scsi/sg.c:sg_proc_write_dressz
  - drivers/scsi/sg.c:sg_proc_write_adio
```
**Symbols:**

```
ffffffff8153bf50-ffffffff8153bfec: kstrtoul_from_user (STB_GLOBAL)
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
