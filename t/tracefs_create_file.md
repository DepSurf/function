# Function: <code>tracefs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8131f420)
Location: fs/tracefs/inode.c:392
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff8131f420-ffffffff8131f554: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813548f0)
Location: fs/tracefs/inode.c:392
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff813548f0-ffffffff81354a24: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8136abb0)
Location: fs/tracefs/inode.c:392
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff8136abb0-ffffffff8136ace4: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8137f200)
Location: fs/tracefs/inode.c:390
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff8137f200-ffffffff8137f334: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813a4240)
Location: fs/tracefs/inode.c:390
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff813a4240-ffffffff813a4374: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813d3610)
Location: fs/tracefs/inode.c:390
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff813d3610-ffffffff813d374e: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813edd00)
Location: fs/tracefs/inode.c:390
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff813edd00-ffffffff813ede3e: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81419fb0)
Location: fs/tracefs/inode.c:386
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff81419fb0-ffffffff8141a0f5: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81433e00)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff81433e00-ffffffff81433f6b: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81483bb0)
Location: fs/tracefs/inode.c:390
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff81483bb0-ffffffff81483d37: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814a1210)
Location: fs/tracefs/inode.c:390
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff814a1210-ffffffff814a1381: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814a7340)
Location: fs/tracefs/inode.c:392
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff814a7340-ffffffff814a74b1: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814ff610)
Location: fs/tracefs/inode.c:465
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff814ff610-ffffffff814ff7af: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81590670)
Location: fs/tracefs/inode.c:465
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
```
**Symbols:**

```
ffffffff81590670-ffffffff81590816: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81637b00)
Location: fs/tracefs/inode.c:480
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_register_monitor
  - kernel/trace/rv/rv.c:rv_register_monitor
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:reactor_populate_monitor
```
**Symbols:**

```
ffffffff81637b00-ffffffff81637ca6: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8166ff00)
Location: fs/tracefs/inode.c:480
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_register_monitor
  - kernel/trace/rv/rv.c:rv_register_monitor
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:reactor_populate_monitor
```
**Symbols:**

```
ffffffff8166ff00-ffffffff816700a6: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff816aabf0)
Location: fs/tracefs/inode.c:553
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:create_trace_option_files
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_register_monitor
  - kernel/trace/rv/rv.c:rv_register_monitor
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:init_rv_reactors
  - kernel/trace/rv/rv_reactors.c:reactor_populate_monitor
```
**Symbols:**

```
ffffffff816aabf0-ffffffff816aadf8: tracefs_create_file (STB_GLOBAL)
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
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffff8000105198b0)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffff8000105198b0-ffff800010519a1c: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (c06d3fcc)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
c06d3fcc-c06d4130: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (c000000000662f70)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
c000000000662f70-c000000000663160: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffe000382bc0)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffe000382bc0-ffffffe000382ce2: tracefs_create_file (STB_GLOBAL)
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
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8142c3e0)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff8142c3e0-ffffffff8142c54b: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8141ce60)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff8141ce60-ffffffff8141cfcb: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81428580)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff81428580-ffffffff814286eb: tracefs_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *tracefs_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8143f440)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/trace.c:trace_create_file
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
```
**Symbols:**

```
ffffffff8143f440-ffffffff8143f5ab: tracefs_create_file (STB_GLOBAL)
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
