# Function: <code>ring_buffer_alloc_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811468e0)
Location: kernel/trace/ring_buffer.c:4413
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811468e0-ffffffff8114695b: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114f130)
Location: kernel/trace/ring_buffer.c:4408
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8114f130-ffffffff8114f1a5: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811592d0)
Location: kernel/trace/ring_buffer.c:4377
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811592d0-ffffffff8115933f: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115ef40)
Location: kernel/trace/ring_buffer.c:4391
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8115ef40-ffffffff8115f038: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116ba30)
Location: kernel/trace/ring_buffer.c:4383
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8116ba30-ffffffff8116bb34: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117aea0)
Location: kernel/trace/ring_buffer.c:4545
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8117aea0-ffffffff8117afab: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811879c0)
Location: kernel/trace/ring_buffer.c:4614
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811879c0-ffffffff81187ac4: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195010)
Location: kernel/trace/ring_buffer.c:4592
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81195010-ffffffff8119510f: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0ad0)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811a0ad0-ffffffff811a0bcf: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7370)
Location: kernel/trace/ring_buffer.c:4685
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811b7370-ffffffff811b744f: ring_buffer_alloc_read_page.part.0.isra.0 (STB_LOCAL)
ffffffff811b7450-ffffffff811b7473: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4f30)
Location: kernel/trace/ring_buffer.c:5295
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811b4f30-ffffffff811b500f: ring_buffer_alloc_read_page.part.0.isra.0 (STB_LOCAL)
ffffffff811b5010-ffffffff811b5033: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7380)
Location: kernel/trace/ring_buffer.c:5404
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811b7380-ffffffff811b7488: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1560)
Location: kernel/trace/ring_buffer.c:5409
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811e1560-ffffffff811e1686: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81217530)
Location: kernel/trace/ring_buffer.c:5451
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81217530-ffffffff81217645: ring_buffer_alloc_read_page.part.0.isra.0 (STB_LOCAL)
ffffffff81217650-ffffffff81217687: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81260990)
Location: kernel/trace/ring_buffer.c:5558
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81260990-ffffffff81260aab: ring_buffer_alloc_read_page.part.0.isra.0 (STB_LOCAL)
ffffffff81260ac0-ffffffff81260af7: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81277a20)
Location: kernel/trace/ring_buffer.c:5590
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81277a20-ffffffff81277b3b: ring_buffer_alloc_read_page.part.0.isra.0 (STB_LOCAL)
ffffffff81277b50-ffffffff81277b87: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct buffer_data_read_page *ring_buffer_alloc_read_page(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81292470)
Location: kernel/trace/ring_buffer.c:5511
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81292470-ffffffff81292618: ring_buffer_alloc_read_page.part.0 (STB_LOCAL)
ffffffff81292630-ffffffff81292663: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217cb8)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffff800010217cb8-ffff800010217e00: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0458464)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
c0458464-c0458564: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029e410)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
c00000000029e410-c00000000029e640: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017789a)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffe00017789a-ffffffe000177950: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811990f0)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811990f0-ffffffff811991ef: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a9a0)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8118a9a0-ffffffff8118aa8a: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196ec0)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81196ec0-ffffffff81196fbf: ring_buffer_alloc_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *ring_buffer_alloc_read_page(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4ad0)
Location: kernel/trace/ring_buffer.c:4593
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811a4ad0-ffffffff811a4bcf: ring_buffer_alloc_read_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>struct buffer_data_read_page *</code>
</li>
</ul>
</details>
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
