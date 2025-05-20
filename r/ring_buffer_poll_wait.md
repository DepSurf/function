# Function: <code>ring_buffer_poll_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114a630)
Location: kernel/trace/ring_buffer.c:630
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff8114a630-ffffffff8114a6e2: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81153090)
Location: kernel/trace/ring_buffer.c:630
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff81153090-ffffffff8115313a: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115d080)
Location: kernel/trace/ring_buffer.c:628
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff8115d080-ffffffff8115d12e: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81160090)
Location: kernel/trace/ring_buffer.c:630
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff81160090-ffffffff8116013e: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116d150)
Location: kernel/trace/ring_buffer.c:633
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff8116d150-ffffffff8116d203: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117c150)
Location: kernel/trace/ring_buffer.c:662
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff8117c150-ffffffff8117c1f8: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189950)
Location: kernel/trace/ring_buffer.c:709
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff81189950-ffffffff811899f8: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196f30)
Location: kernel/trace/ring_buffer.c:686
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff81196f30-ffffffff81196fcd: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2930)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff811a2930-ffffffff811a29cd: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b94f0)
Location: kernel/trace/ring_buffer.c:689
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff811b94f0-ffffffff811b95a2: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6f30)
Location: kernel/trace/ring_buffer.c:925
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff811b6f30-ffffffff811b6fe2: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b79c0)
Location: kernel/trace/ring_buffer.c:1011
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff811b79c0-ffffffff811b7a72: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1bf0)
Location: kernel/trace/ring_buffer.c:1011
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff811e1bf0-ffffffff811e1ca2: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812188f0)
Location: kernel/trace/ring_buffer.c:1047
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff812188f0-ffffffff812189ed: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81262750)
Location: kernel/trace/ring_buffer.c:1121
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff81262750-ffffffff812628f0: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81279730)
Location: kernel/trace/ring_buffer.c:1120
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff81279730-ffffffff812798d0: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct trace_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812941e0)
Location: kernel/trace/ring_buffer.c:944
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff812941e0-ffffffff812943a8: ring_buffer_poll_wait (STB_GLOBAL)
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
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021cdf0)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffff80001021cdf0-ffff80001021cee8: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045b8fc)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
c045b8fc-c045b9d8: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002a07a0)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
c0000000002a07a0-c0000000002a0918: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a626)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffe00017a626-ffffffe00017a6d6: ring_buffer_poll_wait (STB_GLOBAL)
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
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119af50)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff8119af50-ffffffff8119afed: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118dfd0)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff8118dfd0-ffffffff8118e06d: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198d20)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff81198d20-ffffffff81198dbd: ring_buffer_poll_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t ring_buffer_poll_wait(struct ring_buffer *buffer, int cpu, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6990)
Location: kernel/trace/ring_buffer.c:687
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_poll
```
**Symbols:**

```
ffffffff811a6990-ffffffff811a6a2d: ring_buffer_poll_wait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>__poll_t</code>
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
<b>Param added. </b>
<code>int full</code>
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
