# Function: <code>__tracing_resize_ring_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114c5a0)
Location: kernel/trace/trace.c:4220
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8114c5a0-ffffffff8114c6e8: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81154e40)
Location: kernel/trace/trace.c:4617
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff81154e40-ffffffff81154f69: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115f2d0)
Location: kernel/trace/trace.c:4866
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8115f2d0-ffffffff8115f3f9: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811627f0)
Location: kernel/trace/trace.c:5183
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff811627f0-ffffffff811628d6: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116f8c0)
Location: kernel/trace/trace.c:5187
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8116f8c0-ffffffff8116f9a6: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117e7b0)
Location: kernel/trace/trace.c:5193
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8117e7b0-ffffffff8117e896: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118c0b0)
Location: kernel/trace/trace.c:5216
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8118c0b0-ffffffff8118c196: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5437
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff81199610-ffffffff811996eb: __tracing_resize_ring_buffer (STB_LOCAL)
ffffffff811a19f8-ffffffff811a1a15: __tracing_resize_ring_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4eb0)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff811a4eb0-ffffffff811a4f93: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bd910)
Location: kernel/trace/trace.c:5693
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811bd910-ffffffff811bda3e: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb530)
Location: kernel/trace/trace.c:5766
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811bb530-ffffffff811bb65e: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bb0b0)
Location: kernel/trace/trace.c:6103
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
```
**Symbols:**

```
ffffffff811bb0b0-ffffffff811bb206: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6181
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff811e5920-ffffffff811e5b32: __tracing_resize_ring_buffer (STB_LOCAL)
ffffffff81cb4e0f-ffffffff81cb4e24: __tracing_resize_ring_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6193
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8121cfa0-ffffffff8121d1bf: __tracing_resize_ring_buffer (STB_LOCAL)
ffffffff81e65e62-ffffffff81e65e77: __tracing_resize_ring_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff81266880-ffffffff812669d2: __tracing_resize_ring_buffer (STB_LOCAL)
ffffffff8205d403-ffffffff8205d418: __tracing_resize_ring_buffer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6349
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8127d990-ffffffff8127dae2: __tracing_resize_ring_buffer (STB_LOCAL)
ffffffff820dbdba-ffffffff820dbdcf: __tracing_resize_ring_buffer.cold (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff8129bb91)
Location: kernel/trace/trace.c:6365
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8129ba90-ffffffff8129bb51: __tracing_resize_ring_buffer.part.0 (STB_LOCAL)
ffffffff821b7d68-ffffffff821b7d7d: __tracing_resize_ring_buffer.part.0.cold (STB_LOCAL)
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
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021ff90)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffff80001021ff90-ffff80001022009c: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045e0a8)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
c045e0a8-c045e1c8: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a3ca0)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
c0000000002a3ca0-c0000000002a3e60: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017c8da)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffe00017c8da-ffffffe00017c9ce: __tracing_resize_ring_buffer (STB_LOCAL)
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
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d4d0)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8119d4d0-ffffffff8119d5b3: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81190530)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff81190530-ffffffff81190613: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b2a0)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff8119b2a0-ffffffff8119b383: __tracing_resize_ring_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __tracing_resize_ring_buffer(struct trace_array *tr, long unsigned int size, int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8f40)
Location: kernel/trace/trace.c:5490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_entries_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_update_buffers
```
**Symbols:**

```
ffffffff811a8f40-ffffffff811a9023: __tracing_resize_ring_buffer (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
