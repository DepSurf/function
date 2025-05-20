# Function: <code>xbc_node_get_child</code>

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
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09b3f)
Location: lib/bootconfig.c:89
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init_instances
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_add_sibling
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff82d09b3f-ffffffff82d09b5a: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff710b)
Location: lib/bootconfig.c:89
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init_instances
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_add_sibling
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff82ff710b-ffffffff82ff7126: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201df0)
Location: lib/bootconfig.c:89
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_add_sibling
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff83201df0-ffffffff83201e0b: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e9526)
Location: lib/bootconfig.c:89
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:xbc_node_get_subkey
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_sibling
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_node_get_subkey
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff832e9526-ffffffff832e9541: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0df4)
Location: lib/bootconfig.c:154
Inline: False
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:xbc_node_get_subkey
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_sibling
  - lib/bootconfig.c:xbc_node_get_subkey
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
```
**Symbols:**

```
ffffffff834a0df4-ffffffff834a0e16: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83eda688)
Location: lib/bootconfig.c:154
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_sibling
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
**Symbols:**

```
ffffffff83edab00-ffffffff83edab22: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff837003f6)
Location: lib/bootconfig.c:154
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_sibling
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
**Symbols:**

```
ffffffff83700630-ffffffff83700652: xbc_node_get_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_node_get_child(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83933c36)
Location: lib/bootconfig.c:154
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_sibling
  - lib/bootconfig.c:xbc_node_find_next_key_value
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_next_leaf
  - lib/bootconfig.c:xbc_node_find_value
  - lib/bootconfig.c:xbc_node_find_subkey
  - lib/bootconfig.c:xbc_node_find_subkey
Direct callers:
  - init/main.c:xbc_snprint_cmdline
  - init/main.c:xbc_snprint_cmdline
  - kernel/trace/trace_boot.c:trace_boot_init
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_handlers
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
**Symbols:**

```
ffffffff83933e70-ffffffff83933e92: xbc_node_get_child (STB_GLOBAL)
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
