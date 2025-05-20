# Function: <code>trace_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81152560)
Location: kernel/trace/trace.c:6311
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/trace.c:create_trace_option_files
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
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81152560-ffffffff81152593: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115b770)
Location: kernel/trace/trace.c:6714
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff8115b770-ffffffff8115b7a3: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165f80)
Location: kernel/trace/trace.c:6997
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81165f80-ffffffff81165fb3: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811694a0)
Location: kernel/trace/trace.c:7361
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811694a0-ffffffff811694d3: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81176450)
Location: kernel/trace/trace.c:7364
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81176450-ffffffff81176483: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:7452
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81186558-ffffffff8118656c: trace_create_file.cold.80 (STB_LOCAL)
ffffffff811855f0-ffffffff81185616: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:7474
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81193ee8-ffffffff81193efc: trace_create_file.cold.80 (STB_LOCAL)
ffffffff81192f20-ffffffff81192f46: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:7959
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811a1ba6-ffffffff811a1bba: trace_create_file.cold (STB_LOCAL)
ffffffff811a0a20-ffffffff811a0a48: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811ad57c-ffffffff811ad590: trace_create_file.cold (STB_LOCAL)
ffffffff811ac450-ffffffff811ac478: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be9f0)
Location: kernel/trace/trace.c:8213
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811c55e4-ffffffff811c55f8: trace_create_file.cold (STB_LOCAL)
ffffffff811c4bf0-ffffffff811c4c18: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc5d0)
Location: kernel/trace/trace.c:8287
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81be5901-ffffffff81be5915: trace_create_file.cold (STB_LOCAL)
ffffffff811c27f0-ffffffff811c2818: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc0c0)
Location: kernel/trace/trace.c:8623
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81bd77a9-ffffffff81bd77bd: trace_create_file.cold (STB_LOCAL)
ffffffff811c3860-ffffffff811c3888: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e686f)
Location: kernel/trace/trace.c:8787
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81cb572b-ffffffff81cb573f: trace_create_file.cold (STB_LOCAL)
ffffffff811eea10-ffffffff811eea38: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121e71f)
Location: kernel/trace/trace.c:8819
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace.c:tracer_init_tracefs_work_func
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81e66734-ffffffff81e66748: trace_create_file.cold (STB_LOCAL)
ffffffff81226e30-ffffffff81226e65: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb3f18)
Location: kernel/trace/trace.c:8914
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff812720f0-ffffffff81272147: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d9248)
Location: kernel/trace/trace.c:9077
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff812893f0-ffffffff81289447: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390b7d8)
Location: kernel/trace/trace.c:9159
Inline: True
Inline callers:
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
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_dynevent.c:init_dynamic_event
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff812a4770-ffffffff812a47c7: trace_create_file (STB_GLOBAL)
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
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010229458)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffff800010229458-ffff800010229498: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0466a5c)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
c0466a5c-c0466aa4: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b09c0)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
c0000000002b09c0-c0000000002b0a24: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000183b82)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffe000183b82-ffffffe000183bbe: trace_create_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811a5b9c-ffffffff811a5bb0: trace_create_file.cold (STB_LOCAL)
ffffffff811a4a70-ffffffff811a4a98: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81198b2c-ffffffff81198b40: trace_create_file.cold (STB_LOCAL)
ffffffff81197a20-ffffffff81197a48: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811a396c-ffffffff811a3980: trace_create_file.cold (STB_LOCAL)
ffffffff811a2840-ffffffff811a2868: trace_create_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *trace_create_file(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8010
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:ftrace_init_tracefs
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/ftrace.c:ftrace_create_filter_files
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:tracer_init_tracefs
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
  - kernel/trace/trace_printk.c:init_trace_printk_function_export
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_stack.c:stack_trace_init
  - kernel/trace/trace_functions_graph.c:init_graph_tracefs
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811b16fc-ffffffff811b1710: trace_create_file.cold (STB_LOCAL)
ffffffff811b05d0-ffffffff811b05f8: trace_create_file (STB_GLOBAL)
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
