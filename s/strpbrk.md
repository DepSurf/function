# Function: <code>strpbrk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff813f1bc0)
Location: lib/string.c:562
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - lib/dynamic_debug.c:ddebug_exec_queries
```
**Symbols:**

```
ffffffff813f1bc0-ffffffff813f1c04: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814385bc)
Location: lib/string.c:562
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - lib/dynamic_debug.c:ddebug_exec_queries
```
**Symbols:**

```
ffffffff81438560-ffffffff814385a4: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff814555ac)
Location: lib/string.c:562
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - lib/dynamic_debug.c:ddebug_exec_queries
```
**Symbols:**

```
ffffffff81455550-ffffffff81455594: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f701c)
Location: lib/string.c:562
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff818f6fc0-ffffffff818f7004: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197da1c)
Location: lib/string.c:563
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff8197d9c0-ffffffff8197da04: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819d9f18)
Location: lib/string.c:563
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff819d9ec0-ffffffff819d9f01: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12138)
Location: lib/string.c:564
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81a120e0-ffffffff81a12121: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a81570)
Location: lib/string.c:606
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81a81570-ffffffff81a815b1: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8640)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81ab8640-ffffffff81ab8681: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f3280)
Location: lib/string.c:649
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:local_field_var_ref
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_init
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff815f3280-ffffffff815f32c1: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617930)
Location: lib/string.c:646
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:parse_expr
  - kernel/trace/trace_events_hist.c:local_field_var_ref
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_init
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81617930-ffffffff81617971: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fafb0)
Location: lib/string.c:646
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_init
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff815fafb0-ffffffff815fafee: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668860)
Location: lib/string.c:647
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_init
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81668860-ffffffff8166889e: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81781fc0)
Location: lib/string.c:555
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_parse_tree
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81781fc0-ffffffff81782027: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203edd0)
Location: lib/string.c:481
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_parse_tree
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff8203edd0-ffffffff8203ee37: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bd2e0)
Location: lib/string.c:481
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_parse_tree
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff820bd2e0-ffffffff820bd33c: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82197be0)
Location: lib/string.c:466
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_synth.c:create_synth_event
  - kernel/trace/trace_events_synth.c:create_or_delete_synth_event
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - lib/bootconfig.c:xbc_parse_tree
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff82197be0-ffffffff82197c3c: strpbrk (STB_GLOBAL)
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
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92ac0)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffff800010d92ac0-ffff800010d92b00: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f264)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
c0e8f264-c0e8f2b8: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6a60)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
c000000000ed6a60-c000000000ed6aa8: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcc24)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffe0008bcbde-ffffffe0008bcc18: strpbrk (STB_GLOBAL)
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
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a57490)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81a57490-ffffffff81a574d1: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a14570)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81a14570-ffffffff81a145b1: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac3880)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81ac3880-ffffffff81ac38c1: strpbrk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *strpbrk(const char *cs, const char *ct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfd50)
Location: lib/string.c:608
Inline: True
Inline callers:
  - lib/string.c:strsep
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdbgetaddrarg
  - kernel/trace/trace_events_hist.c:contains_operator
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_split_symbol_offset
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - lib/dynamic_debug.c:ddebug_exec_queries
  - drivers/hwmon/hwmon.c:__hwmon_device_register
```
**Symbols:**

```
ffffffff81acfd50-ffffffff81acfd91: strpbrk (STB_GLOBAL)
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
