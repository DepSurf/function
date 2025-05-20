# Function: <code>ftrace_trace_userstack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114f9d0)
Location: kernel/trace/trace.c:1921
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8114f9d0-ffffffff8114fb11: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81158a40)
Location: kernel/trace/trace.c:2293
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81158a40-ffffffff81158b70: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81163000)
Location: kernel/trace/trace.c:2517
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81163000-ffffffff81163176: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811664a0)
Location: kernel/trace/trace.c:2723
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811664a0-ffffffff81166619: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81173430)
Location: kernel/trace/trace.c:2732
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81173430-ffffffff811735a9: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81182410)
Location: kernel/trace/trace.c:2733
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81182410-ffffffff8118258a: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ftrace_trace_userstack(struct ring_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118fd70)
Location: kernel/trace/trace.c:2735
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8118fd70-ffffffff8118feea: ftrace_trace_userstack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d5f4)
Location: kernel/trace/trace.c:2913
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8fc4)
Location: kernel/trace/trace.c:2939
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ftrace_trace_userstack(struct trace_buffer *buffer, long unsigned int flags, int pc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd220)
Location: kernel/trace/trace.c:3050
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811bd220-ffffffff811bd369: ftrace_trace_userstack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bae30)
Location: kernel/trace/trace.c:3068
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811bae30-ffffffff811baf7b: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811baf50)
Location: kernel/trace/trace.c:3085
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811baf50-ffffffff811bb0a2: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e5720)
Location: kernel/trace/trace.c:3145
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff811e5720-ffffffff811e5872: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f830)
Location: kernel/trace/trace.c:3143
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8121f830-ffffffff8121f9b4: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126a400)
Location: kernel/trace/trace.c:3167
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8126a400-ffffffff8126a581: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81281580)
Location: kernel/trace/trace.c:3258
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff81281580-ffffffff81281701: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129c430)
Location: kernel/trace/trace.c:3235
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
**Symbols:**

```
ffffffff8129c430-ffffffff8129c5b1: ftrace_trace_userstack.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2984
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2984
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a15e4)
Location: kernel/trace/trace.c:2939
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811945b4)
Location: kernel/trace/trace.c:2939
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f3b4)
Location: kernel/trace/trace.c:2939
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad114)
Location: kernel/trace/trace.c:2939
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffer_unlock_commit_regs
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
</ul>
