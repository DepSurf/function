# Function: <code>__ring_buffer_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114a0c0)
Location: kernel/trace/ring_buffer.c:1301
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:trace_init
```
**Symbols:**

```
ffffffff8114a0c0-ffffffff8114a2df: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152b10)
Location: kernel/trace/ring_buffer.c:1292
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81152b10-ffffffff81152d2d: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cb50)
Location: kernel/trace/ring_buffer.c:1285
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8115cb50-ffffffff8115cd14: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115fba0)
Location: kernel/trace/ring_buffer.c:1287
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8115fba0-ffffffff8115fd60: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116cc70)
Location: kernel/trace/ring_buffer.c:1290
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff8116cc70-ffffffff8116ce1e: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117bc30)
Location: kernel/trace/ring_buffer.c:1351
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff8117bc30-ffffffff8117bdde: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81188d30)
Location: kernel/trace/ring_buffer.c:1399
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff81188d30-ffffffff81188ede: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194e50)
Location: kernel/trace/ring_buffer.c:1376
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81194e50-ffffffff81195007: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0910)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811a0910-ffffffff811a0ac7: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6ef0)
Location: kernel/trace/ring_buffer.c:1380
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b6ef0-ffffffff811b70b1: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4ab0)
Location: kernel/trace/ring_buffer.c:1627
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b4ab0-ffffffff811b4c7a: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3e70)
Location: kernel/trace/ring_buffer.c:1710
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b3e70-ffffffff811b4044: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dde80)
Location: kernel/trace/ring_buffer.c:1710
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811dde80-ffffffff811de054: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81214fc0)
Location: kernel/trace/ring_buffer.c:1746
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81214fc0-ffffffff812151bb: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125e690)
Location: kernel/trace/ring_buffer.c:1808
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8125e690-ffffffff8125e878: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81275870)
Location: kernel/trace/ring_buffer.c:1804
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81275870-ffffffff81275a58: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812900d0)
Location: kernel/trace/ring_buffer.c:1638
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff812900d0-ffffffff812902d3: __ring_buffer_alloc (STB_GLOBAL)
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
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021a0e8)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffff80001021a0e8-ffff80001021a2ec: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c04575b0)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
c04575b0-c0457754: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029d3e0)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
c00000000029d3e0-c00000000029d668: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177e02)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffe000177e02-ffffffe000177f9c: __ring_buffer_alloc (STB_GLOBAL)
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
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198f30)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81198f30-ffffffff811990e7: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118c770)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8118c770-ffffffff8118c927: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196d00)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81196d00-ffffffff81196eb7: __ring_buffer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ring_buffer *__ring_buffer_alloc(long unsigned int size, unsigned int flags, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4910)
Location: kernel/trace/ring_buffer.c:1377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811a4910-ffffffff811a4ac7: __ring_buffer_alloc (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>struct ring_buffer *</code> ➡️ <code>struct trace_buffer *</code>
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
