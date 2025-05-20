# Function: <code>ring_buffer_record_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146290)
Location: kernel/trace/ring_buffer.c:3094
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot
  - kernel/trace/trace.c:trace_init
```
**Symbols:**

```
ffffffff81146290-ffffffff811462af: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114eae0)
Location: kernel/trace/ring_buffer.c:3089
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot
```
**Symbols:**

```
ffffffff8114eae0-ffffffff8114eaff: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81158a20)
Location: kernel/trace/ring_buffer.c:3058
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot
```
**Symbols:**

```
ffffffff81158a20-ffffffff81158a3f: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115bd50)
Location: kernel/trace/ring_buffer.c:3060
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
```
**Symbols:**

```
ffffffff8115bd50-ffffffff8115bd6f: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81168e10)
Location: kernel/trace/ring_buffer.c:3052
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
```
**Symbols:**

```
ffffffff81168e10-ffffffff81168e2f: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81177db0)
Location: kernel/trace/ring_buffer.c:3185
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
```
**Symbols:**

```
ffffffff81177db0-ffffffff81177dcf: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185350)
Location: kernel/trace/ring_buffer.c:3248
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
```
**Symbols:**

```
ffffffff81185350-ffffffff8118536f: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811924f0)
Location: kernel/trace/ring_buffer.c:3225
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811924f0-ffffffff8119250a: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119e1a0)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff8119e1a0-ffffffff8119e1ba: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4a50)
Location: kernel/trace/ring_buffer.c:3295
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811b4a50-ffffffff811b4a6a: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2300)
Location: kernel/trace/ring_buffer.c:3841
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811b2300-ffffffff811b231a: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2e00)
Location: kernel/trace/ring_buffer.c:3948
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811b2e00-ffffffff811b2e1a: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dcd30)
Location: kernel/trace/ring_buffer.c:3948
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811dcd30-ffffffff811dcd4a: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812131f0)
Location: kernel/trace/ring_buffer.c:3986
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff812131f0-ffffffff81213218: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125ca30)
Location: kernel/trace/ring_buffer.c:4065
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff8125ca30-ffffffff8125ca58: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273b60)
Location: kernel/trace/ring_buffer.c:4068
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff81273b60-ffffffff81273b9e: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_record_off(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e160)
Location: kernel/trace/ring_buffer.c:3972
Inline: False
Direct callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff8128e160-ffffffff8128e19e: ring_buffer_record_off (STB_GLOBAL)
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
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217668)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffff800010217668-ffff8000102176ac: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0455e3c)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
c0455e3c-c0455e84: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c000000000299370)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
c000000000299370-c0000000002993ec: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017694c)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffe00017694c-ffffffe000176982: ring_buffer_record_off (STB_GLOBAL)
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
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811967c0)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811967c0-ffffffff811967da: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811898d0)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811898d0-ffffffff811898ea: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194590)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff81194590-ffffffff811945aa: ring_buffer_record_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_record_off(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2170)
Location: kernel/trace/ring_buffer.c:3226
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
```
**Symbols:**

```
ffffffff811a2170-ffffffff811a218a: ring_buffer_record_off (STB_GLOBAL)
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
