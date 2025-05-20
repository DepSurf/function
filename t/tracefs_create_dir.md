# Function: <code>tracefs_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8131f560)
Location: fs/tracefs/inode.c:461
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8131f560-ffffffff8131f577: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81354a30)
Location: fs/tracefs/inode.c:461
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff81354a30-ffffffff81354a47: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8136acf0)
Location: fs/tracefs/inode.c:461
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8136acf0-ffffffff8136ad07: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8137f340)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8137f340-ffffffff8137f357: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813a4380)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff813a4380-ffffffff813a4397: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813d3750)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff813d3750-ffffffff813d3767: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff813ede40)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:instance_mkdir
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff813ede40-ffffffff813ede57: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8141a100)
Location: fs/tracefs/inode.c:455
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8141a100-ffffffff8141a117: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81433f70)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff81433f70-ffffffff81433f87: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81483d40)
Location: fs/tracefs/inode.c:462
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff81483d40-ffffffff81483d57: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814a1390)
Location: fs/tracefs/inode.c:462
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_dir
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff814a1390-ffffffff814a13a7: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814a74c0)
Location: fs/tracefs/inode.c:464
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace.c:tracing_init_tracefs_percpu
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff814a74c0-ffffffff814a74d7: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814ff7b0)
Location: fs/tracefs/inode.c:542
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff814ff7b0-ffffffff814ff7c7: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81590820)
Location: fs/tracefs/inode.c:542
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
```
**Symbols:**

```
ffffffff81590820-ffffffff81590841: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff81637cc0)
Location: fs/tracefs/inode.c:557
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_register_monitor
```
**Symbols:**

```
ffffffff81637cc0-ffffffff81637ce1: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff816700c0)
Location: fs/tracefs/inode.c:557
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_register_monitor
```
**Symbols:**

```
ffffffff816700c0-ffffffff816700e1: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff816aae10)
Location: fs/tracefs/inode.c:639
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_init_interface
  - kernel/trace/rv/rv.c:rv_register_monitor
```
**Symbols:**

```
ffffffff816aae10-ffffffff816aae55: tracefs_create_dir (STB_GLOBAL)
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
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffff800010519a20)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffff800010519a20-ffff800010519a5c: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (c06d4130)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
c06d4130-c06d4154: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (c000000000663160)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
c000000000663160-c00000000066317c: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffe000382ce2)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffe000382ce2-ffffffe000382d1c: tracefs_create_dir (STB_GLOBAL)
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
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8142c550)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8142c550-ffffffff8142c567: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8141cfd0)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8141cfd0-ffffffff8141cfe7: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff814286f0)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff814286f0-ffffffff81428707: tracefs_create_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *tracefs_create_dir(const char *name, struct dentry *parent);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/tracefs/inode.c (ffffffff8143f5b0)
Location: fs/tracefs/inode.c:459
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_events.c:create_event_toplevel_files
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
  - kernel/trace/trace_events.c:event_create_dir
```
**Symbols:**

```
ffffffff8143f5b0-ffffffff8143f5c7: tracefs_create_dir (STB_GLOBAL)
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
