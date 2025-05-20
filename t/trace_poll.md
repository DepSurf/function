# Function: <code>trace_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114ba60)
Location: kernel/trace/trace.c:4657
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_poll_pipe
  - kernel/trace/trace.c:tracing_buffers_poll
```
**Symbols:**

```
ffffffff8114ba60-ffffffff8114baad: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81154480)
Location: kernel/trace/trace.c:5054
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff81154480-ffffffff811544cd: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115eac0)
Location: kernel/trace/trace.c:5303
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8115eac0-ffffffff8115eb0d: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161cf0)
Location: kernel/trace/trace.c:5620
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff81161cf0-ffffffff81161d3b: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116edc0)
Location: kernel/trace/trace.c:5631
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8116edc0-ffffffff8116ee0b: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117de30)
Location: kernel/trace/trace.c:5637
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8117de30-ffffffff8117de7a: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118b720)
Location: kernel/trace/trace.c:5659
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8118b720-ffffffff8118b76a: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198a70)
Location: kernel/trace/trace.c:5890
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff81198a70-ffffffff81198aba: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4360)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff811a4360-ffffffff811a43aa: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba977)
Location: kernel/trace/trace.c:6144
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b98fa)
Location: kernel/trace/trace.c:6217
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b8dfa)
Location: kernel/trace/trace.c:6554
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e474a)
Location: kernel/trace/trace.c:6632
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121a4ea)
Location: kernel/trace/trace.c:6646
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812641ea)
Location: kernel/trace/trace.c:6684
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127b21a)
Location: kernel/trace/trace.c:6840
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129754a)
Location: kernel/trace/trace.c:6855
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
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
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021f2e8)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffff80001021f2e8-ffff80001021f340: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045d744)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
c045d744-c045d7a0: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a2c70)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
c0000000002a2c70-c0000000002a2cec: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017bd82)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffe00017bd82-ffffffe00017bdd4: trace_poll (STB_LOCAL)
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
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c980)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8119c980-ffffffff8119c9ca: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f9e0)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8118f9e0-ffffffff8118fa2a: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119a750)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff8119a750-ffffffff8119a79a: trace_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__poll_t trace_poll(struct trace_iterator *iter, struct file *filp, poll_table *poll_table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a83f0)
Location: kernel/trace/trace.c:5941
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_poll
  - kernel/trace/trace.c:tracing_poll_pipe
```
**Symbols:**

```
ffffffff811a83f0-ffffffff811a843a: trace_poll (STB_LOCAL)
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
<code>unsigned int</code> ➡️ <code>__poll_t</code>
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
