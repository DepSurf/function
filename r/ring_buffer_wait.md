# Function: <code>ring_buffer_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, bool full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114a440)
Location: kernel/trace/ring_buffer.c:526
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8114a440-ffffffff8114a624: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, bool full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152eb0)
Location: kernel/trace/ring_buffer.c:526
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff81152eb0-ffffffff8115308a: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, bool full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cea0)
Location: kernel/trace/ring_buffer.c:524
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8115cea0-ffffffff8115d073: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, bool full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115fec0)
Location: kernel/trace/ring_buffer.c:526
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8115fec0-ffffffff8116008d: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, bool full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116cf90)
Location: kernel/trace/ring_buffer.c:529
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8116cf90-ffffffff8116d142: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, bool full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117bf80)
Location: kernel/trace/ring_buffer.c:558
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8117bf80-ffffffff8117c14f: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189700)
Location: kernel/trace/ring_buffer.c:598
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff81189700-ffffffff81189942: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196d00)
Location: kernel/trace/ring_buffer.c:575
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff81196d00-ffffffff81196f28: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a26a0)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff811a26a0-ffffffff811a292a: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b9250)
Location: kernel/trace/ring_buffer.c:578
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff811b9250-ffffffff811b94ec: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6c60)
Location: kernel/trace/ring_buffer.c:814
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff811b6c60-ffffffff811b6f28: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b76f0)
Location: kernel/trace/ring_buffer.c:900
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff811b76f0-ffffffff811b79b8: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1920)
Location: kernel/trace/ring_buffer.c:900
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff811e1920-ffffffff811e1be8: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812185e0)
Location: kernel/trace/ring_buffer.c:936
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff812185e0-ffffffff812188f0: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812623f0)
Location: kernel/trace/ring_buffer.c:1004
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff812623f0-ffffffff81262739: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81279440)
Location: kernel/trace/ring_buffer.c:1003
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_wait_pipe
```
**Symbols:**

```
ffffffff81279440-ffffffff81279718: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ring_buffer_wait(struct trace_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81293fe0)
Location: kernel/trace/ring_buffer.c:855
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff81293fe0-ffffffff812941ca: ring_buffer_wait (STB_GLOBAL)
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
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021cb60)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffff80001021cb60-ffff80001021cdf0: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045b6c8)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
c045b6c8-c045b8fc: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002a0480)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
c0000000002a0480-c0000000002a079c: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a450)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffe00017a450-ffffffe00017a626: ring_buffer_wait (STB_GLOBAL)
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
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119acc0)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8119acc0-ffffffff8119af4a: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118dd40)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff8118dd40-ffffffff8118dfca: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198a90)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff81198a90-ffffffff81198d1a: ring_buffer_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ring_buffer_wait(struct ring_buffer *buffer, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6700)
Location: kernel/trace/ring_buffer.c:576
Inline: False
Direct callers:
  - kernel/trace/trace.c:wait_on_pipe
```
**Symbols:**

```
ffffffff811a6700-ffffffff811a698a: ring_buffer_wait (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>bool full</code> ➡️ <code>int full</code>
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
