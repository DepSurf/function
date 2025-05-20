# Function: <code>event_triggers_post_call</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811657c0)
Location: kernel/trace/trace_events_trigger.c:106
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811657c0-ffffffff81165812: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt, void *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8116ff10)
Location: kernel/trace/trace_events_trigger.c:108
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8116ff10-ffffffff8116ff73: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt, void *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117b680)
Location: kernel/trace/trace_events_trigger.c:108
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8117b680-ffffffff8117b6e3: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt, void *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8117e370)
Location: kernel/trace/trace_events_trigger.c:109
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8117e370-ffffffff8117e3c4: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt, void *rec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8118bc00)
Location: kernel/trace/trace_events_trigger.c:109
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8118bc00-ffffffff8118bc5a: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff8119a640)
Location: kernel/trace/trace_events_trigger.c:109
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8119a640-ffffffff8119a694: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811a8830)
Location: kernel/trace/trace_events_trigger.c:98
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811a8830-ffffffff811a8884: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b6770)
Location: kernel/trace/trace_events_trigger.c:98
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811b6770-ffffffff811b67c4: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c1db0)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811c1db0-ffffffff811c1e04: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811db880)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811db880-ffffffff811db8d6: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811d89b0)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811d89b0-ffffffff811d8a06: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811d9f20)
Location: kernel/trace/trace_events_trigger.c:100
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811d9f20-ffffffff811d9f78: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:100
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff81cb66d6-ffffffff81cb66eb: event_triggers_post_call.cold (STB_LOCAL)
ffffffff81207900-ffffffff8120796b: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:114
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff81e676bc-ffffffff81e676d1: event_triggers_post_call.cold (STB_LOCAL)
ffffffff812432c0-ffffffff81243339: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:114
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff8205e120-ffffffff8205e135: event_triggers_post_call.cold (STB_LOCAL)
ffffffff81290dc0-ffffffff81290e39: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:116
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff820dcb63-ffffffff820dcb78: event_triggers_post_call.cold (STB_LOCAL)
ffffffff812ae030-ffffffff812ae0a9: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_trigger.c (0)
Location: kernel/trace/trace_events_trigger.c:116
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
```
**Symbols:**

```
ffffffff821b8967-ffffffff821b897c: event_triggers_post_call.cold (STB_LOCAL)
ffffffff812ca550-ffffffff812ca5c9: event_triggers_post_call (STB_GLOBAL)
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
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffff800010241490)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffff800010241490-ffff800010241508: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c047cf1c)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c047cf1c-c047cf84: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (c0000000002d2810)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c0000000002d2810-c0000000002d28bc: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffe0001964a6)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffe0001964a6-ffffffe0001964f8: event_triggers_post_call (STB_GLOBAL)
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
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ba3d0)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811ba3d0-ffffffff811ba424: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811ad1b0)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811ad1b0-ffffffff811ad204: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811b81a0)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811b81a0-ffffffff811b81f4: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void event_triggers_post_call(struct trace_event_file *file, enum event_trigger_type tt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_trigger.c (ffffffff811c6240)
Location: kernel/trace/trace_events_trigger.c:99
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811c6240-ffffffff811c6294: event_triggers_post_call (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *rec</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *rec</code>
</li>
</ul>
</details>
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
