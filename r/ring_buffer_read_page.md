# Function: <code>ring_buffer_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811498f0)
Location: kernel/trace/ring_buffer.c:4477
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811498f0-ffffffff81149cdd: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152720)
Location: kernel/trace/ring_buffer.c:4472
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81152720-ffffffff81152b0f: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c750)
Location: kernel/trace/ring_buffer.c:4441
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8115c750-ffffffff8115cb45: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115f7b0)
Location: kernel/trace/ring_buffer.c:4492
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8115f7b0-ffffffff8115fb95: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116c870)
Location: kernel/trace/ring_buffer.c:4490
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8116c870-ffffffff8116cc65: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117b830)
Location: kernel/trace/ring_buffer.c:4652
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8117b830-ffffffff8117bc2a: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81188910)
Location: kernel/trace/ring_buffer.c:4721
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81188910-ffffffff81188d2d: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811960a0)
Location: kernel/trace/ring_buffer.c:4699
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811960a0-ffffffff811964c2: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a1a70)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811a1a70-ffffffff811a1e92: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7a90)
Location: kernel/trace/ring_buffer.c:4792
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811b7a90-ffffffff811b7eda: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5650)
Location: kernel/trace/ring_buffer.c:5402
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811b5650-ffffffff811b5a9a: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6f30)
Location: kernel/trace/ring_buffer.c:5511
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811b6f30-ffffffff811b7378: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1120)
Location: kernel/trace/ring_buffer.c:5516
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811e1120-ffffffff811e1557: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81217e30)
Location: kernel/trace/ring_buffer.c:5558
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81217e30-ffffffff812182a7: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81261360)
Location: kernel/trace/ring_buffer.c:5670
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81261360-ffffffff812617ec: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812783f0)
Location: kernel/trace/ring_buffer.c:5702
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff812783f0-ffffffff8127886e: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ring_buffer_read_page(struct trace_buffer *buffer, struct buffer_data_read_page *data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81292ef0)
Location: kernel/trace/ring_buffer.c:5637
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81292ef0-ffffffff8129331f: ring_buffer_read_page (STB_GLOBAL)
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
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010218d78)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffff800010218d78-ffff8000102191c4: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045a908)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
c045a908-c045acfc: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029eca0)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
c00000000029eca0-c00000000029f1dc: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000179ac4)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffe000179ac4-ffffffe000179e32: ring_buffer_read_page (STB_GLOBAL)
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
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119a090)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8119a090-ffffffff8119a4b2: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118d110)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8118d110-ffffffff8118d532: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197e60)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff81197e60-ffffffff81198282: ring_buffer_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ring_buffer_read_page(struct ring_buffer *buffer, void **data_page, size_t len, int cpu, int full);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a5a90)
Location: kernel/trace/ring_buffer.c:4700
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff811a5a90-ffffffff811a5eb2: ring_buffer_read_page (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>void **data_page</code> ➡️ <code>struct buffer_data_read_page *data_page</code>
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
