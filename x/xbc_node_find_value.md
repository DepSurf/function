# Function: <code>xbc_node_find_value</code>

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
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d0a247)
Location: lib/bootconfig.c:191
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff82d0a247-ffffffff82d0a2a6: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff782e)
Location: lib/bootconfig.c:191
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_enable_tracer
  - kernel/trace/trace_boot.c:trace_boot_enable_tracer
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff82ff782e-ffffffff82ff788d: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff8320233d)
Location: lib/bootconfig.c:191
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8320233d-ffffffff8320239c: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e9aaa)
Location: lib/bootconfig.c:191
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff832e9aaa-ffffffff832e9b09: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a173c)
Location: lib/bootconfig.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff834a173c-ffffffff834a179f: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83edad50)
Location: lib/bootconfig.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff83edad50-ffffffff83edadf6: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83700880)
Location: lib/bootconfig.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff83700880-ffffffff83700926: xbc_node_find_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *xbc_node_find_value(struct xbc_node *parent, const char *key, struct xbc_node **vnode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff839340c0)
Location: lib/bootconfig.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_set_ftrace_filter
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_init_one_event
  - kernel/trace/trace_boot.c:trace_boot_hist_add_one_handler
  - kernel/trace/trace_boot.c:trace_boot_hist_add_array
  - kernel/trace/trace_boot.c:trace_boot_add_synth_event
  - kernel/trace/trace_boot.c:trace_boot_add_kprobe_event
  - kernel/trace/trace_boot.c:trace_boot_enable_events
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff839340c0-ffffffff83934166: xbc_node_find_value (STB_GLOBAL)
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
