# Function: <code>tracing_generic_entry_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114a730)
Location: kernel/trace/trace.c:1649
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_prepare
```
**Symbols:**

```
ffffffff8114a730-ffffffff8114a7b7: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81153180)
Location: kernel/trace/trace.c:1894
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81153180-ffffffff8115320d: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115d250)
Location: kernel/trace/trace.c:1938
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8115d250-ffffffff8115d2d9: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160280)
Location: kernel/trace/trace.c:2115
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81160280-ffffffff81160309: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116d340)
Location: kernel/trace/trace.c:2118
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8116d340-ffffffff8116d3c9: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117c390)
Location: kernel/trace/trace.c:2130
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8117c390-ffffffff8117c419: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81189b90)
Location: kernel/trace/trace.c:2131
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81189b90-ffffffff81189c19: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197180)
Location: kernel/trace/trace.c:2314
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81197180-ffffffff8119720a: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a2b60)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff811a2b60-ffffffff811a2bea: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb7c0)
Location: kernel/trace/trace.c:2444
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
  - kernel/trace/trace_events_inject.c:parse_entry
```
**Symbols:**

```
ffffffff811bb7c0-ffffffff811bb845: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b93c0)
Location: kernel/trace/trace.c:2588
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
  - kernel/trace/trace_events_inject.c:parse_entry
```
**Symbols:**

```
ffffffff811b93c0-ffffffff811b9445: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be7ff)
Location: include/linux/trace_events.h:155
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff811d6b57)
Location: include/linux/trace_events.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dbd5e)
Location: include/linux/trace_events.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e90b3)
Location: include/linux/trace_events.h:155
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
```
```
In kernel/trace/trace_event_perf.c (ffffffff812039a7)
Location: include/linux/trace_events.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff8120b48e)
Location: include/linux/trace_events.h:155
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220d7e)
Location: include/linux/trace_events.h:156
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_event_perf.c (ffffffff8123ed16)
Location: include/linux/trace_events.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff8124757c)
Location: include/linux/trace_events.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126bc1e)
Location: include/linux/trace_events.h:156
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_puts
```
```
In kernel/trace/trace_event_perf.c (ffffffff8128c766)
Location: include/linux/trace_events.h:156
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff81295bec)
Location: include/linux/trace_events.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282f7e)
Location: include/linux/trace_events.h:167
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_event_perf.c (ffffffff812a9666)
Location: include/linux/trace_events.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff812b2afc)
Location: include/linux/trace_events.h:167
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129e30e)
Location: include/linux/trace_events.h:167
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace.c:__trace_array_puts
```
```
In kernel/trace/trace_event_perf.c (ffffffff812c5376)
Location: include/linux/trace_events.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
```
In kernel/trace/trace_events_inject.c (ffffffff812cf0ac)
Location: include/linux/trace_events.h:167
Inline: True
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
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010220fb8)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffff800010220fb8-ffff800010221034: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045bc04)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
c045bc04-c045bc80: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a0bd0)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
c0000000002a0bd0-c0000000002a0c40: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017a8fa)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffe00017a8fa-ffffffe00017a958: tracing_generic_entry_update (STB_GLOBAL)
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
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b180)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8119b180-ffffffff8119b20a: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118e200)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff8118e200-ffffffff8118e28a: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198f50)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff81198f50-ffffffff81198fda: tracing_generic_entry_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tracing_generic_entry_update(struct trace_entry *entry, short unsigned int type, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a6bd0)
Location: kernel/trace/trace.c:2340
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
  - kernel/trace/trace_event_perf.c:perf_trace_buf_update
```
**Symbols:**

```
ffffffff811a6bd0-ffffffff811a6c5a: tracing_generic_entry_update (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>short unsigned int type</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, flags, pc</code> ➡️ <code>entry, type, flags, pc</code>
</li>
</ul>
</details>
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
