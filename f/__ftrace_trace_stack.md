# Function: <code>__ftrace_trace_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114eb70)
Location: kernel/trace/trace.c:1798
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8114eb70-ffffffff8114ed7a: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81157b70)
Location: kernel/trace/trace.c:2163
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81157b70-ffffffff81157d5c: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81160ec0)
Location: kernel/trace/trace.c:2387
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81160ec0-ffffffff8116110c: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81164210)
Location: kernel/trace/trace.c:2564
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81164210-ffffffff81164467: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81171150)
Location: kernel/trace/trace.c:2572
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81171150-ffffffff811713a7: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811802d0)
Location: kernel/trace/trace.c:2584
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:trace_dump_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811802d0-ffffffff8118051a: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118dc40)
Location: kernel/trace/trace.c:2585
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8118dc40-ffffffff8118de8a: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b6c0)
Location: kernel/trace/trace.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8119b6c0-ffffffff8119b80a: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a70b0)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811a70b0-ffffffff811a71fa: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc990)
Location: kernel/trace/trace.c:2915
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811bc990-ffffffff811bcb01: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba5a0)
Location: kernel/trace/trace.c:2938
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811ba5a0-ffffffff811ba711: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, unsigned int trace_ctx, int skip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811baa10)
Location: kernel/trace/trace.c:2959
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811baa10-ffffffff811bab81: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, unsigned int trace_ctx, int skip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e50b0)
Location: kernel/trace/trace.c:3019
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811e50b0-ffffffff811e5221: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, unsigned int trace_ctx, int skip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f680)
Location: kernel/trace/trace.c:3017
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_puts
```
**Symbols:**

```
ffffffff8121f680-ffffffff8121f829: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, unsigned int trace_ctx, int skip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126a260)
Location: kernel/trace/trace.c:3041
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_puts
```
**Symbols:**

```
ffffffff8126a260-ffffffff8126a3e8: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, unsigned int trace_ctx, int skip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812813e0)
Location: kernel/trace/trace.c:3112
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_array_puts
```
**Symbols:**

```
ffffffff812813e0-ffffffff81281568: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct trace_buffer *buffer, unsigned int trace_ctx, int skip, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129c290)
Location: kernel/trace/trace.c:3106
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
  - kernel/trace/trace.c:__trace_array_puts
```
**Symbols:**

```
ffffffff8129c290-ffffffff8129c417: __ftrace_trace_stack (STB_LOCAL)
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
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010222788)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffff800010222788-ffff800010222938: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045ef50)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
c045ef50-c045f118: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a5020)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
c0000000002a5020-c0000000002a52ac: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017de10)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffe00017de10-ffffffe00017dfd0: __ftrace_trace_stack (STB_LOCAL)
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
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f6d0)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8119f6d0-ffffffff8119f81a: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192720)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81192720-ffffffff8119286a: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d4a0)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8119d4a0-ffffffff8119d5ea: __ftrace_trace_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ftrace_trace_stack(struct ring_buffer *buffer, long unsigned int flags, int skip, int pc, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ab140)
Location: kernel/trace/trace.c:2804
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:__trace_stack
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811ab140-ffffffff811ab2ae: __ftrace_trace_stack (STB_LOCAL)
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
<code>buffer, flags, skip, pc, regs</code> ➡️ <code>buffer, trace_ctx, skip, regs</code>
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
