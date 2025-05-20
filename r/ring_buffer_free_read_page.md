# Function: <code>ring_buffer_free_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146a30)
Location: kernel/trace/ring_buffer.c:4438
Inline: False
Direct callers:
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_splice_read
```
**Symbols:**

```
ffffffff81146a30-ffffffff81146a40: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114f280)
Location: kernel/trace/ring_buffer.c:4433
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff8114f280-ffffffff8114f290: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81159410)
Location: kernel/trace/ring_buffer.c:4402
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff81159410-ffffffff81159420: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115eeb0)
Location: kernel/trace/ring_buffer.c:4438
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff8115eeb0-ffffffff8115ef31: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811691b0)
Location: kernel/trace/ring_buffer.c:4430
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811691b0-ffffffff8116927f: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117b350)
Location: kernel/trace/ring_buffer.c:4592
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff8117b350-ffffffff8117b41f: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185690)
Location: kernel/trace/ring_buffer.c:4661
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff81185690-ffffffff8118575d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811929d0)
Location: kernel/trace/ring_buffer.c:4639
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811929d0-ffffffff81192a9d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119e650)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff8119e650-ffffffff8119e71d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5bc0)
Location: kernel/trace/ring_buffer.c:4732
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811b5bc0-ffffffff811b5c8d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b34a0)
Location: kernel/trace/ring_buffer.c:5342
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811b34a0-ffffffff811b356d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b56a0)
Location: kernel/trace/ring_buffer.c:5451
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811b56a0-ffffffff811b5773: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811df7c0)
Location: kernel/trace/ring_buffer.c:5456
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811df7c0-ffffffff811df893: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812135a0)
Location: kernel/trace/ring_buffer.c:5498
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff812135a0-ffffffff81213686: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125cd60)
Location: kernel/trace/ring_buffer.c:5605
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff8125cd60-ffffffff8125ce57: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273d50)
Location: kernel/trace/ring_buffer.c:5637
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff81273d50-ffffffff81273e47: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer *buffer, int cpu, struct buffer_data_read_page *data_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e350)
Location: kernel/trace/ring_buffer.c:5565
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_read
```
**Symbols:**

```
ffffffff8128e350-ffffffff8128e470: ring_buffer_free_read_page (STB_GLOBAL)
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
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217f30)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffff800010217f30-ffff800010218038: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c04585e8)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
c04585e8-c04586b8: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029e640)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
c00000000029e640-c00000000029e7e8: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000176f06)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffe000176f06-ffffffe000176f82: ring_buffer_free_read_page (STB_GLOBAL)
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
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196c70)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff81196c70-ffffffff81196d3d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189f60)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff81189f60-ffffffff8118a017: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194a40)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff81194a40-ffffffff81194b0d: ring_buffer_free_read_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer *buffer, int cpu, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2650)
Location: kernel/trace/ring_buffer.c:4640
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_buffers_release
```
**Symbols:**

```
ffffffff811a2650-ffffffff811a271d: ring_buffer_free_read_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>buffer, data</code> ➡️ <code>buffer, cpu, data</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>struct buffer_data_read_page *data_page</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
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
