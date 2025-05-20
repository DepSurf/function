# Function: <code>ring_buffer_discard_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148e40)
Location: kernel/trace/ring_buffer.c:2933
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_current_buffer_discard_commit
  - kernel/trace/trace_events.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
**Symbols:**

```
ffffffff81148e40-ffffffff8114920c: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81151190)
Location: kernel/trace/ring_buffer.c:2928
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
ffffffff81151190-ffffffff81151599: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115bf80)
Location: kernel/trace/ring_buffer.c:2897
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
ffffffff8115bf80-ffffffff8115c3d2: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115f040)
Location: kernel/trace/ring_buffer.c:2899
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
ffffffff8115f040-ffffffff8115f446: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116c100)
Location: kernel/trace/ring_buffer.c:2891
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
ffffffff8116c100-ffffffff8116c510: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117b420)
Location: kernel/trace/ring_buffer.c:3024
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
ffffffff8117b420-ffffffff8117b82a: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81188120)
Location: kernel/trace/ring_buffer.c:3087
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
ffffffff81188120-ffffffff81188541: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195580)
Location: kernel/trace/ring_buffer.c:3064
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
ffffffff81195580-ffffffff81195a12: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0c80)
Location: kernel/trace/ring_buffer.c:3065
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
ffffffff811a0c80-ffffffff811a10ad: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b67e0)
Location: kernel/trace/ring_buffer.c:3134
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b67e0-ffffffff811b6c28: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b41d0)
Location: kernel/trace/ring_buffer.c:3685
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b41d0-ffffffff811b45b0: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5140)
Location: kernel/trace/ring_buffer.c:3772
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff811b5140-ffffffff811b554f: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3772
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
ffffffff81cb49da-ffffffff81cb49fb: ring_buffer_discard_commit.cold (STB_LOCAL)
ffffffff811df3a0-ffffffff811df7b2: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3810
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
```
**Symbols:**

```
ffffffff81e65a31-ffffffff81e65a52: ring_buffer_discard_commit.cold (STB_LOCAL)
ffffffff81216150-ffffffff8121658f: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3889
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
```
**Symbols:**

```
ffffffff8205d0d3-ffffffff8205d0f4: ring_buffer_discard_commit.cold (STB_LOCAL)
ffffffff8125f600-ffffffff8125fa3f: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3892
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
**Symbols:**

```
ffffffff820dba94-ffffffff820dbab5: ring_buffer_discard_commit.cold (STB_LOCAL)
ffffffff81276830-ffffffff81276c97: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ring_buffer_discard_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3796
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace.c:call_filter_check_discard
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
**Symbols:**

```
ffffffff821b785c-ffffffff821b78dc: ring_buffer_discard_commit.cold (STB_LOCAL)
ffffffff81291360-ffffffff812917ae: ring_buffer_discard_commit (STB_GLOBAL)
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
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021aaa8)
Location: kernel/trace/ring_buffer.c:3065
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
ffff80001021aaa8-ffff80001021b028: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0459508)
Location: kernel/trace/ring_buffer.c:3065
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c0459508-c0459abc: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029ddc0)
Location: kernel/trace/ring_buffer.c:3065
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_uprobe.c:__uprobe_trace_func
```
**Symbols:**

```
c00000000029ddc0-c00000000029e40c: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000179468)
Location: kernel/trace/ring_buffer.c:3065
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_event_buffer_commit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_exit
  - kernel/trace/trace_syscalls.c:ftrace_syscall_enter
```
**Symbols:**

```
ffffffe000179468-ffffffe000179772: ring_buffer_discard_commit (STB_GLOBAL)
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
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811992a0)
Location: kernel/trace/ring_buffer.c:3065
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
ffffffff811992a0-ffffffff811996cd: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118c930)
Location: kernel/trace/ring_buffer.c:3065
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
ffffffff8118c930-ffffffff8118cd5d: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197070)
Location: kernel/trace/ring_buffer.c:3065
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
ffffffff81197070-ffffffff8119749d: ring_buffer_discard_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_discard_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4c80)
Location: kernel/trace/ring_buffer.c:3065
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
ffffffff811a4c80-ffffffff811a50c4: ring_buffer_discard_commit (STB_GLOBAL)
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
