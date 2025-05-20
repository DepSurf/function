# Function: <code>resize_buffer_duplicate_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114c330)
Location: kernel/trace/trace.c:4194
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8114c330-ffffffff8114c3ca: resize_buffer_duplicate_size.isra.30.part.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81154f01)
Location: kernel/trace/trace.c:4591
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff81154da0-ffffffff81154e3a: resize_buffer_duplicate_size.isra.34.part.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115f391)
Location: kernel/trace/trace.c:4840
Inline: True
Inline callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8115f230-ffffffff8115f2cc: resize_buffer_duplicate_size.isra.31.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162700)
Location: kernel/trace/trace.c:5157
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff81162700-ffffffff811627e7: resize_buffer_duplicate_size.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116f620)
Location: kernel/trace/trace.c:5161
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8116f620-ffffffff8116f6f8: resize_buffer_duplicate_size.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117e680)
Location: kernel/trace/trace.c:5167
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8117e680-ffffffff8117e755: resize_buffer_duplicate_size.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118bf80)
Location: kernel/trace/trace.c:5190
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8118bf80-ffffffff8118c055: resize_buffer_duplicate_size.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811994d0)
Location: kernel/trace/trace.c:5411
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff811994d0-ffffffff811995b2: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4d70)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff811a4d70-ffffffff811a4e52: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9960)
Location: kernel/trace/trace.c:5667
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff811b9960-ffffffff811b9a38: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b74c0)
Location: kernel/trace/trace.c:5740
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff811b74c0-ffffffff811b7598: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b8140)
Location: kernel/trace/trace.c:6077
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff811b8140-ffffffff811b8218: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e24e0)
Location: kernel/trace/trace.c:6155
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff811e24e0-ffffffff811e26de: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81219210)
Location: kernel/trace/trace.c:6167
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff81219210-ffffffff8121940d: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81266660)
Location: kernel/trace/trace.c:6200
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff81266660-ffffffff81266867: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127d770)
Location: kernel/trace/trace.c:6323
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
**Symbols:**

```
ffffffff8127d770-ffffffff8127d977: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int resize_buffer_duplicate_size(struct array_buffer *trace_buf, struct array_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81298540)
Location: kernel/trace/trace.c:6339
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
```
**Symbols:**

```
ffffffff81298540-ffffffff81298747: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffff80001021fdd0)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffff80001021fdd0-ffff80001021ff14: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int resize_buffer_duplicate_size(struct trace_buffer *trace_buf, struct trace_buffer *size_buf, int cpu_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045dfb8)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
c045dfb8-c045e0a8: resize_buffer_duplicate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c0000000002a3a50)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
c0000000002a3a50-c0000000002a3bf0: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017c77a)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffe00017c77a-ffffffe00017c86e: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d390)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8119d390-ffffffff8119d472: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811903f0)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff811903f0-ffffffff811904d2: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b160)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff8119b160-ffffffff8119b242: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8e00)
Location: kernel/trace/trace.c:5464
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
```
**Symbols:**

```
ffffffff811a8e00-ffffffff811a8ee2: resize_buffer_duplicate_size.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
