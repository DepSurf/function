# Function: <code>ring_buffer_lock_reserve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81147cc0)
Location: kernel/trace/ring_buffer.c:2832
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81147cc0-ffffffff81147d68: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81151f80)
Location: kernel/trace/ring_buffer.c:2827
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_lock_reserve
```
**Symbols:**

```
ffffffff81151f80-ffffffff81152024: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115a550)
Location: kernel/trace/ring_buffer.c:2796
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
```
**Symbols:**

```
ffffffff8115a550-ffffffff8115a8f1: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115d5c0)
Location: kernel/trace/ring_buffer.c:2798
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
```
**Symbols:**

```
ffffffff8115d5c0-ffffffff8115d938: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116a7f0)
Location: kernel/trace/ring_buffer.c:2790
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
```
**Symbols:**

```
ffffffff8116a7f0-ffffffff8116ab6e: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811794f0)
Location: kernel/trace/ring_buffer.c:2923
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
```
**Symbols:**

```
ffffffff811794f0-ffffffff811798b2: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81186bc0)
Location: kernel/trace/ring_buffer.c:2986
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
```
**Symbols:**

```
ffffffff81186bc0-ffffffff81186f7f: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81193dc0)
Location: kernel/trace/ring_buffer.c:2963
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
```
**Symbols:**

```
ffffffff81193dc0-ffffffff81194197: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119f8e0)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffffffff8119f8e0-ffffffff8119fc7b: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b8210)
Location: kernel/trace/ring_buffer.c:3033
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
```
**Symbols:**

```
ffffffff811b8210-ffffffff811b85b0: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5dd0)
Location: kernel/trace/ring_buffer.c:3584
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
```
**Symbols:**

```
ffffffff811b5dd0-ffffffff811b6121: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4990)
Location: kernel/trace/ring_buffer.c:3671
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_last_func_repeats
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
```
**Symbols:**

```
ffffffff811b4990-ffffffff811b4cc7: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3671
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff81cb4920-ffffffff81cb49da: ring_buffer_lock_reserve.cold (STB_LOCAL)
ffffffff811deba0-ffffffff811def26: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3709
Inline: False
Direct callers:
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
  - kernel/trace/trace.c:__trace_puts
```
**Symbols:**

```
ffffffff81e6591a-ffffffff81e659d1: ring_buffer_lock_reserve.cold (STB_LOCAL)
ffffffff81215ba0-ffffffff81215f4e: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3788
Inline: False
Direct callers:
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
  - kernel/trace/trace.c:__trace_puts
```
**Symbols:**

```
ffffffff8205d01c-ffffffff8205d0d3: ring_buffer_lock_reserve.cold (STB_LOCAL)
ffffffff8125f240-ffffffff8125f5ee: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3791
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff820db9dd-ffffffff820dba94: ring_buffer_lock_reserve.cold (STB_LOCAL)
ffffffff81276450-ffffffff81276818: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct trace_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (0)
Location: kernel/trace/ring_buffer.c:3695
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff821b77a5-ffffffff821b785c: ring_buffer_lock_reserve.cold (STB_LOCAL)
ffffffff81290f60-ffffffff81291346: ring_buffer_lock_reserve (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021be60)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffff80001021be60-ffff80001021c2c8: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045a3cc)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
c045a3cc-c045a908: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029ce50)
Location: kernel/trace/ring_buffer.c:2964
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_mark_raw_write
  - kernel/trace/trace.c:tracing_mark_write
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:trace_function
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_event_buffer_lock_reserve
  - kernel/trace/trace.c:trace_buffer_lock_reserve
```
**Symbols:**

```
c00000000029ce50-c00000000029d3dc: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001785cc)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffffffe0001785cc-ffffffe000178862: ring_buffer_lock_reserve (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197f00)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffffffff81197f00-ffffffff8119829b: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118b6b0)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffffffff8118b6b0-ffffffff8118ba4b: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195cd0)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffffffff81195cd0-ffffffff8119606b: ring_buffer_lock_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_lock_reserve(struct ring_buffer *buffer, long unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a3b60)
Location: kernel/trace/ring_buffer.c:2964
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
```
**Symbols:**

```
ffffffff811a3b60-ffffffff811a3f1c: ring_buffer_lock_reserve (STB_GLOBAL)
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
