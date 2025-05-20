# Function: <code>ring_buffer_consume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148ab0)
Location: kernel/trace/ring_buffer.c:3969
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81148ab0-ffffffff81148bd6: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81150dc0)
Location: kernel/trace/ring_buffer.c:3964
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81150dc0-ffffffff81150f01: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115be40)
Location: kernel/trace/ring_buffer.c:3933
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8115be40-ffffffff8115bf72: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115ece0)
Location: kernel/trace/ring_buffer.c:3947
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8115ece0-ffffffff8115edfe: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116bfe0)
Location: kernel/trace/ring_buffer.c:3939
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8116bfe0-ffffffff8116c0fe: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117a950)
Location: kernel/trace/ring_buffer.c:4101
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8117a950-ffffffff8117aa74: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81187ff0)
Location: kernel/trace/ring_buffer.c:4166
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81187ff0-ffffffff81188114: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195f80)
Location: kernel/trace/ring_buffer.c:4143
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81195f80-ffffffff8119609d: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a1950)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811a1950-ffffffff811a1a6d: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b80f0)
Location: kernel/trace/ring_buffer.c:4240
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811b80f0-ffffffff811b820c: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5cb0)
Location: kernel/trace/ring_buffer.c:4786
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811b5cb0-ffffffff811b5dcc: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6e00)
Location: kernel/trace/ring_buffer.c:4893
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811b6e00-ffffffff811b6f2f: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e0ff0)
Location: kernel/trace/ring_buffer.c:4893
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811e0ff0-ffffffff811e111f: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81217ce0)
Location: kernel/trace/ring_buffer.c:4935
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81217ce0-ffffffff81217e29: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81261200)
Location: kernel/trace/ring_buffer.c:5041
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81261200-ffffffff81261349: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81278290)
Location: kernel/trace/ring_buffer.c:5048
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81278290-ffffffff812783d9: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81292d90)
Location: kernel/trace/ring_buffer.c:4954
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81292d90-ffffffff81292ed9: ring_buffer_consume (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010219518)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffff800010219518-ffff8000102196f0: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0458e40)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
c0458e40-c0458fbc: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029f6c0)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
c00000000029f6c0-c00000000029f8f8: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017930e)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffe00017930e-ffffffe000179468: ring_buffer_consume (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81199f70)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81199f70-ffffffff8119a08d: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118c3a0)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8118c3a0-ffffffff8118c4a8: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197d40)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81197d40-ffffffff81197e5d: ring_buffer_consume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_consume(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a5960)
Location: kernel/trace/ring_buffer.c:4144
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811a5960-ffffffff811a5a90: ring_buffer_consume (STB_GLOBAL)
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
