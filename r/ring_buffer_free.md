# Function: <code>ring_buffer_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146b00)
Location: kernel/trace/ring_buffer.c:1390
Inline: False
Direct callers:
  - kernel/trace/trace.c:allocate_trace_buffer
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:trace_init
```
**Symbols:**

```
ffffffff81146b00-ffffffff81146b72: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114f350)
Location: kernel/trace/ring_buffer.c:1382
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8114f350-ffffffff8114f3c2: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811594e0)
Location: kernel/trace/ring_buffer.c:1358
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:free_trace_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811594e0-ffffffff81159556: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c3a0)
Location: kernel/trace/ring_buffer.c:1360
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8115c3a0-ffffffff8115c415: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169350)
Location: kernel/trace/ring_buffer.c:1363
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff81169350-ffffffff811693bc: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811782d0)
Location: kernel/trace/ring_buffer.c:1424
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff811782d0-ffffffff8117833c: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185760)
Location: kernel/trace/ring_buffer.c:1472
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
```
**Symbols:**

```
ffffffff81185760-ffffffff811857cc: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81192aa0)
Location: kernel/trace/ring_buffer.c:1449
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffff81192aa0-ffffffff81192b0d: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119e720)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffff8119e720-ffffffff8119e78d: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5440)
Location: kernel/trace/ring_buffer.c:1453
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b5440-ffffffff811b54ad: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2d10)
Location: kernel/trace/ring_buffer.c:1700
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b2d10-ffffffff811b2d7d: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3aa0)
Location: kernel/trace/ring_buffer.c:1783
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811b3aa0-ffffffff811b3b0d: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dda50)
Location: kernel/trace/ring_buffer.c:1783
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff811dda50-ffffffff811ddabd: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81214710)
Location: kernel/trace/ring_buffer.c:1819
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81214710-ffffffff81214783: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125e130)
Location: kernel/trace/ring_buffer.c:1881
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff8125e130-ffffffff8125e1b0: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812753f0)
Location: kernel/trace/ring_buffer.c:1877
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:allocate_trace_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff812753f0-ffffffff8127547a: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_free(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81290030)
Location: kernel/trace/ring_buffer.c:1718
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:allocate_trace_buffers
  - kernel/trace/trace.c:allocate_trace_buffer
```
**Symbols:**

```
ffffffff81290030-ffffffff812900ba: ring_buffer_free (STB_GLOBAL)
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
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217268)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffff800010217268-ffff8000102172e8: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c04568dc)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
c04568dc-c045694c: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c000000000299cc0)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
c000000000299cc0-c000000000299d78: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000176f82)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffe000176f82-ffffffe00017700a: ring_buffer_free (STB_GLOBAL)
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
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196d40)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffff81196d40-ffffffff81196dad: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a020)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffff8118a020-ffffffff8118a08d: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194b10)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffff81194b10-ffffffff81194b7d: ring_buffer_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_free(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2720)
Location: kernel/trace/ring_buffer.c:1450
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffff811a2720-ffffffff811a278d: ring_buffer_free (STB_GLOBAL)
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
