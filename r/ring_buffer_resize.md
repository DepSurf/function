# Function: <code>ring_buffer_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81148370)
Location: kernel/trace/ring_buffer.c:1650
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff81148370-ffffffff811487a5: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811501b0)
Location: kernel/trace/ring_buffer.c:1642
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff811501b0-ffffffff811505e8: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115b2e0)
Location: kernel/trace/ring_buffer.c:1611
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff8115b2e0-ffffffff8115b74a: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115e1b0)
Location: kernel/trace/ring_buffer.c:1613
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff8115e1b0-ffffffff8115e632: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116b160)
Location: kernel/trace/ring_buffer.c:1616
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff8116b160-ffffffff8116b589: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117a2a0)
Location: kernel/trace/ring_buffer.c:1689
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff8117a2a0-ffffffff8117a64b: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81187270)
Location: kernel/trace/ring_buffer.c:1737
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff81187270-ffffffff8118761b: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194680)
Location: kernel/trace/ring_buffer.c:1714
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff81194680-ffffffff81194a18: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff81194a20-ffffffff81194a44: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a0140)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff811a0140-ffffffff811a04d8: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811a04e0-ffffffff811a0504: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b86a0)
Location: kernel/trace/ring_buffer.c:1718
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff811b86a0-ffffffff811b8adf: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811b8ae0-ffffffff811b8b04: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6130)
Location: kernel/trace/ring_buffer.c:1965
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff811b6130-ffffffff811b651a: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811b6520-ffffffff811b6544: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b6400)
Location: kernel/trace/ring_buffer.c:2048
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff811b6400-ffffffff811b67d9: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811b67e0-ffffffff811b6804: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e05f0)
Location: kernel/trace/ring_buffer.c:2048
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff811e05f0-ffffffff811e09c9: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811e09d0-ffffffff811e09f4: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81214830)
Location: kernel/trace/ring_buffer.c:2084
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff81214830-ffffffff81214c8f: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125fff0)
Location: kernel/trace/ring_buffer.c:2149
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff8125fff0-ffffffff812604ae: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812772b0)
Location: kernel/trace/ring_buffer.c:2145
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff812772b0-ffffffff81277748: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ring_buffer_resize(struct trace_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81291d10)
Location: kernel/trace/ring_buffer.c:1986
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:resize_buffer_duplicate_size
```
**Symbols:**

```
ffffffff81291d10-ffffffff8129219f: ring_buffer_resize (STB_GLOBAL)
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
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010219a10)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffff800010219a10-ffff800010219e70: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (c0457e1c)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
c0457e1c-c0458218: ring_buffer_resize.part.0 (STB_LOCAL)
c0458218-c045826c: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029b9a0)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
c00000000029b9a0-c00000000029bf24: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000178af6)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffe000178af6-ffffffe000178e94: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198760)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff81198760-ffffffff81198af8: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff81198b00-ffffffff81198b24: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118bc70)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff8118bc70-ffffffff8118c008: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff8118c010-ffffffff8118c034: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196530)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff81196530-ffffffff811968c8: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811968d0-ffffffff811968f4: ring_buffer_resize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ring_buffer_resize(struct ring_buffer *buffer, long unsigned int size, int cpu_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a4140)
Location: kernel/trace/ring_buffer.c:1715
Inline: True
Direct callers:
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:__tracing_resize_ring_buffer
  - kernel/trace/trace.c:free_snapshot
```
**Symbols:**

```
ffffffff811a4140-ffffffff811a44d8: ring_buffer_resize.part.0 (STB_LOCAL)
ffffffff811a44e0-ffffffff811a4504: ring_buffer_resize (STB_GLOBAL)
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
