# Function: <code>ring_buffer_normalize_time_stamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146210)
Location: kernel/trace/ring_buffer.c:706
Inline: True
```
**Symbols:**

```
ffffffff81146210-ffffffff81146216: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114ea60)
Location: kernel/trace/ring_buffer.c:706
Inline: True
```
**Symbols:**

```
ffffffff8114ea60-ffffffff8114ea66: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811589a0)
Location: kernel/trace/ring_buffer.c:704
Inline: True
```
**Symbols:**

```
ffffffff811589a0-ffffffff811589a6: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115bcd0)
Location: kernel/trace/ring_buffer.c:706
Inline: True
```
**Symbols:**

```
ffffffff8115bcd0-ffffffff8115bcd6: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81168d90)
Location: kernel/trace/ring_buffer.c:709
Inline: True
```
**Symbols:**

```
ffffffff81168d90-ffffffff81168d96: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81177c00)
Location: kernel/trace/ring_buffer.c:738
Inline: True
```
**Symbols:**

```
ffffffff81177c00-ffffffff81177c01: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811851a0)
Location: kernel/trace/ring_buffer.c:785
Inline: True
```
**Symbols:**

```
ffffffff811851a0-ffffffff811851a1: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195422)
Location: kernel/trace/ring_buffer.c:762
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffff81192470-ffffffff81192471: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a1312)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffff8119e120-ffffffff8119e121: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6632)
Location: kernel/trace/ring_buffer.c:765
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff811b49d0-ffffffff811b49d1: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b40e2)
Location: kernel/trace/ring_buffer.c:1009
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff811b22d0-ffffffff811b22d1: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5052)
Location: kernel/trace/ring_buffer.c:1095
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff811b2dd0-ffffffff811b2dd1: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811df2b2)
Location: kernel/trace/ring_buffer.c:1095
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff811dcd00-ffffffff811dcd01: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216a2e)
Location: kernel/trace/ring_buffer.c:1131
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff812131c0-ffffffff812131c5: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125ff1e)
Location: kernel/trace/ring_buffer.c:1215
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff8125c9d0-ffffffff8125c9d5: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812771f6)
Location: kernel/trace/ring_buffer.c:1214
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff81273910-ffffffff81273915: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct trace_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81291c56)
Location: kernel/trace/ring_buffer.c:1046
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
Direct callers:
  - kernel/trace/trace.c:tracing_reset_online_cpus
  - kernel/trace/trace.c:ftrace_now
```
**Symbols:**

```
ffffffff8128dea0-ffffffff8128dea5: ring_buffer_normalize_time_stamp (STB_GLOBAL)
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
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021bc24)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffff800010216f90-ffff800010216f94: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0459340)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
c0455d14-c0455d24: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029db48)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
c0000000002992c0-c0000000002992c4: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017999e)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffe0001768c8-ffffffe0001768d4: ring_buffer_normalize_time_stamp (STB_GLOBAL)
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
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81199932)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffff81196740-ffffffff81196741: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118cfc2)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffff81189850-ffffffff81189851: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197702)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffff81194510-ffffffff81194511: ring_buffer_normalize_time_stamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ring_buffer_normalize_time_stamp(struct ring_buffer *buffer, int cpu, u64 *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a5332)
Location: kernel/trace/ring_buffer.c:763
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_buffer_peek
```
**Symbols:**

```
ffffffff811a20f0-ffffffff811a20f1: ring_buffer_normalize_time_stamp (STB_GLOBAL)
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
