# Function: <code>trace_buffer_unlock_commit_regs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114fb90)
Location: kernel/trace/trace.c:1746
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8114fb90-ffffffff8114fbf5: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81158b70)
Location: kernel/trace/trace.c:2109
Inline: False
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81158b70-ffffffff81158bd6: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81163180)
Location: kernel/trace/trace.c:2197
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81163180-ffffffff81163213: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166620)
Location: kernel/trace/trace.c:2374
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81166620-ffffffff811666b3: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811735b0)
Location: kernel/trace/trace.c:2386
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811735b0-ffffffff81173641: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81182590)
Location: kernel/trace/trace.c:2398
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81182590-ffffffff81182621: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118fef0)
Location: kernel/trace/trace.c:2399
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8118fef0-ffffffff8118ff81: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d590)
Location: kernel/trace/trace.c:2583
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8119d590-ffffffff8119d72d: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8f60)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811a8f60-ffffffff811a90fd: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c1240)
Location: kernel/trace/trace.c:2720
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811c1240-ffffffff811c12d1: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bee70)
Location: kernel/trace/trace.c:2866
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_wakeup_trace
  - kernel/trace/trace_sched_wakeup.c:tracing_sched_switch_trace
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811bee70-ffffffff811bef0b: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, unsigned int trace_ctx, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf740)
Location: kernel/trace/trace.c:2888
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811bf740-ffffffff811bf7ce: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, unsigned int trace_ctx, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ea090)
Location: kernel/trace/trace.c:2948
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811ea090-ffffffff811ea11e: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, unsigned int trace_ctx, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81221f00)
Location: kernel/trace/trace.c:2946
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff81221f00-ffffffff81221faf: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, unsigned int trace_ctx, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126ceb0)
Location: kernel/trace/trace.c:2970
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff8126ceb0-ffffffff8126cf5f: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, unsigned int trace_ctx, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81284040)
Location: kernel/trace/trace.c:3041
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff81284040-ffffffff812840ef: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct trace_buffer *buffer, struct ring_buffer_event *event, unsigned int trace_ctx, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129f140)
Location: kernel/trace/trace.c:3035
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
```
**Symbols:**

```
ffffffff8129f140-ffffffff8129f1ef: trace_buffer_unlock_commit_regs (STB_GLOBAL)
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
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225cf0)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffff800010225cf0-ffff800010225db8: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c046321c)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:trace_note
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c046321c-c04632e0: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002ab570)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c0000000002ab570-c0000000002ab6bc: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000180b34)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffe000180b34-ffffffe000180c14: trace_buffer_unlock_commit_regs (STB_GLOBAL)
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
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1580)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811a1580-ffffffff811a171d: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81194550)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81194550-ffffffff811946ed: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f350)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8119f350-ffffffff8119f4ed: trace_buffer_unlock_commit_regs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_regs(struct trace_array *tr, struct ring_buffer *buffer, struct ring_buffer_event *event, long unsigned int flags, int pc, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad0b0)
Location: kernel/trace/trace.c:2609
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_mmiotrace.c:mmio_trace_mapping
  - kernel/trace/trace_mmiotrace.c:mmio_trace_rw
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811ad0b0-ffffffff811ad26b: trace_buffer_unlock_commit_regs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int trace_ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int pc</code>
</li>
<li>
<b>Param reordered. </b>
<code>tr, buffer, event, flags, pc, regs</code> ➡️ <code>tr, buffer, event, trace_ctx, regs</code>
</li>
</ul>
</details>
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
