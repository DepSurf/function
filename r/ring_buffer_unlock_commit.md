# Function: <code>ring_buffer_unlock_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148be0)
Location: kernel/trace/ring_buffer.c:2650
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81148be0-ffffffff81148e3d: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81150f10)
Location: kernel/trace/ring_buffer.c:2644
Inline: False
```
**Symbols:**

```
ffffffff81150f10-ffffffff81151185: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81159830)
Location: kernel/trace/ring_buffer.c:2613
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81159830-ffffffff811598d0: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cf40)
Location: kernel/trace/ring_buffer.c:2615
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8115cf40-ffffffff8115cfe9: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169ee0)
Location: kernel/trace/ring_buffer.c:2608
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81169ee0-ffffffff81169f89: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81178e40)
Location: kernel/trace/ring_buffer.c:2737
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81178e40-ffffffff81178ee5: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811890d0)
Location: kernel/trace/ring_buffer.c:2800
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811890d0-ffffffff811891dc: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811966b0)
Location: kernel/trace/ring_buffer.c:2777
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811966b0-ffffffff811967c4: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2080)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811a2080-ffffffff811a2194: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7650)
Location: kernel/trace/ring_buffer.c:2847
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:ftrace_trace_userstack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811b7650-ffffffff811b779c: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5210)
Location: kernel/trace/ring_buffer.c:3180
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811b5210-ffffffff811b535c: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5550)
Location: kernel/trace/ring_buffer.c:3263
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811b5550-ffffffff811b569e: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3263
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81cb486a-ffffffff81cb48ca: ring_buffer_unlock_commit.cold (STB_LOCAL)
ffffffff811de0d0-ffffffff811de286: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3301
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_puts
```
**Symbols:**

```
ffffffff81e659d1-ffffffff81e65a31: ring_buffer_unlock_commit.cold (STB_LOCAL)
ffffffff81215f50-ffffffff81216145: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_puts
```
**Symbols:**

```
ffffffff8205d109-ffffffff8205d169: ring_buffer_unlock_commit.cold (STB_LOCAL)
ffffffff81261b90-ffffffff81261d36: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3384
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_array_puts
```
**Symbols:**

```
ffffffff820dbaca-ffffffff820dbb2a: ring_buffer_unlock_commit.cold (STB_LOCAL)
ffffffff81278c10-ffffffff81278daf: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ring_buffer_unlock_commit(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3204
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_array_puts
```
**Symbols:**

```
ffffffff821b78f1-ffffffff821b7951: ring_buffer_unlock_commit.cold (STB_LOCAL)
ffffffff812936d0-ffffffff81293870: ring_buffer_unlock_commit (STB_GLOBAL)
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
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021c4b0)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffff80001021c4b0-ffff80001021c5b4: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045af48)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
c045af48-c045b05c: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029fb90)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
c00000000029fb90-c00000000029fd28: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000179fee)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffe000179fee-ffffffe00017a0c4: ring_buffer_unlock_commit (STB_GLOBAL)
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
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119a6a0)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8119a6a0-ffffffff8119a7b4: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118d720)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8118d720-ffffffff8118d834: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198470)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81198470-ffffffff81198584: ring_buffer_unlock_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ring_buffer_unlock_commit(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a60a0)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_buffer_unlock_commit_nostack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811a60a0-ffffffff811a61d4: ring_buffer_unlock_commit (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ring_buffer_event *event</code>
</li>
</ul>
</details>
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
