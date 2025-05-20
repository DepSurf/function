# Function: <code>ring_buffer_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81149870)
Location: kernel/trace/ring_buffer.c:4132
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81149870-ffffffff811498e6: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152320)
Location: kernel/trace/ring_buffer.c:4127
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81152320-ffffffff81152396: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c6d0)
Location: kernel/trace/ring_buffer.c:4096
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8115c6d0-ffffffff8115c746: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115f730)
Location: kernel/trace/ring_buffer.c:4110
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8115f730-ffffffff8115f7a6: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116c7f0)
Location: kernel/trace/ring_buffer.c:4102
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8116c7f0-ffffffff8116c866: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117b2d0)
Location: kernel/trace/ring_buffer.c:4264
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8117b2d0-ffffffff8117b346: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81188890)
Location: kernel/trace/ring_buffer.c:4329
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81188890-ffffffff81188906: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195510)
Location: kernel/trace/ring_buffer.c:4307
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81195510-ffffffff81195577: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a13f0)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811a13f0-ffffffff811a1457: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021bd80)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffff80001021bd80-ffff80001021be5c: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0459498)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
c0459498-c0459508: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029dcd0)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
c00000000029dcd0-c00000000029ddc0: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000179a50)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffe000179a50-ffffffe000179ac4: ring_buffer_read (STB_GLOBAL)
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
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81199a10)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff81199a10-ffffffff81199a77: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118d0a0)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff8118d0a0-ffffffff8118d107: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811977e0)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811977e0-ffffffff81197847: ring_buffer_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer_event *ring_buffer_read(struct ring_buffer_iter *iter, u64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a5410)
Location: kernel/trace/ring_buffer.c:4308
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_iter_reset
  - kernel/trace/trace.c:trace_find_next_entry_inc
  - kernel/trace/trace_functions_graph.c:print_graph_entry
```
**Symbols:**

```
ffffffff811a5410-ffffffff811a5477: ring_buffer_read (STB_GLOBAL)
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
