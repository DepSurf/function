# Function: <code>trace_event_buffer_lock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114ead0)
Location: kernel/trace/trace.c:1710
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8114ead0-ffffffff8114eb48: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811577a0)
Location: kernel/trace/trace.c:2069
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811577a0-ffffffff81157887: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115d700)
Location: kernel/trace/trace.c:2082
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8115d700-ffffffff8115d7f1: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160820)
Location: kernel/trace/trace.c:2259
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81160820-ffffffff81160911: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116d8e0)
Location: kernel/trace/trace.c:2262
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8116d8e0-ffffffff8116d9d1: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117cce0)
Location: kernel/trace/trace.c:2274
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8117cce0-ffffffff8117cde3: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118a580)
Location: kernel/trace/trace.c:2275
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8118a580-ffffffff8118a683: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197c80)
Location: kernel/trace/trace.c:2459
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81197c80-ffffffff81197d7c: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3620)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811a3620-ffffffff811a371c: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb850)
Location: kernel/trace/trace.c:2589
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811bb850-ffffffff811bb94c: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9450)
Location: kernel/trace/trace.c:2733
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b9450-ffffffff811b9559: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b7ff0)
Location: kernel/trace/trace.c:2742
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b7ff0-ffffffff811b8113: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e23b0)
Location: kernel/trace/trace.c:2766
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811e23b0-ffffffff811e24bc: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81219070)
Location: kernel/trace/trace.c:2759
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
**Symbols:**

```
ffffffff81219070-ffffffff812191de: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81263100)
Location: kernel/trace/trace.c:2783
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
**Symbols:**

```
ffffffff81263100-ffffffff8126326e: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127a0e0)
Location: kernel/trace/trace.c:2854
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
**Symbols:**

```
ffffffff8127a0e0-ffffffff8127a21e: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct trace_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, unsigned int trace_ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81294bc0)
Location: kernel/trace/trace.c:2848
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
**Symbols:**

```
ffffffff81294bc0-ffffffff81294cfe: trace_event_buffer_lock_reserve (STB_GLOBAL)
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
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010221038)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffff800010221038-ffff800010221170: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045c7e0)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c045c7e0-c045c8f4: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a1c10)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c0000000002a1c10-c0000000002a1df0: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017b248)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
```
**Symbols:**

```
ffffffe00017b248-ffffffe00017b37a: trace_event_buffer_lock_reserve (STB_GLOBAL)
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
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119bc40)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8119bc40-ffffffff8119bd3c: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ecc0)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff8118ecc0-ffffffff8118edbc: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81199a10)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81199a10-ffffffff81199b0c: trace_event_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *trace_event_buffer_lock_reserve(struct ring_buffer **current_rb, struct trace_event_file *trace_file, int type, long unsigned int len, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a76b0)
Location: kernel/trace/trace.c:2485
Inline: False
Direct callers:
  - kernel/trace/trace_events.c:trace_event_buffer_reserve
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff811a76b0-ffffffff811a77ac: trace_event_buffer_lock_reserve (STB_GLOBAL)
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
<code>struct ring_buffer **current_rb</code> ➡️ <code>struct trace_buffer **current_rb</code>
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
