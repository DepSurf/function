# Function: <code>ring_buffer_peek</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148980)
Location: kernel/trace/ring_buffer.c:3905
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81148980-ffffffff81148ab0: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81150c80)
Location: kernel/trace/ring_buffer.c:3900
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81150c80-ffffffff81150db2: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115bd00)
Location: kernel/trace/ring_buffer.c:3869
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8115bd00-ffffffff8115be35: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115ebc0)
Location: kernel/trace/ring_buffer.c:3883
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8115ebc0-ffffffff8115ecd3: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116bec0)
Location: kernel/trace/ring_buffer.c:3875
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8116bec0-ffffffff8116bfd3: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117a830)
Location: kernel/trace/ring_buffer.c:4037
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8117a830-ffffffff8117a944: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81187ed0)
Location: kernel/trace/ring_buffer.c:4102
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81187ed0-ffffffff81187fe4: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195e60)
Location: kernel/trace/ring_buffer.c:4079
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81195e60-ffffffff81195f76: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a1830)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811a1830-ffffffff811a1946: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7fd0)
Location: kernel/trace/ring_buffer.c:4162
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811b7fd0-ffffffff811b80e6: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5b90)
Location: kernel/trace/ring_buffer.c:4708
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811b5b90-ffffffff811b5ca1: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6cd0)
Location: kernel/trace/ring_buffer.c:4815
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811b6cd0-ffffffff811b6df2: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e0ec0)
Location: kernel/trace/ring_buffer.c:4815
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811e0ec0-ffffffff811e0fe2: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81217b50)
Location: kernel/trace/ring_buffer.c:4857
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81217b50-ffffffff81217cd3: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81261060)
Location: kernel/trace/ring_buffer.c:4963
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81261060-ffffffff812611e3: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812780f0)
Location: kernel/trace/ring_buffer.c:4970
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff812780f0-ffffffff81278273: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct trace_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81292bf0)
Location: kernel/trace/ring_buffer.c:4876
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81292bf0-ffffffff81292d73: ring_buffer_peek (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010219320)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffff800010219320-ffff800010219518: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0458cf8)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
c0458cf8-c0458e40: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029f400)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
c00000000029f400-c00000000029f6bc: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001791b0)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffe0001791b0-ffffffe00017930e: ring_buffer_peek (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81199e50)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81199e50-ffffffff81199f66: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118c290)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8118c290-ffffffff8118c391: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197c20)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81197c20-ffffffff81197d36: ring_buffer_peek (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_peek(struct ring_buffer *buffer, int cpu, u64 *ts, long unsigned int *lost_events);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a5850)
Location: kernel/trace/ring_buffer.c:4080
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811a5850-ffffffff811a5954: ring_buffer_peek (STB_GLOBAL)
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
