# Function: <code>xbc_node_get_data</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09c53)
Location: lib/bootconfig.c:115
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init_instances
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:find_match_node
  - lib/bootconfig.c:xbc_node_match_prefix
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff82d09c53-ffffffff82d09c78: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff7213)
Location: lib/bootconfig.c:115
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init_instances
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:find_match_node
  - lib/bootconfig.c:xbc_node_match_prefix
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff82ff7213-ffffffff82ff7238: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201ef8)
Location: lib/bootconfig.c:115
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:find_match_node
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff83201ef8-ffffffff83201f1d: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e9678)
Location: lib/bootconfig.c:115
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:find_match_node
  - lib/bootconfig.c:xbc_debug_dump
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff832e9678-ffffffff832e969d: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0f75)
Location: lib/bootconfig.c:180
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:find_match_node
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff834a0f75-ffffffff834a0fa1: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83eda806)
Location: lib/bootconfig.c:180
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
**Symbols:**

```
ffffffff83edab80-ffffffff83edabb8: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83700336)
Location: lib/bootconfig.c:180
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
**Symbols:**

```
ffffffff837006b0-ffffffff837006e8: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *xbc_node_get_data(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83933b76)
Location: lib/bootconfig.c:180
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
**Symbols:**

```
ffffffff83933ef0-ffffffff83933f28: xbc_node_get_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
