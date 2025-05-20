# Function: <code>ring_buffer_record_is_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114a700)
Location: kernel/trace/ring_buffer.c:3135
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff8114a700-ffffffff8114a711: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81153150)
Location: kernel/trace/ring_buffer.c:3130
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff81153150-ffffffff81153161: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115d140)
Location: kernel/trace/ring_buffer.c:3099
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff8115d140-ffffffff8115d151: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81160150)
Location: kernel/trace/ring_buffer.c:3101
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff81160150-ffffffff81160161: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116d220)
Location: kernel/trace/ring_buffer.c:3093
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff8116d220-ffffffff8116d231: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117c270)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff8117c270-ffffffff8117c27c: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189a70)
Location: kernel/trace/ring_buffer.c:3289
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff81189a70-ffffffff81189a79: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197040)
Location: kernel/trace/ring_buffer.c:3266
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff81197040-ffffffff81197049: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2a40)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff811a2a40-ffffffff811a2a49: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b9620)
Location: kernel/trace/ring_buffer.c:3336
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811b9620-ffffffff811b9629: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7060)
Location: kernel/trace/ring_buffer.c:3882
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
```
**Symbols:**

```
ffffffff811b7060-ffffffff811b7069: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7af0)
Location: kernel/trace/ring_buffer.c:3989
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
```
**Symbols:**

```
ffffffff811b7af0-ffffffff811b7af9: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1d30)
Location: kernel/trace/ring_buffer.c:3989
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
```
**Symbols:**

```
ffffffff811e1d30-ffffffff811e1d39: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81218aa0)
Location: kernel/trace/ring_buffer.c:4027
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
```
**Symbols:**

```
ffffffff81218aa0-ffffffff81218aaf: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81262a00)
Location: kernel/trace/ring_buffer.c:4106
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
```
**Symbols:**

```
ffffffff81262a00-ffffffff81262a0f: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812799e0)
Location: kernel/trace/ring_buffer.c:4109
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
```
**Symbols:**

```
ffffffff812799e0-ffffffff812799ef: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812944c0)
Location: kernel/trace/ring_buffer.c:4013
Inline: False
```
**Symbols:**

```
ffffffff812944c0-ffffffff812944cf: ring_buffer_record_is_on (STB_GLOBAL)
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
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021cf50)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffff80001021cf50-ffff80001021cf60: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045ba7c)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
c045ba7c-c045ba98: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002a0990)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
c0000000002a0990-c0000000002a09a0: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a740)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffe00017a740-ffffffe00017a754: ring_buffer_record_is_on (STB_GLOBAL)
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
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119b060)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff8119b060-ffffffff8119b069: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118e0e0)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff8118e0e0-ffffffff8118e0e9: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198e30)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff81198e30-ffffffff81198e39: ring_buffer_record_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ring_buffer_record_is_on(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6ab0)
Location: kernel/trace/ring_buffer.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
```
**Symbols:**

```
ffffffff811a6ab0-ffffffff811a6ab9: ring_buffer_record_is_on (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
