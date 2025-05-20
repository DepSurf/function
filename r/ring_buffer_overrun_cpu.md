# Function: <code>ring_buffer_overrun_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146f90)
Location: kernel/trace/ring_buffer.c:3272
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff81146f90-ffffffff81146fb4: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8114f7b0)
Location: kernel/trace/ring_buffer.c:3267
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff8114f7b0-ffffffff8114f7d2: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811599e0)
Location: kernel/trace/ring_buffer.c:3236
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff811599e0-ffffffff81159a05: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c7e0)
Location: kernel/trace/ring_buffer.c:3238
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff8115c7e0-ffffffff8115c805: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169780)
Location: kernel/trace/ring_buffer.c:3230
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff81169780-ffffffff811697a5: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811786f0)
Location: kernel/trace/ring_buffer.c:3379
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff811786f0-ffffffff81178718: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185bb0)
Location: kernel/trace/ring_buffer.c:3442
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff81185bb0-ffffffff81185bd8: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81193000)
Location: kernel/trace/ring_buffer.c:3419
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff81193000-ffffffff81193024: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119eee0)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff8119eee0-ffffffff8119ef04: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b5940)
Location: kernel/trace/ring_buffer.c:3489
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff811b5940-ffffffff811b5964: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b31c0)
Location: kernel/trace/ring_buffer.c:4035
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff811b31c0-ffffffff811b31e4: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3520)
Location: kernel/trace/ring_buffer.c:4142
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff811b3520-ffffffff811b3544: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dd250)
Location: kernel/trace/ring_buffer.c:4142
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff811dd250-ffffffff811dd274: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213af0)
Location: kernel/trace/ring_buffer.c:4180
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff81213af0-ffffffff81213b1e: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125d3e0)
Location: kernel/trace/ring_buffer.c:4259
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff8125d3e0-ffffffff8125d40e: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81274660)
Location: kernel/trace/ring_buffer.c:4262
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff81274660-ffffffff8127468e: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct trace_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128ecd0)
Location: kernel/trace/ring_buffer.c:4166
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:trace_total_entries_cpu
```
**Symbols:**

```
ffffffff8128ecd0-ffffffff8128ecfe: ring_buffer_overrun_cpu (STB_GLOBAL)
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
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010217448)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffff800010217448-ffff800010217484: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0456e08)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:get_total_entries_cpu
```
**Symbols:**

```
c0456e08-c0456e4c: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029a3f0)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
c00000000029a3f0-c00000000029a438: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001773d4)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffe0001773d4-ffffffe000177412: ring_buffer_overrun_cpu (STB_GLOBAL)
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
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197500)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff81197500-ffffffff81197524: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a7e0)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff8118a7e0-ffffffff8118a804: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811952d0)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff811952d0-ffffffff811952f4: ring_buffer_overrun_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int ring_buffer_overrun_cpu(struct ring_buffer *buffer, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2ee0)
Location: kernel/trace/ring_buffer.c:3420
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_stats_read
```
**Symbols:**

```
ffffffff811a2ee0-ffffffff811a2f04: ring_buffer_overrun_cpu (STB_GLOBAL)
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
